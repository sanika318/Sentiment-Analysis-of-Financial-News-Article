# Sentiment Analysis of Financial News Using NLTK and Spacy

This project performs sentiment analysis on financial news articles using NLTK and Spacy. The notebook provides step-by-step instructions for processing and analyzing the sentiment of news headlines from financial sources.

## About the Dataset

The dataset used in this project is sourced from Kaggle and consists of two CSV files:
- **Guardian Headline Dataset:** 17,800 records
- **Reuters Headline Dataset:** 32,770 records

**Dataset Link:** [Financial News Headlines on Kaggle](https://www.kaggle.com/datasets/notlucasp/financial-news-headlines/code)

### Columns in the Dataset

#### CNBC Headline Dataset:
1. **time:** The timestamp of the news headline.
2. **headlines:** The news headline.
3. **description:** A brief description of the news.

#### Reuters Headline Dataset:
1. **time:** The timestamp of the news headline.
2. **headline:** The news headline.
3. **description:** A brief description of the news.

## Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/sanika318/Sentiment-Analysis-of-Financial-News-Article.git
    ```

2. **Download the dataset:**
    Download the CSV files from the [Kaggle dataset](https://www.kaggle.com/datasets/notlucasp/financial-news-headlines/code) and place them in the runtime environment before running the notebook.

3. **Install the required libraries:**
    Ensure that the following Python libraries are installed:
    ```bash
    pip install nltk spacy pandas
    ```

4. **Run the notebook:**
    Open the `CDS_PROJECT.ipynb` notebook and run all cells to perform the sentiment analysis.

## Project Structure

- `CDS_PROJECT.ipynb`: The main Jupyter notebook containing the code for sentiment analysis.
- `README.md`: This file, providing an overview of the project.

## Results

The notebook processes and predicts sentiment for financial news articles and also includes a section for performing live sentiment analysis on articles scraped from URLs.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.
