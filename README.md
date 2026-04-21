# OCR + RAG Question Answering System

An AI system that extracts text from images using OCR and answers questions using a QA model.

## Tech Stack
- Python
- pytesseract (OCR)
- Pillow (image processing)
- LlamaIndex (document indexing)
- Transformers / DistilBERT (QA model)
- Gradio (UI)

## How to Run
1. Install dependencies
pip install pytesseract Pillow llama-index gradio transformers sentence-transformers llama-index-embeddings-huggingface
apt-get install -y tesseract-ocr

2. Run the notebook on Google Colab

## Usage
1. Upload an image
2. Click "Extract & Add to Index"
3. Click "Build Index"
4. Go to "Ask Questions" tab and type your question
