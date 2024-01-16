# Sentiment-analysis-with-LLMs
A collection of sentiment analysis made with pre-trained LLMs. One applies to Chinese hotel reviews, and the other to twitter tweets.


## Usage
1. Mount your Google Drive to access the dataset:
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
2. Load and preprocess the dataset from your Drive. The dataset should be in two directories `/content/drive/My Drive/China hotel review/pos` for positive reviews and `/content/drive/My Drive/China hotel review/neg` for negative reviews.
3. Split the dataset into training and evaluation sets.
4. Train the sentiment analysis model on this data.
5. Evaluate the model's performance on the evaluation set.

## Data
The dataset consists of hotel reviews, classified into positive and negative categories. Due to oversized files, the dataset is not included in this repository.




