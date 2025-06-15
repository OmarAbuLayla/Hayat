# Hayat – Context-Aware Medical LLM Assistant

Hayat AI is a modular, context-aware medical assistant powered by advanced AI. It integrates diagnostic imaging and language models to deliver accurate, explainable, and grounded medical responses and built with open-source tools and deployable as a lightweight API.

---

## Features

- Medical Image Classification: Detects abnormalities in X-ray and MRI scans using a deep learning model.
- RAG Pipeline (Retrieval-Augmented Generation): Combines a vector search (FAISS) with a medical knowledge base for grounded LLM responses.
- LLM-based Medical Explanation: Translates raw diagnoses into human-readable insights using fine-tuned prompts.
- RESTful API (Flask): Easily integrates into web apps, mobile tools, or hospital systems.
- Modular Design: Each component (vision, retrieval, language) is independently testable and replaceable.

---

## Tech Stack

Component                | Stack
------------------------|-------------------------------
Image Diagnosis         | CNN trained on medical datasets
Embedding               | SentenceTransformers (`all-MiniLM-L6-v2`)
Vector DB               | FAISS
LLM                     | Open-source model
API                     | Flask
Deployment              | ngrok / Hugging Face Spaces

---

## Example Usage

1. Upload a medical image to `/predict`
2. Receives a diagnosis (e.g., "pituitary_tumor")
3. Automatically sent to the LLM endpoint `/custom`
4. Response: "The tumor is located in the pituitary gland, which may affect hormonal regulation..."

---

## Ethics & Responsibility

This project is intended for educational and prototyping purposes only. It must not be used for real medical decision-making without supervision by qualified professionals.

---

## Contributors

Omar Abu Layla – Biomedical Engineer | AI Developer  
Portfolio: https://omarabulayla.github.io/portfolio/  
LinkedIn: https://linkedin.com/in/omar-abulayla

---

## Future Enhancements

- Improve multi-label classification for overlapping conditions
- Add speech-to-text support for mobile interface
- Expand KB with real medical guidelines (e.g., WHO, UpToDate)
- Dockerize for easier deployment

---
## Demo

Check out the full walkthrough of Hayat AI in action:

[![Hayat AI Demo](https://img.youtube.com/vi/0/0.jpg)](https://youtu.be/7dbw4ZcwMBM)

 [Click here to watch the Hayat AI demo video](https://youtu.be/7dbw4ZcwMBM)

