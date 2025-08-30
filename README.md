# 📧 Spam Detection using TF-IDF & Logistic Regression  

This repository contains a **Spam Detection System** built with **TF-IDF Vectorizer** and **Logistic Regression**. The project demonstrates how traditional machine learning techniques can classify text messages as either spam or not spam.  

The workflow includes preprocessing, feature extraction with **TF-IDF**, training a **Logistic Regression model**, and testing on sample inputs.  

---

## 🚀 Features  
- Preprocesses and vectorizes text using **TF-IDF**  
- Classifies messages into:  
  - `0` → Spam  
  - `1` → Not Spam  
- Tested on real-world sample inputs  
- Jupyter Notebook included for step-by-step code execution  

---

## 🛠️ Tech Stack  
- Python 3.x  
- scikit-learn  
- pandas / numpy  
- Jupyter Notebook  

---

## 📂 Repository Structure  

📦 Spam-Detection
┣ 📜 Spam&NotSpam.ipynb   # Main notebook with code
┣ 📜 README.md            # Project documentation
┣ 📜 requirements.txt     # Dependencies
┗ 📜 .gitignore           # Ignore unnecessary files

---

## 🧪 Example Usage  

```python
msg = ["Congratulations! You've won a free lottery ticket."]

# Model output
Prediction: 0  # Spam

msg = ["Hey, are we meeting tomorrow?"]

# Model output
Prediction: 1  # Not Spam


⸻

⚡ How to Run
	1.	Clone the repository:

git clone https://github.com/your-username/spam-detection.git
cd spam-detection


	2.	Install dependencies:

pip install -r requirements.txt


	3.	Open the notebook:

jupyter notebook Spam&NotSpam.ipynb


	4.	Run all cells to train and test the model.

⸻

🎯 Applications
	•	SMS spam filtering
	•	Email classification
	•	Chat moderation systems

⸻

🤝 Contributing

Feel free to fork this repo, raise issues, or submit pull requests to improve the project.

⸻

📜 License

This project is open-source and available under the MIT License.

---
