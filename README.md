# Sentiment-Analysis-on-Amazon-Product-Reviews

## Introduction
In the expanding realm of e-commerce, platforms like Amazon have transformed the consumer experience, providing unparalleled access to a vast array of products. However, this abundance of choice presents challenges for both consumers and businesses. The surge in product reviews on platforms like Amazon has created a wealth of feedback for consumers to navigate. Yet, for businesses, the challenge lies in extracting meaningful insights from this massive volume of unstructured data.

**Sentiment analysis**, a branch of Natural Language Processing (NLP), automates the extraction of sentiment or opinion from text data. By analyzing sentiments expressed in product reviews, businesses can gain valuable insights into consumer preferences and trends. This project focuses specifically on sentiment analysis for product reviews sourced from Amazon's electronics category. Electronics represent a dynamic and popular category on Amazon, making it crucial for businesses to understand consumer sentiments within this domain.

## Project Description
In the rapidly evolving landscape of e-commerce, businesses face the challenge of harnessing the wealth of customer sentiments embedded within online reviews to drive informed decision-making. The proliferation of product reviews on platforms like Amazon presents a double-edged sword: while these reviews offer invaluable insights into consumer preferences, the sheer volume and diversity of data make it difficult for businesses to extract meaningful and actionable insights efficiently.

This project addresses this issue by developing a machine learning model that classifies customer reviews into positive or negative sentiments. By focusing on the electronics category, the project aims to help businesses in this industry gain deeper insights into consumer opinions and make data-driven decisions.

## Features
- Data Preprocessing: Tokenization, stopword removal, and stemming/lemmatization.
- Vectorization using TF-IDF (Term Frequency-Inverse Document Frequency).
- Supervised learning model using algorithms such as Logistic Regression, Naive Bayes, and Random Forest.
- Performance metrics: Accuracy, Precision, Recall, and F1 Score.

## Project Structure
- `dataset/` - Contains the Amazon review dataset.
- `notebooks/` - Jupyter Notebooks with step-by-step implementation.
- `models/` - Saved trained machine learning models.
- `scripts/` - Python scripts for preprocessing, training, and evaluation.

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, NLTK, Matplotlib
- **Algorithms:** Logistic Regression, Naive Bayes, Random Forest
- **Tools:** Jupyter Notebook

## Installation and Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/amazon-sentiment-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd amazon-sentiment-analysis
    ```
3. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebooks or Python scripts to preprocess data and train the models.

## Dataset
The dataset used contains reviews of electronics products from Amazon, including features like product ID, reviewer ID, rating, and review text.

## Results
The model was able to classify reviews with **90% accuracy**. Below are some of the key results:
- **Confusion Matrix:**
  ![Confusion Matrix](images/confusion_matrix.png)
  
- **Accuracy:** 90%
- **Precision:** 88%
- **Recall:** 92%

## Future Improvements
- Implement deep learning techniques (e.g., LSTM, BERT).
- Extend the analysis to other product categories.
- Create a web-based interface for live sentiment analysis.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or collaborations, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/hitakshi-tanna) or email at hitakshi.email@example.com.
