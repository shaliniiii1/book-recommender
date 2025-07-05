This is a book recommendation system built using large language models (LLMs), vector search, and an interactive Gradio interface. It uses semantic similarity between book descriptions to help users discover books similar to the ones they like.

Features

Semantic search using OpenAI embeddings and FAISS

Text data exploration and cleaning using Python

Genre classification using zero-shot learning

Sentiment analysis with fine-tuned LLMs

Interactive Gradio dashboard for book recommendations

Vector database built using LangChain's text splitting and FAISS

Technologies Used

Python

LangChain

OpenAI API

Hugging Face Transformers

Gradio

FAISS

Pandas and NumPy

Project Structure
books_cleaned.csv - Dataset containing cleaned book descriptions
data-exploration.ipynb - Data cleaning and initial exploration
sentiment-analysis.ipynb - Extracts emotions from book descriptions using LLMs
text-classification.ipynb - Classifies books into genres using zero-shot models
vector-search.ipynb - Embeds descriptions and performs similarity search
tagged_description.txt - Descriptions tagged with genre or sentiment

How It Works

Clean the book descriptions and remove irrelevant or short data.

Use OpenAI to generate embeddings for each book.

Store the embeddings in a FAISS vector database for fast search.

Use Hugging Face models to classify genres and sentiments.

Build an interactive Gradio app where users can select a book and get similar ones recommended.

Setup Instructions
Clone the repository

git clone https://github.com/shaliniiii1/book-recommender.git
cd book-recommender

Install the dependencies

pip install -r requirements.txt

Set your API keys in a .env file

OPENAI_API_KEY=your_openai_key

Run the notebooks or launch the Gradio interface

python app.py
