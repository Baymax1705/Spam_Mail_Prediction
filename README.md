# 📧 Spam Mail Prediction

This project is a Machine Learning-based solution for predicting whether an email is **spam** or **not spam**. It utilizes Natural Language Processing (NLP) techniques to clean and vectorize email text, and then applies a classification model to make predictions.

---

## Features

- Text preprocessing and cleaning  
- Feature extraction using TF-IDF  
- Model training using Multinomial Naive Bayes  
- Accuracy evaluation and confusion matrix  
- Predict function for custom inputs  

---

## How to Use
1. Clone this repository:
   ```sh
   git clone https://github.com/Baymax1705/Spam_Mail_Prediction.git
   cd Spam_Mail_Prediction
2. Install dependencies (recommended: use a virtual environment):
   ```sh
   pip install -r requirements.txt
3. Run the notebook:
   ```sh
   jupyter notebook Spam_Mail_Prediction.ipynb

## Dataset

The dataset used in this project is the **SMS Spam Collection Dataset** from UCI Machine Learning Repository:

🔗 [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)


## Results

- Achieved accuracy of over 97% using Multinomial Naive Bayes
- High precision and recall for both spam and ham classes

## Future Improvements

- Deploy the model using Flask or Streamlit for a web-based spam checker
- Explore deep learning models like LSTM for sequence-based text classification
- Add real-time email input integration

