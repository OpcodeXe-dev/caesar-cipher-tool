# Caesar Cipher Tool

A simple and interactive web application for encrypting and decrypting text using Caesar cipher algorithm. This tool allows you to encode your messages with customizable shift values and visualize how the cipher works.

## Features

The tool comes with several features that makes it easy to use:

- **Encrypt/Decrypt Functionality**: You can encrypt your text or decrypt cipher text with just one click
- **Adjustable Shift Value**: The shift value can be adjusted from 0 to 25 using a slider control
- **Alphabet Animation**: Visualize how the alphabet shifts with the current shift value - this helps understanding the cipher better
- **Dark Mode**: Toggle between light and dark themes for comfortable viewing
- **Sample Text**: Insert sample texts to quickly test the functionality
- **Copy to Clipboard**: Easily copy the encrypted or decrypted result
- **Character Counter**: See how many characters are in your input and output text
- **Responsive Design**: Works well on both desktop and mobile devices

## How It Works

Caesar cipher is one of the simplest encryption techniques where each letter in the plaintext is shifted a certain number of places down the alphabet. For example, with a shift of 3, 'A' becomes 'D', 'B' becomes 'E', and so on. When you reach the end of alphabet, it wraps around to the beginning.

The tool handles both uppercase and lowercase letters while preserving the case. Non-alphabetic characters like numbers, spaces, and punctuation marks are left unchanged.

## Usage

1. Open the `index.html` file in your web browser
2. Enter the text you want to encrypt or decrypt in the "Original Text" field
3. Adjust the shift value using the slider (default is 3)
4. Click "Encrypt" to encode your text or "Decrypt" to decode it
5. The result will appear in the "Result" field
6. You can click "Copy" button to copy the result to your clipboard
7. Use "Animate" button to see visual representation of how the alphabet shifts
8. Toggle the theme switch to change between light and dark mode

## Files Structure

The project consists of three main files:

- `index.html` - The main HTML structure of the application
- `style.css` - All the styling and theme definitions
- `script.js` - The JavaScript logic for encryption, decryption, and UI interactions

## Technical Details

The encryption algorithm works by:
1. Taking each alphabetic character in the input text
2. Determining whether it's uppercase or lowercase
3. Shifting the character by the specified number of positions
4. Wrapping around if the shift goes beyond 'Z' or 'z'
5. Preserving non-alphabetic characters as they are

The theme preference is saved in browser's localStorage so your choice persists between sessions.

## Browser Compatibility

This tool should work on all modern web browsers that supports:
- ES6 JavaScript features
- CSS Grid and Flexbox
- LocalStorage API
- Font Awesome icons (loaded via CDN)

## Future Improvements

Some ideas for future enhancements includes:
- Frequency analysis to help crack unknown ciphers
- Support for multiple cipher types
- Export/import functionality
- History of previous encryptions
- Custom alphabet support

## License

This project is open source and available for anyone to use and modify as needed.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or found any bugs. All contributions are welcome!

---

**Note**: This tool is for educational purposes only. Caesar cipher is not secure for real-world encryption needs and should not be used for protecting sensitive information.
