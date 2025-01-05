QR Code Generator
This project is a simple QR code generator built using Node.js. It allows users to input a URL and generates a QR code image, saving it to a file. The entered URL is also stored in a text file for reference.

Features
- **Generate QR Codes**: Converts user-entered URLs into QR codes.
- **Save Input**: Saves the entered URL in a text file.
- 
## Technologies Used
- [Node.js](https://nodejs.org/): JavaScript runtime for building server-side applications.
- [Inquirer](https://www.npmjs.com/package/inquirer): CLI library for interactive user input.
- [qr-image](https://www.npmjs.com/package/qr-image): QR code generation library.
- [fs](https://nodejs.org/api/fs.html): Native Node.js module for file system operations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/qr-code-generator.git
   cd qr-code-generator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

---

## Usage

1. Run the application:
   ```bash
   node index.js
   ```

2. Follow the prompt to enter a URL.
3. The application will:
   - Save the QR code as an image file (`qr_img.png`).
   - Save the entered URL to a text file (`URL.txt`).
