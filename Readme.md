# 🧠 Depression Detection via Audio-Video Fusion (Gradio GUI | Colab Ready)

[[Hugging Face Spaces](Live Demo)](https://huggingface.co/spaces/nouman54/Depression)

This project detects signs of depression using combined **audio** and **visual** features extracted from video files. It leverages a pre-trained **DenseNet201** deep learning model, audio feature extraction via **Librosa**, frame processing with **OpenCV**, and an interactive **Gradio** interface.

---

## 🚀 Features

- 🎥 Accepts video files with both audio and visual data  
- 🔉 Extracts MFCCs and spectral features using `librosa`  
- 🎞️ Processes video frames using `OpenCV`  
- ⚙️ Uses `scaler.pkl` for feature normalization  
- 🧠 Predicts depression levels using a **DenseNet201** model  
- 🌐 Offers an interactive **Gradio web interface**  
- ☁️ Compatible with **local and Colab environments**  
- 🔗 **Deployed on Hugging Face**: [Live Demo](https://huggingface.co/spaces/nouman54/Depression)

---

## 🧠 Model Info

- **Architecture**: DenseNet201 (via Keras)  
- **Dataset**: Fine-tuned on **DAIC-WOZ**  
- **Optional Pretraining**: Compatible with **CREMA-D**  
- **Input Shape**: `(None, 216, 78)`  
- **Fusion**: Early fusion of audio and visual features  

---

## 📁 Files

- `densenet201_depression_model.keras` – Trained model  
- `depression_model_finetuned.h5` – Alternative trained model  
- `scaler.pkl` – Preprocessing scaler (required)  
- `samplevideo.flv` – Sample video for testing  
- `requirements.txt` – Project dependencies  
- `app.py` or `notebook.ipynb` – Main interface/script  
- `README.md` – Project overview and usage  

---

## 🔧 Setup

Install dependencies:

pip install -r requirements.txt


---

## ⚙️ Usage

1. Run the Gradio app locally or in Colab.  
2. Upload a video file containing both **audio and visual** input.  
3. The system will extract features and return a **depression prediction**.  

---

## ⚠️ Disclaimer

This tool is for **research and educational purposes only**.  
**It is not intended for medical diagnosis or treatment.**

---

## 👨‍💻 Author

**Nouman Afzal**  
📂 GitHub: [NoumanAfzal54](https://github.com/NoumanAfzal54)  
🚀 Hugging Face: [DepressionDetection App](https://huggingface.co/spaces/nouman54/Depression)

---
