# Fake-News-Detection using Pattern Recognition

A Machine Learning-based application that classifies news articles as **Real** or **Fake** by analyzing textual content. The project leverages Natural Language Processing (NLP) techniques and supervised machine learning algorithms to identify misinformation and improve news credibility assessment.

## Project Overview
With the rapid spread of information through digital platforms, distinguishing between genuine and misleading news has become increasingly important. This project aims to automate the detection of fake news by training a machine learning model on labeled news datasets and providing predictions based on user-input news content.

## Features
* Detects whether a news article is Real or Fake
* Text preprocessing and cleaning pipeline
* NLP-based feature extraction
* Machine Learning model training and evaluation
* User-friendly prediction interface
* Model performance visualization and analysis

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Jupyter Notebook

## ⚙️ Installation
1. Clone the repository:

```bash
git clone https://github.com/mranjit14/Fake-News-Detection.git
cd Fake-News-Detection
```

2. Create a virtual environment (optional):

```bash
python -m venv venv
```

3. Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

4. Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python app.py
```

Enter the news text/article content and the system will predict whether it is:
* ✅ Real News
* ❌ Fake News

## Methodology
1. Data Collection
2. Data Cleaning and Preprocessing
3. Text Vectorization (TF-IDF/Count Vectorization)
4. Model Training
5. Model Evaluation
6. Prediction and Deployment

## Model Evaluation
Common evaluation metrics used:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Future Improvements
* Deep Learning-based classification
* Transformer models (BERT, RoBERTa)
* Real-time news verification
* Web application deployment
* Multi-language support

## License
This project is intended for educational and academic purposes.
