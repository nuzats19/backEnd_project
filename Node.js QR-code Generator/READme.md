# Node.js QR Code Generator

A sleek Node.js CLI app that turns any URL into a QR code with interactive prompts and clean file handling.

## 📌 Overview
This project is a simple but powerful command-line application that:
- Accepts user input for a URL via interactive prompts.
- Generates a QR code in PNG format from the given URL.
- Saves the original URL to a text file for future reference.

## 🚀 Features
- **Interactive CLI prompts** using [Inquirer.js](https://www.npmjs.com/package/inquirer).
- **QR code generation** with [qr-image](https://www.npmjs.com/package/qr-image).
- **File I/O** using Node’s native `fs` module.
- Lightweight and dependency-minimal.
- Easy to extend and customize.

---

## 🛠️ Technologies Used
- **Node.js** — JavaScript runtime environment.
- **Inquirer.js** — for command-line interaction.
- **qr-image** — for creating QR codes.
- **fs** (File System) — for saving files locally.

---

## 📂 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nodejs-qr-code-generator.git
   cd nodejs-qr-code-generator
