# **Physician Notetaker: Medical NLP Pipeline**

An AI-powered system for **medical transcription, summarization, sentiment analysis, and SOAP note generation**. It processes physician-patient conversations to extract key details, analyze sentiment, and generate structured reports.

---

## **Features**
1. **Medical NLP Summarization:**
   - Extracts **Symptoms, Diagnosis, Treatment, Prognosis**.
   - Generates structured medical reports in JSON.

2. **Sentiment & Intent Analysis:**
   - Classifies sentiment (`Anxious`, `Neutral`, `Reassured`).
   - Detects intent (e.g., "Seeking reassurance").

3. **SOAP Note Generation (Bonus):**
   - Converts transcripts into structured **SOAP notes**.

---

## **Setup Instructions**

### **Prerequisites**
-  **Google Colab**.
- No local installation required.





## **Methodologies Used**

### **1. Medical NLP Summarization**
- **Algorithm:** Rule-based matching using **spaCy's PhraseMatcher**.
- **Reasoning:** Simple and effective for extracting predefined medical terms (e.g., symptoms, treatments).
- **Pre-trained Models:** `en_core_web_sm` (spaCy's small English model).

### **2. Sentiment & Intent Analysis**
- **Algorithm:** Transformer-based sentiment analysis using **DistilBERT**.
- **Reasoning:** DistilBERT is lightweight and efficient for sentiment classification.
- **Intent Detection:** Rule-based keyword matching for simplicity and interpretability.

### **3. SOAP Note Generation**
- **Algorithm:** Rule-based mapping of transcript data to SOAP sections.
- **Reasoning:** Provides a structured and clinically meaningful output without requiring complex training.

### **Pre-trained Models**
- **NER and Summarization:** `en_core_web_sm`, `BioBERT`, `ClinicalBERT`.
- **Sentiment Analysis:** `distilbert-base-uncased-finetuned-sst-2-english`.


--- 

Thank you for using **Physician Notetaker**! 🚀
