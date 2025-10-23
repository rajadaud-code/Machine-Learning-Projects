# 📧 Spam vs Ham Mail Prediction using Machine Learning

## 🧠 Project Overview
This project predicts whether an email is **Spam (0)** or **Ham (1)** using a machine learning approach.  
The model is trained on the **Mail_Data dataset**, which contains two columns:
- **Category** → Spam or Ham  
- **Message** → Email text content  

The main goal is to classify messages accurately using a **Logistic Regression model**.

---

## 🧩 Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Platform:** Google Colab  

---

## ⚙️ Steps Involved
1. **Importing the Dependencies**  
2. **Data Collection and Preprocessing**  
3. **Label Encoding**  
   - Spam → 0  
   - Ham → 1  
4. **Splitting the Data** into Training and Testing sets  
5. **Feature Extraction** using text vectorization  
6. **Training the Model** using **Logistic Regression**  
7. **Evaluating the Trained Model**  
8. **Building a Predictive System** to test new emails  

---

## 📊 Model Performance
- **Accuracy on Training Data:** `0.9677`  
- **Accuracy on Testing Data:** `0.9668`  

The model shows strong performance in detecting spam emails while minimizing false positives.

---

## 🚀 How to Run
1. Open the `.ipynb` file in **Google Colab**.  
2. Upload the **mail_data.csv** dataset.  
3. Run all cells sequentially.  
4. Test the model by entering custom email messages to check predictions.

---

## 🧾 Dataset
- **File:** `mail_data.csv`  
- **Columns:**  
  - `Category` — Label (spam or ham)  
  - `Message` — Email text content  

---

## 👨‍💻 Author
Developed by **[Muhammad Daud Israr]** **AI ML Engineer** 
A beginner-friendly text classification project using **Logistic Regression** for spam detection.
