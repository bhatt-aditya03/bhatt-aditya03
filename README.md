# Aditya Bhatt

**B.Tech CSE (Data Science) · Pranveer Singh Institute of Technology, Kanpur · Expected June 2027**

3rd year CS student interested in ML, iOS development, and building things end-to-end. I learn by shipping — most of these projects started as "let me see if I can actually build this" and grew from there.

---

## Projects

### [ProteinLens](https://github.com/bhatt-aditya03/ProteinLens) · *CoreML · iOS*

On-device food classification iOS app — point your camera at food, get nutrition estimates instantly with no internet required.

- Fine-tuned MobileNetV2 on a 20-class India-optimised Food-101 subset — **86% validation accuracy**
- Converted to CoreML (`.mlpackage`, ~5.9 MB) via TensorFlow → SavedModel → coremltools
- Live camera inference using AVFoundation + Vision + CoreML — < 50ms on Neural Engine
- Serving size slider (50g–500g), daily scan history, tap-to-freeze frame
- Stack: Swift · CoreML · Vision · AVFoundation · TensorFlow · Python · coremltools

---

### [FitMacroAI](https://github.com/bhatt-aditya03/FitMacroAI) · [Backend](https://github.com/bhatt-aditya03/FitMacroAI-Backend) · *iOS · FastAPI · Deployed*

iOS macro tracking app where you describe food in plain language and get back calorie and macro data.

- Type *"rajma chawal 1 katori"* → **420 cal, 19g protein, 60g carbs, 14g fat**
- LLaMA 3.3 70B (Groq) handles the food parsing; FastAPI backend deployed on Railway
- SwiftUI frontend with onboarding flow, daily auto-reset, and UserDefaults persistence
- Stack: SwiftUI · FastAPI · Python · Groq SDK · Railway

---

### [DocuMind](https://github.com/bhatt-aditya03/DocuMind) · *RAG · Python · Deployed*

Document Q&A tool built on a RAG pipeline — upload a PDF, ask questions, get answers with page-level citations.

- HuggingFace embeddings (`all-MiniLM-L6-v2`) → ChromaDB → LLaMA3-70b (Groq)
- Confidence indicator, auto-summary on upload, strict document-only prompting to avoid hallucination
- Live at **[docu-mind03.streamlit.app](https://docu-mind03.streamlit.app)**
- Stack: Streamlit · FastAPI · LangChain · ChromaDB · HuggingFace · Groq

---

### [Credit Risk Analyzer](https://github.com/bhatt-aditya03/credit-risk-analyzer) · *ML · Python*

Credit scoring model trained on 307,511 real loan applications.

- Baseline Logistic Regression AUC **0.6063** → XGBoost AUC **0.6805** (+12.3% lift)
- Feature engineering across 300k+ records from raw financial data
- Score output: 300–900 (FICO-style)
- Stack: Python · XGBoost · Scikit-learn · Pandas · NumPy

---

## Tech I've worked with

**ML / Data:** Python · TensorFlow · CoreML · coremltools · XGBoost · Scikit-learn · Pandas · NumPy  
**Backend:** FastAPI · REST APIs · Railway · LangChain  
**iOS:** Swift · SwiftUI · AVFoundation · Vision · CoreML · iOS 17+  
**AI / LLM:** Groq SDK · LLaMA 3.3 70B · Prompt Engineering · RAG  
**Vector DB / Embeddings:** ChromaDB · HuggingFace Sentence Transformers

---

## Connect

📧 [bhatt.aditya1105@gmail.com](mailto:bhatt.aditya1105@gmail.com)  
💼 [linkedin.com/in/bhatt-aditya03](https://linkedin.com/in/bhatt-aditya03)  
🐙 [github.com/bhatt-aditya03](https://github.com/bhatt-aditya03)
