# GitHub Profile QR Code Generator

## About the Project
This project generates a QR code that links directly to my GitHub profile. By scanning the QR code with a smartphone, users can easily visit my GitHub page.

The project was developed using Python and the `qrcode` library.

## Technologies Used
- Python
- Qrcode Library
- Jupyter Notebook

## Features
- Generates a QR code from a URL.
- Links directly to my GitHub profile.
- Displays the generated QR code.
- Saves the QR code as a PNG image.

## Code Example

```python
import qrcode as qr

img = qr.make("https://github.com/MinooJafari")

img.show()
img.save("github_qrcode.png")
```

## How to Run
1. Install the required library:

```bash
pip install qrcode[pil]
```

2. Run the Python code.
3. Scan the generated QR code to visit my GitHub profile.

## Learning Objectives
- Working with Python libraries.
- Generating QR codes.
- Converting URLs into QR codes.
- Saving and displaying images using Python.

