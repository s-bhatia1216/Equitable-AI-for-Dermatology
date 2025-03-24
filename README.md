# Equitable AI for Dermatology
**A Break Through Tech x Algorithmic Justice League Challenge**

Building an ML model to classify skin conditions across diverse skin tones for the AJL Kaggle Challenge, aiming to advance equity by centering those historically excluded in AI.

## 👥 Team Members
- Sofia Nguyen 
- Pa Yeng Yang
- Sonal Bhatia
- Lisa Farley
- Jacky Chen
- Svetlana Voda
- Cindy Deng (BTT TA)


## 📌 Project Highlights
(insert text here)

### 📝 Project Overview
This Kaggle competition was created in collaboration with the Break Through Tech (BTT) AI Program and the Algorithmic Justice League (AJL) to explore the machine learning life cycle and build a model that challenges the biases and ethics of dermatology AI.  Both BTT AI and AJL's missions surround educating future engineers to build the most unbiased and ethical AI models as humanly possible. This competition sheds light on the fact that existing machine learning models for dermatology are biased against darker skin tones, and good AI engineers understand and combat these issues in their models. Therefore, we are tasked with designing a machine learning model that is more fair and is capable of classifying 21 skin conditions across diverse skin tones.

### 🔍 Objective
The objective of this challenge is to build an inclusive machine learning model that can accurately classify 21 different skin conditions from dermatology images across a range of skin tones. The goal is not only to achieve strong performance using metrics like the weighted F1 score, but also to address fairness and reduce bias—especially for communities that have been historically underrepresented in healthcare AI.

### 💡 Significance
AI is transforming healthcare, but many dermatology AI tools underperform for people with darker skin tones due to non-diverse training data, leading to misdiagnosis and worsening health disparities. This challenge from Break Through Tech and the Algorithmic Justice League gives us the opportunity to help address this issue by building a more inclusive machine learning model. Our work builds on research from Stanford and the MIT Media Lab to improve fairness and explainability in dermatology AI. More broadly, this project highlights how biased AI can reinforce discrimination across healthcare, economic opportunity, and criminal justice. By advocating for diverse training data and more transparent models, we hope to push for more ethical AI in medicine and beyond.

## Setup & Execution
(insert text here.)


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
![image](https://github.com/user-attachments/assets/3ae62dd1-7906-4dd3-a961-2ec3b6d5458d)

📷 **Example 2:** Fitzpatrick scale distribution  
*(Histogram showing that the dataset is right-skewed towards lighter skin pigmentation)*
![image](https://github.com/user-attachments/assets/94bd94a6-9941-40da-bd54-a2aa899fdf69)


📷 **Example 3:** Image sample grid across skin tones  
*(Grid visualization displaying the same condition (keloid) across different skin tones)*
![image](https://github.com/user-attachments/assets/3fa04e2b-ab50-417a-b0ab-6639727583fb)

These insights helped guide our data augmentation strategies and model architecture choices.

## 🧠 Model Development
(insert text here)



## 📊 Results & Key Findings
(insert text here)



## 🌍 Impact Narrative

AI is transforming healthcare, but many dermatology AI tools underperform for people with darker skin tones due to non-diverse training data, leading to misdiagnosis and worsening health disparities. This challenge from Break Through Tech and the Algorithmic Justice League gave us the opportunity to help address this issue by building a more inclusive machine learning model.

Our work builds on research from Stanford and the MIT Media Lab to improve fairness and explainability in dermatology AI. More broadly, this project highlights how biased AI can reinforce discrimination across healthcare, economic opportunity, and criminal justice. By advocating for diverse training data and more transparent models, we hope to push for more **ethical AI** in medicine and beyond.

## 🔮 Next Steps & Future Improvements
(insert text here)

