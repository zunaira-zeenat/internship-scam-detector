# 🔍 Internship Scam Detector

A beginner-friendly Machine Learning project that analyzes internship and job descriptions and predicts whether an offer is **Likely Legitimate** or a **Potential Scam**.

The project uses **Natural Language Processing (NLP)** to convert text into numerical features and **Logistic Regression** to classify the internship description.

## 🎯 Project Objective

The goal of this project is to help students identify potentially suspicious internship offers by analyzing common patterns such as:

* Registration or processing fees
* Requests for money
* Unrealistic earning promises
* Requests for sensitive information
* Suspicious job/internship claims

> ⚠️ **Disclaimer:** This project is an educational/demo project. The current dataset is small and the model should not be used as a reliable real-world scam detection system.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorization
* Logistic Regression
* Gradio
* Google Colab

## 🔄 How It Works

The project follows these main steps:

1. Create and inspect the dataset
2. Clean the internship descriptions
3. Convert text into numerical features using **TF-IDF**
4. Split the data into training and testing sets
5. Train a **Logistic Regression** classification model
6. Evaluate the model
7. Enter a new internship description
8. Predict whether it is likely legitimate or potentially a scam
9. Display the estimated scam risk
10. Provide a simple explanation of the prediction

## 📊 Classification

The model uses two labels:

| Label | Meaning           |
| ----- | ----------------- |
| `0`   | Likely Legitimate |
| `1`   | Potential Scam    |

## 💻 Example

### Input

```text
Congratulations! You have been selected for an internship.
Pay a registration fee of Rs. 10,000 to secure your position immediately.
```

### Output

```text
Result: Potential Scam
Scam Risk: High
```

The application also provides an explanation reminding users to be careful before sharing money or personal information.

## 🌐 Gradio Interface

The project includes a simple **Gradio web interface** where users can:

* Paste an internship/job description
* Click **Analyze Internship**
* View the prediction
* View scam risk
* Read an explanation
* ![Internship Scam Detector](Screenshot 2026-09-15 012415 .png)

## 📁 Project Structure

```text
internship-scam-detector/
│
├── Internship_Scam_Detector.ipynb
└── README.md
```

## 📚 What I Learned

Through this project, I practiced:

* Text preprocessing
* NLP fundamentals
* TF-IDF
* Classification
* Logistic Regression
* Train/test splitting
* Model evaluation
* Prediction probabilities
* Building a simple ML interface with Gradio

## 🚀 Future Improvements

The project can be improved by:

* Expanding the dataset with many more real and verified examples
* Improving the quality and balance of the dataset
* Using a larger real-world dataset
* Testing additional classification algorithms
* Improving the explanation system
* Adding more detailed scam indicators
* Deploying the application online

## 👩‍💻 Author

**Zunaira Zeenat**

BS Information Technology Student

This project was created as part of my Machine Learning learning journey.
