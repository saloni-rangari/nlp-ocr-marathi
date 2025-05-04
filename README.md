# Marathi Handwriting Text Recognition using Transformer-based OCR / Tesseract + NLP

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![Colab](https://img.shields.io/badge/Run%20in-Colab-orange?logo=googlecolab)](https://colab.research.google.com/drive/1YgqR6DplHggogXh2Wv46ocIJAHjUVnSG?usp=sharing)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)](#)

---

## 📌 Project Overview

This project implements handwritten text recognition using **OCR (Optical Character Recognition)** and **NLP (Natural Language Processing)** techniques, focusing on **Marathi** script. It allows users to upload handwritten Marathi text images, extract and clean the text, then perform NLP tasks like **tokenization**, **translation**, **NER**, **sentiment analysis**, and **summarization**.

> 📚 **Subject:** Natural Language Processing ( CTMTAIDS SII P3 )  
> 🏫 **Course:** M.Tech in Artificial Intelligence & Data Science (Specialization in Cybersecurity)  
> 🎓 **Institute:** National Forensic Sciences University (NFSU), Goa  
> 🔖 **Project:** TA2 – Mararthi Handwritten Text Recognition, Language Detection, Translation, and Summarization

---

## 🚀 Features

- 📸 **Upload or capture** handwritten text images in your mother tongue (Marathi)
- 🧼 **Image preprocessing** using OpenCV (grayscale, denoising, resizing)
- 🔍 **OCR extraction** using Transformer-based models or Tesseract with Marathi language support
- 🧹 **Text normalization** to clean OCR output (remove noise, fix encoding)
- 🧠 **NLP processing** including:
  - Tokenization
  - Named Entity Recognition (NER) for Marathi
  - Language detection and translation
  - Sentiment analysis (positive, negative, or neutral)
  - Summarization of extracted text
- 📊 **Output visualization** in console or tabular format for easy interpretation

---

## 🛠️ Tools & Technologies

- **Python 3.10+**
- **Jupyter/Google Colab**
- **Transformer + Tesseract OCR + Marathi Language Pack**
- **TrOCR** (Microsoft Transformer OCR)
- **TrOCR Marathi** (Fine-tuned for Marathi handwriting)
- **spaCy** (NLP toolkit)
- **MahaBERT & L3Cube-Marathi NLP models**
- **Helsinki-NLP OPUS-MT** (Translation models)
- **OpenCV** (Computer Vision)
- **PIL (Pillow)**
- **Indic NLP Library**
- **Deep Translator / Google Translate API**
- **LangDetect** (Language detection)
- **BERT-base-NER** (Named Entity Recognition)
- **mT5-multilingual-XLSum & Falconsai summarizers**
- **Matplotlib & Pandas**

---

## 📁 Repository Files

| File                                                        | Description                               |
|-------------------------------------------------------------|-------------------------------------------|
| [`NLP_TA2_Assignment.ipynb`](NLP_TA2_Assignment.ipynb)      | Full Colab notebook with implementation   |
| [`NLP_TA2_Assignment.py`](NLP_TA2_Assignment.py)            | Python script version of the notebook     |
| [`NLP_TA2_Code_Output.pdf`](NLP_TA2_Code_Output.pdf)        | Code with final output                    |
| [`NLP_TA2_Project_Report.pdf`](NLP_TA2_Project_Report.pdf)  | Project Report                            |
| [`marathi_text.png`](marathi_text.png)                      | Sample Marathi handwritten image          |

---

## ▶️ Run on Google Colab

Click the badge below to open the notebook in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YgqR6DplHggogXh2Wv46ocIJAHjUVnSG?usp=sharing)

---

## 📜 License

This project is licensed under the **GNU GPL v3**. See the [`LICENSE`](LICENSE) file for details.

---

## 🙌 Acknowledgements

- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) – Open-Source OCR Engine
- [TrOCR (Microsoft)](https://github.com/microsoft/unilm/tree/master/trocr) – Transformer-based OCR
- [TrOCR Marathi](https://github.com/MubashirTanwar/TrOCR) – Fine-tuned model for Marathi handwriting
- [spaCy](https://spacy.io) – Industrial-strength NLP library
- [L3Cube Marathi NLP](https://github.com/l3cube-pune/MarathiNLP) – Marathi NLP resources
- [Helsinki-NLP](https://huggingface.co/Helsinki-NLP) – OPUS-MT translation models
- [Indic NLP Library](https://github.com/anoopkunchukuttan/indic_nlp_library) – Indian language NLP tools
- [OpenCV](https://opencv.org) – Computer vision library
- [BERT-base-NER](https://huggingface.co/dslim/bert-base-NER) – NER model on Hugging Face
- [mT5-multilingual-XLSum](https://huggingface.co/Existance/mT5_multilingual_XLSum) – Multilingual summarizer
- [Falconsai summarizer](https://huggingface.co/Falconsai/text_summarization) – Text summarization model
- [MahaBERT](https://huggingface.co/abhi964/MahaPhrase_mahaBERTv2_Finetuning) – Marathi BERT model
- [LangDetect](https://pypi.org/project/langdetect/) – Language detection Python library
- [Deep Translator](https://pypi.org/project/deep-translator/) – Translation utility library
