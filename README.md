# AI Attention Visualizer

## Project Overview

AI Attention Visualizer is a beginner-friendly AI application that extracts text from study-note images using OCR, converts words into numerical embeddings, and visualizes attention scores.

The application uses Streamlit to provide a simple web interface where users can upload images and view the extracted text and word attention bars.

## Technologies Used

* Python
* Streamlit
* Tesseract OCR
* Pytesseract
* Sentence Transformers
* NumPy
* Pillow

## Features

* Upload study-note images in JPG, JPEG, and PNG formats.
* Extract text from images using OCR.
* Convert words into numerical embeddings.
* Calculate attention scores using scaled dot-product attention.
* Visualize word attention using progress bars.
* Display the word with the highest attention score.

## Project Structure

```text
AI-Attention-Visualizer/
│
├── app.py
├── ocr.py
├── embedding.py
├── attention.py
├── requirements.txt
└── README.md
```



## Project Workflow

Image Upload → OCR Text Extraction → Word Processing → Embeddings → Attention Calculation → Visualization

## Output
<img width="230" height="413" alt="image" src="https://github.com/user-attachments/assets/7cb5c840-3bd6-4f9e-8038-8d4670c69b6d" />


## Learning Outcomes

* Understanding Optical Character Recognition (OCR).
* Learning how text embeddings represent words numerically.
* Understanding Query, Key, and Value in attention.
* Implementing scaled dot-product attention.
* Building an interactive AI application using Streamlit.


## Conclusion

AI Attention Visualizer demonstrates how OCR, text embeddings, and an attention mechanism can be combined in a simple AI application. It provides a practical introduction to text processing and attention visualization.
