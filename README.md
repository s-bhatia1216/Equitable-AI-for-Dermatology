# Equitable-AI-for-Dermatology
**A Break Through Tech x Algorithmic Justice League Challenge**
Building an ML model to classify skin conditions across diverse skin tones for the AJL Kaggle Challenge, aiming to advance equity by centering those historically excluded in AI.

## 📌 Project Overview
This project was completed as part of the Break Through Tech AI Program, in collaboration with Kaggle and the Algorithmic Justice League. The challenge asked us to design a machine learning model capable of classifying 21 skin conditions across diverse skin tones, addressing the real-world implications of fairness and bias in healthcare AI.

## 🔍 Objective
The objective of this challenge is to build an inclusive machine learning model that can accurately classify 21 different skin conditions from dermatology images across a range of skin tones. The goal is not only to achieve strong performance using metrics like the weighted F1 score, but also to address fairness and reduce bias—especially for communities that have been historically underrepresented in healthcare AI.

## 💡 Significance
AI is transforming healthcare, but many dermatology AI tools underperform for people with darker skin tones due to non-diverse training data, leading to misdiagnosis and worsening health disparities. This challenge from Break Through Tech and the Algorithmic Justice League gives us the opportunity to help address this issue by building a more inclusive machine learning model. Our work builds on research from Stanford and the MIT Media Lab to improve fairness and explainability in dermatology AI. More broadly, this project highlights how biased AI can reinforce discrimination across healthcare, economic opportunity, and criminal justice. By advocating for diverse training data and more transparent models, we hope to push for more ethical AI in medicine and beyond.

## 📁 Dataset & Data Exploration

### 🗂️ Data Sources

We worked with the dataset provided in the [Kaggle competition](https://www.kaggle.com/competitions/bttai-ajl-2025) which included:
- A **training folder** of labeled dermatology images
- A **test folder** of unlabeled images organized by condition

Each image was labeled with one of 21 skin condition categories. The dataset included patients across a wide spectrum of skin tones to ensure diversity and representation.

### 🛠️ Preprocessing & Cleaning

🧼 Key preprocessing steps included:
- Validating that **every image had a proper path**
- Deleting **2531 corrupted or unreadable JPEGs**
- Verifying that each **class folder in test data** contained an appropriate number of images
- Confirming that the train and test folders were formatted consistently

### 📊 Exploratory Data Analysis (EDA)

We explored the data distribution and characteristics to better understand class imbalances and variations across conditions and skin tones.

📷 **Example 1:** Class distribution of skin conditions  
*(Bar chart showing imbalance across 21 classes)*

📷 **Example 2:** Image sample grid across skin tones  
*(Grid visualization displaying the same condition across different skin tones)*

📷 **Example 3:** Image resolution & aspect ratio distribution  
*(Histogram showing spread of image sizes)*

These insights helped guide our data augmentation strategies and model architecture choices.


