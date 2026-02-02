# 🎴 Grok-N-Talk Card Generator

A user-friendly web interface for generating custom flip cards that match the Grok-N-Talk card style.

## 🚀 Quick Start

1. Open `card-generator.html` in your web browser
2. Fill in the card configuration fields
3. Watch the live preview update in real-time
4. Click "Generate HTML" to create the code
5. Click "Copy to Clipboard" to copy the HTML snippet
6. Paste the code into your `index.html` file

## 📋 Features

### ✨ Real-Time Preview
- Live preview updates as you type
- Click the preview card to flip it and see both sides
- Visual feedback for all changes

### 🎨 Customization Options

#### Basic Settings
- **Card CSS Class Name**: Custom class for styling (e.g., "turbo", "instana")

#### Front Face
- **Logo Image URL**: Path to your logo image
- **Subtitle**: Optional subtitle text (e.g., "IBM")
- **Main Title**: Primary card title
- **Background Image URL**: Optional background image
- **Background Color**: Color picker for background

#### Back Face
- **Banner Image URL**: Top banner image
- **Banner Alt Text**: Accessibility text for banner
- **Description Content**: HTML content for the card back
- **Background Color**: Color picker for back face

### ✅ Validation & Error Handling
- Required field validation (Title)
- URL format validation
- CSS class name validation
- Visual error indicators (red borders)
- User-friendly error messages

### 📄 HTML Generation
- Clean, formatted HTML output
- Inline styles for portability
- Compatible with existing card structure
- Ready to paste into your project

## 🎯 Usage Examples

### Example 1: Basic Card
```
Card Class: my-product
Logo: images/my-logo.png
Title: My Product
Subtitle: IBM
```

### Example 2: Card with Background Image
```
Card Class: custom-card
Logo: images/logo.png
Title: Custom Product
Background Image: images/product-bg.png
Background Color: #101010
```

### Example 3: Full Customization
```
Card Class: special-card
Logo: images/special-logo.png
Title: Special Product
Subtitle: Company Name
Front BG Image: images/front-bg.png
Front BG Color: #1a1a1a
Banner: images/banner.png
Back BG Color: #003566
Description: <ul><li>Feature 1</li><li>Feature 2</li></ul>
```

## 🔧 Technical Details

### File Structure
- **Standalone HTML**: No external dependencies
- **Inline CSS**: All styles included
- **Inline JavaScript**: All functionality included
- **Jekyll Compatible**: Works with GitHub Pages

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Clipboard API with fallback support
- Responsive design for desktop and tablet

### Card Dimensions
- Default: 400px × 600px
- Border radius: 10px
- Flip animation: 0.5s

## 🎨 Styling Tips

### Color Schemes
- **Dark Theme**: Use dark backgrounds (#101010, #1a1a1a)
- **Accent Colors**: Use #B3D0F5 for primary text, #FFC294 for emphasis
- **Back Face**: Typically uses #003566 or similar blue tones

### Image Guidelines
- **Logo**: 200px width recommended
- **Banner**: Full width, 10% height
- **Background**: 400px × 600px for best fit
- **Format**: PNG with transparency recommended

### Content Best Practices
- Keep titles concise (1-3 words)
- Use bullet points for features
- Include links where appropriate
- Test both card faces for readability

## 🐛 Troubleshooting

### Preview Not Updating
- Check browser console for errors
- Ensure all URLs are valid
- Refresh the page and try again

### Copy to Clipboard Not Working
- Generate HTML first before copying
- Check browser permissions for clipboard access
- Try using Ctrl+C (Cmd+C on Mac) as fallback

### Card Not Displaying Correctly
- Verify image URLs are accessible
- Check that colors are in valid hex format
- Ensure HTML in description is properly formatted

## 📝 Integration with index.html

1. Generate your card HTML using the generator
2. Copy the generated code
3. Open `index.html`
4. Find the section with other cards (look for `<div class="card">`)
5. Paste your new card code
6. Add any custom CSS for your card class to the `<style>` section
7. Save and test

### Adding Custom Styles

If you need custom hover effects or animations, add them to the `<style>` section in `index.html`:

```css
.my-custom-card .front {
    background-image: url(images/my-bg.png);
    background-size: 100%;
    background-position: 50% 50%;
    transition: background 0.3s;
}

.my-custom-card .front:hover {
    background-size: 200%;
    background-position: 20% 30%;
    transition: background 0.5s;
}
```

## 🔄 Updates & Maintenance

### Version History
- **v1.0** (2026-02-02): Initial release
  - Basic card generation
  - Real-time preview
  - Validation and error handling
  - Copy to clipboard functionality

### Future Enhancements
- Template library with pre-built cards
- Advanced content sections (competitors, stories, etc.)
- Export as separate HTML file
- Batch card generation
- Custom CSS editor
- Image upload functionality

## 📞 Support

For issues or questions:
1. Check this documentation
2. Review the troubleshooting section
3. Inspect the browser console for errors
4. Test with default values to isolate the issue

## 📄 License

This tool is part of the Grok-N-Talk project and follows the same license.

---

**Happy Card Creating! 🎴✨**