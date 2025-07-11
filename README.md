My project is a book recommendation system built using large language models (LLMs), vector search, and an interactive Gradio interface. It uses semantic similarity between book descriptions to help users discover books similar to the ones they like.

Features

1. Semantic search using Gemini embeddings and FAISS
2. Text data exploration and cleaning using Python
3. Genre classification using zero-shot learning
4. Sentiment analysis with fine-tuned LLMs
5. Interactive Gradio dashboard for book recommendations
6. Vector database built using LangChain's text splitting and FAISS

Technologies Used

1. Python
2. LangChain
3. Gemini API
4. Hugging Face Transformers
5. Gradio
6. FAISS
7. Pandas and NumPy

How It Works

Clean the book descriptions and remove irrelevant or short data.
Use Gemini API to generate embeddings for each book.
Store the embeddings in a FAISS vector database for fast search.
Use Hugging Face models to classify genres and sentiments.
Build an interactive Gradio app where users can select a book and get similar ones recommended.
