# QR Code Generator

A simple Python program that generates QR codes from text or URLs and saves them as images. Perfect for quickly creating QR codes for links, contact info, or any text.

## Features

- Generate QR codes from user input (text or URLs)
- Save QR codes as `.png` images
- Customizable QR code size, border, and error correction level
- Works with any platform that runs Python

## Installation

1. Make sure you have Python 3 installed.
2. Install the required library:

```bash
pip install qrcode[pil]
```
---
> `[pil]` ensures the program can create image files using Pillow.

## Usage

1. Run the Python script:

```bash
python qr_code_generator.py
```
2. Enter the text or URL you want to encode when prompted.

3. The QR code will be saved as my_qrcode.png in the current folder (or a folder you specify).
## Example

Enter the data or URL for the QR Code: https://github.com/mibrahim-O2
QR Code successfully saved as my_qrcode.png!

Scan this QR code to visit my GitHub profile:

![QR Code Example](https://raw.githubusercontent.com/mibrahim-O2/Modern-Python/main/Projects/QR-Code-Generator/my_qrcode.png)


