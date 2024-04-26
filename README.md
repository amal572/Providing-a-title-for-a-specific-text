# NLP Project

The project aims to generate a suitable title for a given text. We preprocess and segment the data, then train several models. Next, we take a specific piece of news from the test set and find the main topic of the text to provide a suitable title. We extract the most important words from these topics and input them into the previous models to form the title. Then, we measure how closely these titles align with the given text, and titles are generated using the AraGPT2 model.

## Data Description

Attempting to generate a title for a text in Arabic, I used the Hespress dataset which can be downloaded from Kaggle: [Hespress Dataset](https://www.kaggle.com/datasets/tariqmassaoudi/hespress). It consists of a collection of Arabic news, and the training was conducted on the titles of these news articles.

## Models Used

I used several deep-learning models to attempt title generation and found that the Attention model performed better than other models.

## Usage

I use Google Colab to train the model.
