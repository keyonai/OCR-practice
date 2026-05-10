# OCR Practice — Comparing Tesseract, PaddleOCR, and EasyOCR

Hands-on comparison of three OCR (Optical Character Recognition) engines — TesseractOCR, PaddleOCR, and EasyOCR — using real document images. Each engine is tested for accuracy and output quality, with bounding boxes drawn around detected text regions using OpenCV.

## What it does

- Runs the same document images through all three OCR engines
- Draws bounding boxes around detected text using OpenCV
- Compares accuracy and output format across engines
- Handles PDF-to-image conversion via PyMuPDF

## Stack

- Python
- TesseractOCR
- PaddleOCR
- EasyOCR
- OpenCV
- PyMuPDF
- NumPy / Pillow / Matplotlib / Regex

## Setup

```bash
pip install pytesseract paddleocr easyocr opencv-python pymupdf numpy pillow matplotlib
```

> **Note:** PaddleOCR has compatibility issues with Python 3.12. Use Python 3.10 or 3.11 for full compatibility.

## Files

| File | Description |
|------|-------------|
| `OCR_practice.ipynb` | Initial OCR experiments with all three engines |
| `KeyonaiWilliams_Compare_3_OCR.ipynb` | Head-to-head comparison with bounding box visualization |

## Sample output

Each engine returns detected text with bounding box coordinates. OpenCV draws rectangles around each detected region for visual verification.
