# 🥔 Potato WebGrabber

Potato WebGrabber is a fancy offline website downloader with a fun potato-themed GUI.  
It lets you save the main HTML page of any website for offline use, complete with a custom banner and progress bar.

## Features

- Stylish potato-inspired dark UI with custom colors and ASCII art
- Downloads website HTML and adds an offline warning banner
- Shows a progress bar during download
- Easy to use — just paste a URL and click Download

## Requirements

- Python 3.8+
- PyQt6
- requests

## Installation

`pip install PyQt6 requests`

## Usage

`python potato_webgrabber.py`

1. Enter the website URL (must start with `http://` or `https://`)
2. Click **Download Website**
3. Wait for the progress bar to finish
4. Find the downloaded site in a folder named after the domain (e.g., `example.com/index.html`)

## Limitations

- Currently downloads only the main HTML page, no linked resources (images, CSS, JS)
- Online functions in the downloaded page will show an offline warning

## License

This project is licensed under the MIT License. Feel free to fork and customize!

---

Made with 🥔 by PotatoKing 👑  
[bit.ly/potatokingz](https://bit.ly/potatokingz)
