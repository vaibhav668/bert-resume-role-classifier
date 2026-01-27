# BERT Resume Role Classifier

A deep learning–based NLP project that classifies resumes into predefined job roles using **BERT transformers** and **PyTorch**.  
The system processes resume PDFs, extracts text, and predicts the most suitable job role with detailed evaluation metrics.

---

## 🚀 Project Overview

Resume screening is a critical but time-consuming task in recruitment.  
This project automates resume role classification using a **fine-tuned BERT model**, enabling accurate and scalable resume analysis.

---

## 🧠 Key Features

- 📄 Resume **PDF text extraction**
- 🔤 Context-aware text representation using **BERT**
- 🏷️ Multi-class job role classification
- 📊 Model evaluation using:
  - Confusion Matrix
  - Precision, Recall, and F1-score
- ⚙️ Implemented using **PyTorch & HuggingFace Transformers**

---

## 📂 Dataset Details

- **Total resumes:** ~962  
- **Number of job roles:** ~25  
- **Format:** CSV (Resume text + Role label)  
- **Missing values:** None  
- **Max token length:** ~14,800 (handled via truncation)

---

## 🏗️ Tech Stack

- Python
- PyTorch
- HuggingFace Transformers
- BERT (Pretrained)
- Scikit-learn
- Pandas, NumPy
- Matplotlib / Seaborn

---

## 🔄 Workflow Pipeline

1. Extract text from resume PDFs  
2. Text preprocessing & tokenization  
3. Fine-tune BERT for multi-class classification  
4. Generate predictions on test data  
5. Evaluate performance using confusion matrix & classification report  

---

## 📈 Model Evaluation

- **Metric used:** Weighted F1-score  
- Detailed classification report for each job role  
- Confusion matrix to analyze class-wise misclassifications  

These metrics help understand **model strengths, weaknesses, and role overlap**.

---

## 🧪 Results & Observations

- BERT effectively captures semantic meaning in resumes
- Some role overlap exists (e.g., similar tech roles), visible in the confusion matrix
- Model performs significantly better than traditional ML approaches

---

## 🔮 Future Improvements

- Deploy using **Streamlit / FastAPI**
- Add **confidence scores** for predictions
- Perform detailed **error analysis on misclassified resumes**
- Support **multi-label classification**
- Integrate skill extraction and recommendation

---

## 👤 Author

**Vaibhav Pokhriyal**  
B.Tech 
CSE (AI & ML)  

---

⭐ If you found this project useful, consider giving it a star!
