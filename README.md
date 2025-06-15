# Overview
This project is a book recommender system that helps users find book suggestions based on their input. It utilizes LangChain, Wikipedia API, and OpenAI API to generate relevant book recommendations along with Wikipedia summaries.This was developed to recommend any textbook of interest to its user
# Features
* User inputs a book title
* Retrieves related book suggestions from Wikipedia and generate a clickable link
* Generates a Wikipedia summary for each recommendation using OpenAI API
* Interactive web interface powered by Streamlit
* Quick and easy deployment
# Installation
Clone the repository:
'''bash
git clone https://github.com/auspicie/Book-gpt-recomamender.git
cd book-recommender
Install dependencies:
pip install -r requirements.txt
Set up your OpenAI API key (Create a .env file or set it as an environment variable):
OPENAI_API_KEY="your_api_key_here"
'''bash
# Usage
Run the Streamlit app:
streamlit run app.py
# Tech Stack
Python

Streamlit (for the web interface)

LangChain (for efficient query processing)

Wikipedia API (to fetch book information)

OpenAI API (for generating summaries)
