# Simple Image Generator

A lightweight web application that allows you to create custom images with text overlays and download them instantly.

## Features

- **Custom Dimensions**: Set any width and height for your image (50-2000 pixels)
- **Text Overlay**: Add custom text that automatically centers on the image
- **Color Customization**: Choose both background and text colors using color pickers
- **Smart Text Sizing**: Text automatically scales to fit the image dimensions
- **Custom Filenames**: Specify your own filename when downloading
- **Instant Download**: One-click download as PNG format

## How to Use

1. **Set Image Dimensions**
   - Enter desired width in pixels (50-2000)
   - Enter desired height in pixels (50-2000)

2. **Add Your Text**
   - Type the text you want to display in the "Text to display" field
   - Text will be automatically centered on the image

3. **Choose Colors**
   - Select background color using the color picker
   - Select text color using the color picker

4. **Set Filename**
   - Enter your desired filename (without extension)
   - Default filename is "my-image"

5. **Generate and Download**
   - Click "Generate Image" to create your image
   - Click "Download Image" to save it to your device

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses HTML5 Canvas API for image generation
- No external dependencies or frameworks required
- Responsive design that works on desktop and mobile
- Automatic font sizing algorithm ensures text fits properly

## Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas
- Color input type
- File download via data URLs

## File Structure

The application is contained in a single HTML file with embedded CSS and JavaScript, making it easy to save and run locally.

## Usage Examples

**Creating a Social Media Banner:**
- Width: 1200px, Height: 630px
- Text: "Follow us @username"
- Background: Brand color
- Filename: "social-banner"

**Making a Simple Logo:**
- Width: 500px, Height: 500px  
- Text: "Company Name"
- Background: White, Text: Black
- Filename: "company-logo"

**Generating a Placeholder Image:**
- Width: 800px, Height: 600px
- Text: "Coming Soon"
- Background: Gray, Text: White
- Filename: "placeholder"
