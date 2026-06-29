# 🩺 Fine-Tuning GPT-2 for Disease Symptom Generation

A Natural Language Processing (NLP) project that fine-tunes **GPT-2** on the **Diseases & Symptoms** dataset to generate disease symptoms from disease names.

---

## 📌 Project Overview

This project demonstrates how to fine-tune a pre-trained GPT-2 language model using the Hugging Face Transformers library.

The model learns the relationship between disease names and their associated symptoms, enabling it to generate symptom descriptions for a given disease.

---

## 🚀 Features

* Load a medical dataset from Hugging Face Datasets
* Fine-tune GPT-2 using PyTorch
* Create a custom PyTorch Dataset
* Train and validate the model
* Generate symptoms for unseen disease names
* Save the trained model and tokenizer

---

## 📊 Dataset

Dataset:

**QuyenAnhDE/Diseases_Symptoms**

Each sample contains:

* Disease Name
* Symptoms

Example:

| Disease   | Symptoms                                      |
| --------- | --------------------------------------------- |
| Diabetes  | Increased thirst, fatigue, frequent urination |
| Influenza | Fever, cough, headache                        |

---

## 🧠 Model

**Pre-trained Model:** GPT-2

**Frameworks:**

* PyTorch
* Hugging Face Transformers

---

## ⚙️ Training Pipeline

1. Load the dataset.
2. Tokenize the text using the GPT-2 tokenizer.
3. Create a custom PyTorch dataset.
4. Split the data into training and validation sets.
5. Fine-tune the GPT-2 model.
6. Evaluate the validation loss.
7. Generate symptoms for sample disease names.
8. Save the trained model and tokenizer.

---

## 📦 Installation

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open the notebook and execute all cells.

The notebook will:

* Download the dataset.
* Load the GPT-2 model.
* Fine-tune the model.
* Display training and validation loss.
* Generate symptoms for a sample disease.
* Save the trained model.

---

## 💡 Example Generation

**Input**

```text
Kidney Failure |
```

**Generated Output**

```text
Kidney Failure | fatigue, swelling, decreased urine output, nausea ...
```

---

## 📈 Training

**Optimizer:** AdamW

**Loss Function:** Cross-Entropy Loss (provided by GPT-2)

**Framework:** PyTorch

---

## 💾 Saved Model

After training, the model and tokenizer are saved in the **SmallMedLM/** directory.

---

## 🛠 Technologies Used

* Python
* PyTorch
* Hugging Face Transformers
* Hugging Face Datasets
* Pandas
* tqdm

---

## 🚀 Future Improvements

* Train on larger medical datasets.
* Fine-tune larger language models (GPT-2 Medium, GPT-Neo).
* Apply LoRA or PEFT fine-tuning.
* Evaluate using Perplexity.
* Deploy with Gradio or Streamlit.
* Build a medical chatbot.

---

## 👨‍💻 Author

**Omar Emad**

Deep Learning & NLP Enthusiast

---

## 📄 License

This project is intended for educational and research purposes.
