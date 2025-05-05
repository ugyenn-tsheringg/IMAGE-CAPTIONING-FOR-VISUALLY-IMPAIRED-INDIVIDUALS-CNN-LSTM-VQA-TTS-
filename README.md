# Image Captioning Website for Visually Impaired Individuals

## 📝 Overview
This project develops a **web-based image captioning system** integrated with **Visual Question Answering (VQA)** and **Text-to-Speech (TTS)** functionalities to enhance accessibility for visually impaired users. It leverages **CNN-LSTM architectures with soft attention**, **pre-trained BLIP models** for VQA, and TTS tools like **gTTS** or **pyttsx3**. The system aims to:

- Generate descriptive image captions
- Answer image-related user questions
- Convert outputs to audio
- Offer a user-friendly web interface

---

## ✨ Features

- **Image Captioning**: Generates descriptive captions using CNN-LSTM with soft attention; compares feature extractors like ResNet-101, VGGNet16, and Inception-v3.
- **Visual Question Answering (VQA)**: Enables users to ask image-related questions powered by the pre-trained **BLIP** model.
- **Text-to-Speech (TTS)**: Converts captions and VQA answers into audio using **gTTS** or **pyttsx3** for accessibility.
- **Web Interface**: Upload images, display captions/VQA answers, and play audio. Built using **HTML5**, **CSS**, **JavaScript**, and **Flask**.
- **Evaluation**: Model performance assessed using **BLEU**, **CIDEr**, and **ROUGE** scores; usability feedback gathered from visually impaired users.

---

## 🚧 Project Status
**Under active development** as part of an internship application.

### Current focus:
- Implementing the CNN-LSTM captioning model  
- Integrating VQA (BLIP) and TTS functionality  
- Building the web application interface  

### Next steps:
- Performance evaluation  
- Usability testing with visually impaired users  

---

## 🧠 Architecture Diagram
📌 *To be added:* Diagram illustrating the integration of CNN-LSTM, VQA, and TTS modules.

---

## 📊 Datasets

- **MS COCO**: Primary dataset for training and evaluating the image captioning model.
- **Flickr30k**: Used for additional testing and validation.

---

## 💻 Technologies Used

| Category    | Tools/Libraries                                |
|-------------|------------------------------------------------|
| **Backend** | Python, PyTorch, Flask, Hugging Face Transformers |
| **Frontend**| HTML5, CSS, JavaScript *(React/Vue.js planned)* |
| **TTS**     | gTTS, pyttsx3                                   |
| **Datasets**| MS COCO, Flickr30k                              |
| **Evaluation**| BLEU, CIDEr, ROUGE                          |

---

## 🤝 Contributing
This project is in early development. Contributions are welcome once the initial implementation is complete.

📬 **Contact the repository owner** if you're interested in collaborating.

---

## 📄 License
*To be determined*

---

## 📬 Contact
For inquiries, reach out via [GitHub Issues](../../issues) or email: **your-email@example.com**

---

> 🔧 *Note: This project is a work in progress. The README will be updated as development continues, including setup instructions, model training steps, and architectural diagrams.*
