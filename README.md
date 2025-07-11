# Hand Gesture Drawing App

A web-based application that allows you to draw on your screen using hand gestures detected through your webcam.

## Features

- **Real-time hand gesture detection** using MediaPipe
- **Simplified gesture detection** (index finger pointing + open palm)
- **Manual tool and color selection** via UI buttons
- **Eraser tool** for removing drawn content
- **Palm eraser** with distance-based sizing and visual preview
- **Enhanced color palette** with 12 solid colors
- **Custom color picker** with hex code input
- **Gradient brushes** (Rainbow, Sunset, Ocean, Forest)
- **Adjustable brush size** (1-30 pixels)
- **Full-screen webcam display** with mirrored view
- **Simple gesture guide**
- **Toggle drawing** on/off

## How to Use

1. Open `index.html` in a modern web browser (Chrome, Firefox, Safari)
2. Allow camera permissions when prompted
3. Use gestures and controls:
   - **Point** with your index finger to draw or erase (based on selected tool)
   - **Open palm** for palm eraser - closer to camera = larger eraser
   - **Click UI buttons** to change tools, colors, and settings
   - **Any other gesture** stops drawing
4. Use the controls on the right to:
   - Change colors by clicking color buttons
   - Adjust brush size with the slider
   - Clear the canvas
   - Toggle drawing on/off

## Gestures (Enhanced)

- **👆 Point**: Extend your index finger to draw/erase (other fingers can be relaxed)
- **🖐️ Open Palm**: Extend 4-5 fingers for palm eraser with distance-based sizing
- **✋ Any Other**: Stop drawing - make any other gesture or hide your hand

## Palm Eraser Features

- **Distance-based sizing**: Move hand closer to camera for larger eraser, farther for smaller
- **Visual preview**: Red dashed circle shows eraser area before touching canvas
- **Real-time feedback**: Shows hand proximity and eraser size in bottom-left
- **Smooth erasing**: Large area erasing for quick corrections

## Controls & Features

### Drawing Tools
- **🖌️ Brush**: Draw with selected color/gradient
- **🧹 Eraser**: Remove drawn content with adjustable size

### Colors & Gradients
**Solid Colors:**
- 12 preset colors including primary colors, black, white, and vibrant shades

**Gradient Brushes:**
- 🌈 **Rainbow**: Full spectrum gradient
- 🌅 **Sunset**: Warm orange/yellow tones  
- 🌊 **Ocean**: Cool blue gradient
- 🌲 **Forest**: Green nature tones

**Custom Colors:**
- 🎨 **Color Picker**: Visual color selection wheel
- 🔢 **Hex Input**: Enter exact hex codes (e.g., #FF5733)
- ⚡ **Quick Apply**: Use Enter key or Apply button
- 🔄 **Auto-Sync**: Color picker and hex input stay synchronized

### Brush Settings
- **Size Slider**: Adjust brush/eraser size from 1-30 pixels
- **Clear Canvas**: Remove all drawings instantly
- **Toggle Drawing**: Enable/disable drawing functionality

## Browser Requirements

- Modern web browser with WebGL support
- Camera access permissions
- Stable internet connection (for MediaPipe CDN)

## Technical Details

- Built with HTML5, CSS3, and JavaScript
- Uses MediaPipe Hands for gesture detection
- Canvas API for drawing functionality with gradient support
- Composite operations for eraser functionality
- Optimized gradient caching system
- Responsive design for different screen sizes

## Tips for Best Experience

1. **Lighting**: Ensure good lighting for optimal hand detection
2. **Background**: Plain backgrounds work better for gesture recognition
3. **Distance**: Keep your hand 1-2 feet from the camera
4. **Gestures**: Make clear, distinct gestures for better recognition
5. **Performance**: Close other camera applications for better performance

## Troubleshooting

- **Camera not working**: Check browser permissions and ensure no other apps are using the camera
- **Gestures not detected**: Improve lighting and make sure your hand is clearly visible
- **Performance issues**: Try refreshing the page or closing other browser tabs
- **Gradients not working**: Ensure you have a modern browser with full Canvas API support

Enjoy creating digital art with your hands! 🎨✋🌈
