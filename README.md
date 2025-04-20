# Multilingual Scene Text Recognition and Translation

## Using Hybrid OCR and Machine Translation Approach

## 📌 Project Overview

This Project-Based Learning (PBL) initiative focuses on developing a **Multilingual Scene Text Recognition and Translation System** that uses a hybrid approach combining **Optical Character Recognition (OCR)** and **Machine Translation (MT)** techniques. The goal is to extract text from natural scene images across different languages and translate it into a user-defined target language using AI models.

The project addresses real-world challenges in **cross-language communication, accessibility**, and **global usability of visual content**.

## 🎯 Objectives

- Detect and extract text from natural scene images using OCR.
- Identify the language of the recognized text.
- Translate extracted multilingual text to a user-defined target language.
- Evaluate system accuracy using standard metrics (BLEU, WER, etc.).
- Visualize and analyze OCR performance across languages and image types.

## 🧠 Technologies Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Core Libraries:**
  - `cv2` (OpenCV) – Image processing
  - `pytesseract`, `easyocr` – OCR engines
  - `langdetect`, `googletrans`, `nltk` – Language detection and translation
  - `jiwer` – WER calculation
  - `matplotlib`, `seaborn`, `wordcloud` – Visualization
  - `scikit-learn` – Evaluation and metrics

## 🗂️ Project Structure

```bash
PBL_Project.ipynb         # Main notebook with code and outputs
README.md                 # Project documentation
requirements.txt          # Python dependencies
```

## 🧩 Key Features

- 🌐 **Multilingual OCR Support**: Scene text recognition in diverse scripts using both Tesseract and EasyOCR.
- 🈳 **Language Detection**: Automatic language identification of detected text.
- 🔁 **Machine Translation**: Real-time translation using Google Translate API.
- 📊 **Evaluation Metrics**:
  - BLEU Score for translation accuracy
  - WER (Word Error Rate) for OCR reliability
- 📈 **Visual Feedback**: Heatmaps, word clouds, and confidence scores for model interpretability.

## 🧪 Model Evaluation

The notebook includes training and evaluation of multiple models with performance metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Cross-Validation Results

Model outputs are visualized using confusion matrices, ROC curves, and performance graphs.

## 🔬 Experimental Workflow

- **Image Input**: Natural scene image with text (any language).
- **Preprocessing**: Image enhancement using OpenCV techniques.
- **OCR Engine**: Text extraction using pytesseract and EasyOCR.
- **Language Detection**: Detected using langdetect or custom NLP logic.
- **Translation**: Translated via Google Translate (API/client).
- **Evaluation**: Compared against ground truth using BLEU and WER.

## 🔧 How to Run the Project

1. Clone the repository or download the `.ipynb` file.
2. Ensure you have Python 3.x and Jupyter installed.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch the notebook:

```bash
jupyter notebook PBL_Project.ipynb
```

5. Run all cells sequentially to explore data and model results.

> ⚠️ **Note**: Tesseract OCR must be installed separately on your system:

```bash
sudo apt install tesseract-ocr
```

## ✅ Results Summary

- Successfully extracted and translated text from multilingual scene images.
- EasyOCR improved performance in low-light and non-Latin script scenarios.
- Google Translate provided accurate sentence-level translations.
- Evaluation metrics confirmed robustness of hybrid OCR + MT approach.

## 📊 Sample Outputs

- Detected text overlays on scene images.
- Word clouds of frequently detected terms.
- BLEU score comparisons between models.
- WER values for multiple languages.

## 👨‍💻 Authors & Contributors

- **Authors** – Devanshu Sawarkar([GithubID](https://github.com/DevanshuSawarkar)), Pratham Agrawal([GithubID](https://github.com/PrathamAgrawal51)), Devansh Motghare([GithubID](https://github.com/devansh7444))
- **Institution**: Symbiosis Institute of Technology, Nagpur
- **Course**: B.Tech Computer Science

## 🎓 Mentors
- Dr. Latika Pinjarkar ([GithubID](https://github.com/latika2019))

## 📚 Acknowledgments

- OpenCV and Tesseract teams for robust OCR tools.
- Google Translate API and EasyOCR for multilingual support.
- Faculty mentors for guidance and evaluation.

## 📌 Future Work

- Integration with mobile/web camera feeds.
- Offline translation using transformer-based models (e.g., MarianMT, M2M100).
- End-to-end multilingual scene understanding with vision-language transformers.

## ⚖️ License

This project is for educational and academic purposes only.
