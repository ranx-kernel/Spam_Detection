# 📩 Spam Message Detection

A Natural Language Processing and Machine Learning mini-project that automatically classifies text messages as **Spam** or **Ham (legitimate)**.

## 🎯 Objective

To develop a machine-learning-based system that identifies unwanted or fraudulent messages using Natural Language Processing techniques.

## 🧠 Algorithms

### TF-IDF

TF-IDF (Term Frequency–Inverse Document Frequency) converts text into numerical features that can be processed by a machine-learning model.

### Multinomial Naive Bayes

Multinomial Naive Bayes is used to classify messages into Spam and Ham categories.

## 📊 Dataset

The project uses the **SMS Spam Collection** dataset.

The dataset contains SMS messages labeled as:

- `ham` — legitimate message
- `spam` — unwanted/spam message

## 🛠️ Technologies

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Multinomial Naive Bayes
- Matplotlib
- Seaborn
- Gradio
- Google Colab

## ⚙️ System Architecture

```text
              SMS / Text
                  │
                  ▼
          Text Preprocessing
                  │
                  ▼
               TF-IDF
                  │
                  ▼
        Multinomial Naive Bayes
                  │
           ┌──────┴──────┐
           ▼             ▼
        HAM ✅        SPAM 🚨
           │             │
           └──────┬──────┘
                  ▼
          Prediction Result
```

## 🚀 Features

- SMS spam detection
- Ham message detection
- TF-IDF feature extraction
- Machine-learning classification
- Accuracy evaluation
- Classification report
- Confusion matrix
- Prediction probability
- Interactive Gradio interface

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The actual accuracy is generated during notebook execution and may vary depending on the train-test split.

## ▶️ How to Run

1. Open `Spam_Detection.ipynb` in Google Colab.
2. Install the required libraries.
3. Download/load the SMS Spam Collection dataset.
4. Split the data into training and testing sets.
5. Apply TF-IDF vectorization.
6. Train the Multinomial Naive Bayes model.
7. Evaluate the model.
8. Enter a custom message to test the classifier.
9. Launch the Gradio interface.

## 🔮 Future Enhancements

- Deep-learning-based spam detection
- Multilingual spam detection
- Email spam detection
- URL and phishing detection
- Real-time SMS filtering
- Transformer-based classification

## 👩‍💻 Author

**Rania**

Text and Speech Analysis – Mini Project 2
