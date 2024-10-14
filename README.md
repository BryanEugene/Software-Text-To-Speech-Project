# Text Summarization and Speech App

This is a web-based application built with **Streamlit** that provides a suite of tools for text processing, including text summarization, speech synthesis, paper translation, paper recommendation, and guidelines. This project offers a simple and intuitive user interface for working with various text-related functionalities.



## How to Run the Project

### Prerequisites
- Python 3.x
- Streamlit library

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/text-summarization-speech.git
   cd text-summarization-speech
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

4. Open the local development server on your browser at `http://localhost:8501/`.


## Features
1. **Text to Speech**: Converts the input text or uploaded PDF files into audio.
2. **Summarize Text**: Extracts key points from long documents, either text or PDF, using various summarization techniques.
3. **Translate Paper**: Translates academic papers or any PDF document into the desired language.
4. **Recommendation Paper**: Provides relevant paper recommendations based on the content provided.
5. **Roadmap and Guidelines**: Offers a comprehensive guide and roadmap for using the app.

## Libraries Used

### Text to Speech
- `streamlit`: For building the web interface.
- `gTTS`: Google Text-to-Speech for converting text to audio.
- `PyPDF2.PdfReader`: For reading PDF files.
- `numpy`: For numerical computations.

### Summarize
- `streamlit`: Web interface.
- `PyPDF2.PdfReader`: PDF reading capabilities.
- `nltk.tokenize.sent_tokenize`: Tokenizes text into sentences.
- `nltk.corpus.stopwords`: For filtering stop words in text processing.
- `sklearn.feature_extraction.text.TfidfVectorizer`: TF-IDF vectorizer for extracting important features.
- `gTTS`: Google Text-to-Speech.
- `sentence_transformers.SentenceTransformer`: For generating embeddings from sentences.
- `sklearn.metrics.pairwise.cosine_similarity`: To calculate the similarity between sentences.
- `transformers.BartForConditionalGeneration`, `BartTokenizer`: For advanced text summarization using the BART model.

### Translate
- `streamlit`: Web interface.
- `googletrans.Translator`: For translating text into various languages.
- `PyPDF2.PdfReader`: For extracting text from PDFs.

### Recommendation Paper
- `streamlit`: Web interface.
- `sklearn.feature_extraction.text.TfidfVectorizer`: For converting text into feature vectors.
- `sklearn.metrics.pairwise.linear_kernel`: To compute similarities between papers.
- `pandas`: For handling tabular data and displaying recommendations.

## How to Use
1. Clone the repository and navigate to the project directory.
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Roadmap and Guidelines
The application includes a guide and roadmap for users to understand and explore the different functionalities effectively. Each page provides detailed instructions for optimal use.

### Technologies Used
- **Streamlit**: Fast, interactive web application framework for data science and machine learning.
- **Python**: Core programming language for the app.
  
## Future Enhancements

- Add more languages to the translation feature.
- Enhance recommendation algorithms for research papers.
- Improve the quality of text summarization and speech synthesis.

## Author
Bryan Eugene - [GitHub Profile](https://github.com/your-github-username)