# RSA Algorithm Demo

## Overview
This project is a simple web-based demonstration of the RSA algorithm, a public-key cryptography system used for secure data transmission. The application allows users to input two prime numbers (P and Q) and a numeric message, then performs RSA encryption and decryption to showcase the algorithm's functionality.

## Features
- **Input Fields**: Enter two prime numbers (P and Q) and a numeric message.
- **RSA Process**: Computes the public and private keys, encrypts the message, and decrypts it.
- **Educational Content**: Provides an overview of the RSA algorithm, its advantages, and disadvantages.
- **Interactive UI**: Simple HTML-based interface for ease of use.

## How It Works
1. **Input Prime Numbers**: Users provide two prime numbers, P and Q, which are used to generate the public and private keys.
2. **Input Message**: A numeric message is entered for encryption.
3. **Run RSA**: Clicking the "Run RSA" button triggers the RSA algorithm to:
   - Calculate the modulus (N = P × Q) and totient (φ(N) = (P-1) × (Q-1)).
   - Generate the public key (e) and private key (d).
   - Encrypt the message using the public key.
   - Decrypt the message using the private key.
4. **Output**: Displays the encrypted and decrypted messages.

## Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- Basic understanding of RSA cryptography (optional, but helpful for context).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rsa-algorithm-demo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd rsa-algorithm-demo
   ```
3. Open `index.html` in a web browser to run the application locally.

## Usage
1. Open `index.html` in a browser.
2. Enter two prime numbers (P and Q) in the provided input fields.
3. Enter a numeric message to encrypt.
4. Click the "Run RSA" button to see the encryption and decryption results.

## File Structure
- `index.html`: The main HTML file containing the UI and RSA logic.
- (Add other files like `style.css` or `script.js` if applicable in your project.)

## Limitations
- The demo is designed for educational purposes and uses small prime numbers for simplicity.
- The message must be a numeric value to work with the RSA algorithm in this implementation.
- The application does not handle non-prime inputs or invalid messages gracefully (consider adding validation for production use).

## Future Improvements
- Add input validation to ensure P and Q are prime numbers.
- Support text-based messages by converting them to numeric values.
- Include a visual step-by-step breakdown of the RSA process.
- Enhance the UI with CSS styling and responsive design.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure your code follows the project's structure and includes appropriate documentation.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The RSA algorithm was developed by Ron Rivest, Adi Shamir, and Leonard Adleman.
- Built with HTML and JavaScript for simplicity and accessibility.