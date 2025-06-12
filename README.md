# Image Encryption & Decryption Tool 🔐

A simple, unique, and beginner-friendly image encryption tool using pixel-level XOR manipulation.

Developed as part of my learning journey to explore basic cryptography, image processing, and Python programming.

## 🔧 Features

- XOR-based symmetric encryption & decryption
- Supports most image formats (JPG, PNG, BMP, etc.)
- Class-based design for clean and scalable code
- User-friendly console interface
- Fully open-source and GitHub-ready 🚀

## 🚀 How It Works

- Each pixel's RGB values are XORed with a user-provided key (0-255)
- XOR encryption is symmetric: applying XOR again with the same key decrypts the image
- Non-destructive: original image remains unchanged

## 📦 Dependencies

- Python 3.6+
- Pillow (`pip install pillow`)

## 💻 Usage

### Clone the repository

```bash
git clone https://github.com/yourusername/image-encryption-tool.git
cd image-encryption-tool
