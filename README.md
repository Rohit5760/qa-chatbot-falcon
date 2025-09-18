# 💬 Q&A Chatbot (Falcon + FAISS)  
  

A **multimodal Q&A chatbot** capable of handling **text, PDFs, images, audio, and video** as input.  
It uses **PDFMiner** for PDF text extraction, **PyTesseract** for OCR on images, **Whisper** for speech-to-text, **FAISS** for efficient knowledge retrieval, and **Falcon-3B-Instruct** for generating context-aware answers, all deployed via **Gradio**.  

---

## ✨ Features
- 📄 **PDF Support**: Extracts text from documents using PDFMiner.  
- 🖼️ **Image OCR**: Processes images with PyTesseract to extract text.  
- 🎙️ **Speech-to-Text**: Converts audio/video input into text with Whisper.  
- 📊 **Vector Database**: Uses FAISS for efficient storage and retrieval of embeddings.  
- 🤖 **Answer Generation**: Powered by Falcon-3B-Instruct for natural and accurate responses.  
- 💻 **Interactive Interface**: Deployed with Gradio for easy interaction.  

---

## 🛠 Tech Stack
- **Python**  
- **PDFMiner** for PDF text extraction  
- **PyTesseract** for image OCR  
- **Whisper** for speech-to-text  
- **FAISS** for vector database search  
- **Falcon-3B-Instruct** (Hugging Face)  
- **Gradio** for deployment  

---

## 🔄 How It Works (Pipeline)
1. User uploads **text, PDF, image, audio, or video**.  
2. If PDF → process with **PDFMiner**.  
3. If image → extract text with **PyTesseract**.  
4. If audio/video → convert to text with **Whisper**.  
5. Extract embeddings and store/retrieve with **FAISS**.  
6. Use **Falcon-3B-Instruct** to generate context-aware answers.  
7. Display final answer in **Gradio interface**.  

---

## 📖 References
- 🔗 [Falcon-3B-Instruct (Hugging Face)](https://huggingface.co/tiiuae/Falcon3-1B-Instruct)  
- 🔗 [Whisper](https://github.com/openai/whisper)  
- 🔗 [PDFMiner](https://github.com/euske/pdfminer)  
- 🔗 [PyTesseract](https://pypi.org/project/pytesseract/)  
- 🔗 [FAISS](https://github.com/facebookresearch/faiss)  
- 🔗 [Gradio](https://www.gradio.app/)  
- 🔗 [Hugging Face Transformers](https://huggingface.co/transformers/)  

---

## ⚠️ Disclaimer
This project is for **educational purposes only** and not intended for production deployment without further improvements.
