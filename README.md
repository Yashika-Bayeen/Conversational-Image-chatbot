# Conversational Image Recognition Chatbot (SIH 1604)

An AI-powered **Conversational Image Recognition Chatbot** that enables users to **upload an image and ask natural language questions** about it. The system combines **Computer Vision and Natural Language Processing (NLP)** to generate context-aware, human-like answers using **Vision–Language models**.

---

## Project Overview
This project focuses on **Visual Question Answering (VQA)**, where the system understands both **visual content** and **textual questions** to produce meaningful responses. Unlike traditional image classifiers, this chatbot allows **interactive conversations with images**.

The system leverages **BLIP (Bootstrapped Language-Image Pretraining)** for vision–language understanding and **T5 (Text-to-Text Transfer Transformer)** for fluent answer generation. A **Gradio-based interface** enables real-time user interaction.

---

## Objectives
- Enable conversational interaction with images  
- Answer questions based on image context and semantics  
- Demonstrate multimodal AI (Vision + Language fusion)  
- Build an intuitive and accessible AI chatbot  

---

## ✨ Key Features
- Image upload and visual understanding  
- Natural language question answering  
- Vision–Language fusion using BLIP  
- Fluent answer generation using T5  
- Interactive chatbot UI using Gradio  
- Fuzzy matching for response refinement  
- Model evaluation using BLEU score  

---

## 📂 Dataset Used
The model is trained and evaluated using **publicly available Kaggle VQA datasets**:

### 🔹 visual-question-answering-computer-vision-nlp
- Contains image–question–answer triplets  
- Designed for computer vision and NLP fusion tasks  
- Helps the model learn visual grounding and question understanding  

### 🔹 vqa-fullanswer
- Provides **full-sentence answers** instead of short labels  
- Improves conversational quality and natural language generation  
- Suitable for chatbot-style visual question answering  

These datasets enable the system to generate **complete, human-like answers** rather than single-word predictions.

---

## Methodology
1. User uploads an image  
2. User asks a question about the image  
3. Image and question are processed jointly using **BLIP**  
4. Visual and textual features are fused  
5. **T5** generates a natural language response  
6. The answer is displayed via the conversational interface  

---

## 🛠️ Technologies Used

### Programming & Frameworks
- Python  
- PyTorch  
- Gradio  

### AI & NLP Models
- **BLIP (Bootstrapped Language-Image Pretraining)**  
- **T5 (Text-to-Text Transfer Transformer)**  

### Libraries & Tools
- Hugging Face Transformers  
- Kaggle Datasets  
- RapidFuzz (Fuzzy Matching)  
- PIL (Image Processing)  
- Matplotlib  
- SacreBLEU (Evaluation Metric)  

---

## How to Run the Project
```bash
# Clone the repository
git clone https://github.com/your-username/conversational-image-chatbot.git

# Navigate to the project directory
cd conversational-image-chatbot

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
