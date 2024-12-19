---

# Spam Email Classification with NLP

This project aims to classify emails as spam or non-spam using Natural Language Processing (NLP) techniques. The process involves exploring the dataset, cleaning and normalizing the text, building a machine learning model, and evaluating its performance.

## Project Structure

- **`nlp_report`**: A detailed report that outlines the methodology, findings, and conclusions of the project. It includes insights into the techniques used and the models evaluated.
- **`Spam Email raw text for NLP.csv`**: The raw dataset containing emails labeled as spam or non-spam.

## Steps in the Project

### 1. Data Exploration and Visualization

In this step, the dataset is loaded and its structure is explored. We also visualize the distribution of email categories (spam and non-spam) to understand the dataset's composition.

### 2. Text Cleaning and Normalization

The text data undergoes cleaning, which includes converting all text to lowercase, removing non-alphabetical characters, tokenizing the text, removing stopwords, and lemmatizing the words. The cleaned text is then used for further analysis and model training.

Additionally, word clouds for both spam and non-spam emails are generated to visually understand the most frequent words in each category.

### 3. Model Building

In this phase, the data is split into training and testing sets. Several machine learning models are trained to classify the emails based on the cleaned text. These models include:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest

Each model's performance is evaluated using metrics such as precision, recall, and F1-score.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
