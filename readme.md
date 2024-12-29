# Image Compression Tool

A simple and effective browser-based tool to compress your images instantly. No installation needed - just upload and compress!

Try it out here: [Image Compression Tool](https://mahmoudfahmyemam.github.io/Multimedia_Bonus/index.html)

## What does it do?

This tool helps you reduce image file sizes while keeping good quality. Upload any image over 2MB and get three different compressed versions:
- Light compression (75%)
- Medium compression (50%)
- Heavy compression (25%)

You can see all versions side by side and download whichever one works best for you.

## Main Features

- Works right in your browser - no need to install anything
- Drag and drop your images or click to upload
- See instant previews of compressed versions
- Download any compressed version with one click
- Shows you how much space you saved
- Works on phones and computers
- Clean, modern design that's easy to use

## How to Use It

1. Visit the [compression tool website](https://mahmoudfahmyemam.github.io/Multimedia_Bonus/index.html)
2. Drop your image onto the upload box (or click to choose a file)
3. Wait a moment while the tool creates compressed versions
4. Compare the different versions
5. Download the one you like best

Note: Your image needs to be at least 2MB in size for the tool to work properly.

## Run it Locally

Want to run it on your computer? Easy:

```bash
git clone https://github.com/MahmoudFahmyEmam/Multimedia_Bonus.git
cd Multimedia_Bonus
```

Then just open `index.html` in your web browser. That's it!

## Supported Browsers

The tool works great on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Want to Make Changes?

### Change the compression levels
Find this line in the code:
```javascript
const percentages = [0.75, 0.5, 0.25];
```

### Change the minimum file size
Look for:
```javascript
const MIN_FILE_SIZE = 2 * 1024 * 1024; // 2MB in bytes
```

### Change the colors
Find the `:root` section in the CSS:
```css
:root {
    --primary: #4F46E5;
    --background: #F9FAFB;
    /* other colors... */
}
```

## Contributing

Found a bug? Want to add a feature? Great! Feel free to:
1. Fork the repo
2. Create your feature branch
3. Make your changes
4. Submit a pull request

## License

This project is under the MIT License - use it however you like!
