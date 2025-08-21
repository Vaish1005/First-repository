#  Toxic Comment Classification using Deep Learning

This project implements a **toxic comment classifier** that can automatically detect harmful or offensive content in text using **deep learning models**.  
The model is based on **BERT**, a transformer-based language model fine-tuned for toxic comment classification.

---

##  Features
-  Detects toxic and harmful language in user comments.  
-  Real-time predictions through a simple web interface.  
-  Easy to run locally or in cloud environments.  
-  Built using PyTorch and Transformers.  

---

##  Model
We use a fine-tuned **BERT model** for multi-class toxic comment detection.  
The model can output categories such as:
- TOXIC  
- SEVERE_TOXIC  
- OBSCENE  
- THREAT  
- INSULT  
- IDENTITY_HATE  

---

##  Installation
Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/toxic-comment-detector.git
cd toxic-comment-detector
pip install -r requirements.txt

