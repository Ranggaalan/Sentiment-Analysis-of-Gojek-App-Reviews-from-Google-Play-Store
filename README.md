# **Sentiment Analysis of Gojek App Reviews from Google Play Store**  

## **Project Description**  
This project analyzes **user reviews of the Gojek application** from the **Google Play Store** to determine sentiment polarity: **Positive, Neutral, or Negative**. The goal is to understand **user satisfaction, pain points, and trends in customer feedback** through **text mining and sentiment classification**.  
![Image](https://github.com/user-attachments/assets/c001fe28-0934-4319-aa61-a7cee5eecd19)

## **Dataset**  
The dataset consists of user reviews collected from **Google Play Store**, including:  (Link:https://play.google.com/store/search?q=gojek&c=apps)
- **Review Text**: User feedback about the app  
- **Rating (1-5 Stars)**  
- **Date of Review**  
- **Helpful Votes**  

## **Methodology**  
### **1. Data Preprocessing**  
- Removing stopwords, special characters, and emojis  
- Tokenization and stemming  
- Sentiment labeling based on review ratings  

### **2. Sentiment Classification**  
Three sentiment categories are used:  
1. **Positive** – Satisfied users (ratings 4-5)  
2. **Neutral** – Mixed or moderate feedback (rating 3)  
3. **Negative** – Dissatisfied users (ratings 1-2)  

### **3. Machine Learning Models**  
Several models were applied to classify sentiment, including:  
- **Naïve Bayes**  
- **Logistic Regression**  
- **Random Forest**  
- **Support Vector Machine (SVM)**  
- **Decision Tree**  
- **K-Nearest Neighbors (KNN)**  
- **Gradient Boosting**  

The best-performing models were **Decision Tree and SVM**, achieving the **highest accuracy**.  

## **Results & Insights**  
### **Sentiment Distribution**  
- **Negative Sentiment:** **51 reviews** (most common)  
- **Neutral Sentiment:** **8 reviews**  
- **Positive Sentiment:** **32 reviews**  

Most user feedback is **negative**, indicating areas for improvement in the app.  

### **Model Performance**  
![image](https://github.com/user-attachments/assets/c22f2e07-c6d3-4e3e-a9ab-29f1ea19cb26)

- **Decision Tree and SVM achieved the highest accuracy.**  
- Other models like **Logistic Regression, Naïve Bayes, and Random Forest** also performed well, but with slightly lower accuracy.  

### **Key Insights**  
- **Frequent Positive Words**: "Layanan", "Baik", "Jalan"  
- **Frequent Negative Words**: "Lama", "Bayar", "Driver", "Kecewa"  
- **Common complaints** include **app crashes, slow response, and pricing issues**.  
- **Neutral reviews** often discuss **mixed experiences with customer service**.  

### Sentimen Positif
![Image](https://github.com/user-attachments/assets/7814637d-b694-4556-bf48-d975eaf81361)

### Sentimen Negatif
![Image](https://github.com/user-attachments/assets/607a57db-c1dd-44a8-9192-3a614418baa9)

### Sentimen Netral
![Image](https://github.com/user-attachments/assets/6a190ee1-fd18-41d6-8f17-63a2408127e4)

### Hasil Sentimen
![image](https://github.com/user-attachments/assets/e9dc6df7-4b3f-4e0a-8af6-eef71558b84a)

### Confusion Matrix
![image](https://github.com/user-attachments/assets/4bb31f40-5a11-4800-b6b0-a60c17ffb76d)


## **Technologies Used**  
- **Python**: Pandas, Numpy, Scikit-learn, NLTK  
- **Machine Learning**: Naïve Bayes, Logistic Regression, SVM, Decision Tree  
- **Text Processing**: Natural Language Toolkit (NLTK)  
- **Visualization**: Matplotlib, Seaborn, WordCloud  

## **How to Use**  
1. Clone this repository.  
2. Install dependencies using `pip install -r requirements.txt`.  
3. Run `sentiment_analysis.py` to classify user reviews.  
4. Explore results and insights in `gojek_reviews_analysis.ipynb`.  

## **Conclusion**  
This sentiment analysis of **Gojek app reviews** provides valuable insights into **user satisfaction and common issues**. The **Decision Tree and SVM models** were the most effective in classifying sentiments. These findings can help improve **app development and customer experience**.  
