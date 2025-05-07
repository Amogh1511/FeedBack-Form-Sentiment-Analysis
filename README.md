# FeedBack-Form-Sentiment-Analysis
A real-time web application that extracts text from uploaded docx, pdf, jpg, or png feedback files using OCR and analyzes the sentiment (positive, negative, or neutral) using a pre-trained multilingual BERT model. Built UI with Streamlit 

Tools Used
Hugging Face Transformers (nlptown/bert-base-multilingual-uncased-sentiment)
Streamlit (for UI)
Tesseract OCR (for text extraction)
PyMuPDF (for PDF processing)
python-docx (for DOCX processing)
PIL/OpenCV (for image handling)

Model Working 
The user uploads a feedback file. The app extracts the text using OCR or file parsers, processes the text, and uses a pre-trained BERT model to classify the sentiment. The result is shown instantly on the Streamlit interface.

Steps
Upload feedback file (image, PDF, or DOCX)
Extract text using OCR or text parsers
Clean and preprocess text
Analyze sentiment using the BERT model
Display sentiment result on the interface
