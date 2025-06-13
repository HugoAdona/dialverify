# DialVerify

A comprehensive telephone number validator for validating phone numbers across different formats and regions.

## 🚀 Features

- **Multi-format Support**: Validates various phone number formats including:
  - `(555) 123-4567`
  - `555-123-4567`
  - `555 123 4567`
  - `5551234567`
  - `1 555 123 4567`
  - `+1 (555) 123-4567`

- **Flexible Validation**: Supports US phone number validation with optional country code
- **Clean Interface**: Simple and intuitive user interface
- **Real-time Validation**: Instant feedback on phone number validity
- **Cross-platform**: Works on web browsers and mobile devices

## 📋 Requirements

- Modern web browser with JavaScript support
- No additional dependencies required

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/HugoAdona/dialverify.git
```

2. Navigate to the project directory:
```bash
cd dialverify
```

3. Open `index.html` in your web browser or serve it using a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

## 🎯 Usage

### Basic Usage

1. Open the application in your web browser
2. Enter a phone number in the input field
3. Click the "Validate" button or press Enter
4. The validator will display whether the number is valid or invalid

### Supported Formats

The validator accepts the following US phone number formats:

- `555-555-5555`
- `(555)555-5555`
- `(555) 555-5555`
- `555 555 5555`
- `5555555555`
- `1 555 555 5555`
- `1 (555) 555-5555`
- `1(555)555-5555`

### Invalid Examples

- `555-5555` (too short)
- `5555555` (too short)
- `1 555)555-5555` (invalid format)
- `123**&!!asdf#` (invalid characters)
- `55555555555555555555` (too long)

## 🔧 API Reference

### JavaScript Functions

#### `validatePhoneNumber(number)`
Validates a given phone number string.

**Parameters:**
- `number` (string): The phone number to validate

**Returns:**
- `boolean`: `true` if valid, `false` if invalid

**Example:**
```javascript
const result = validatePhoneNumber("(555) 123-4567");
console.log(result); // true
```

## 🧪 Testing

The project includes comprehensive test cases covering:

- Valid US phone number formats
- Invalid phone number formats
- Edge cases and special characters
- Country code validation

To run tests (if applicable):
```bash
# Add your testing framework command here
npm test
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Hugo Adona**
- GitHub: [@HugoAdona](https://github.com/HugoAdona)

## 🙏 Acknowledgments

- Inspired by the FreeCodeCamp JavaScript Algorithms and Data Structures certification
- Built as part of the Telephone Number Validator project
- Thanks to the open-source community for inspiration and resources

## 📞 Support

If you have any questions or run into issues, please open an issue on GitHub or contact the maintainer.

---

*Made with ❤️ by Hugo Adona*