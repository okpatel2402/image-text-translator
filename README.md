# Image Text Extraction and Translation

This python script facilitates the extraction and translation of text from images. It uses libraries such as OpenCV, Pytesseract, Googletrans, and Matplotlib for image preprocessing, text extraction and translation to English

## Features

- **Image Upload**: Allows user upload images for text extraction and translation.
- **Preprocessing**: Automatically preprocesses uploaded images for optimal text extraction.
- **Multilingual Text Extraction**: Supports multiple languages for text extraction using Pytesserat.
- **Translation**: Translates extracted text into English using Google Translate.

## Installation

To run this script make sure you have python installed on your system. You also need to install the required libraries. You can do this by running:

```bash
pip install opencv-python-headless numpy pytesseract pillow matplotlib googletrans==4.0.0-rc1
```

## Usage
1. **Upload Images**: Run the script and upload images containg the text you want to extract and translate.
2. **Select Image**: Choose the image you want to process from the list of uploaded images.
3. **View Results**: The script will display the original image, the preprocessed image, detected text, and translated text.

## Acknowledgments

- [OpenCV](https://opencv.org/)
- [Pytesseract](https://github.com/madmaze/pytesseract)
- [Googletrans](https://py-googletrans.readthedocs.io/en/latest/)
