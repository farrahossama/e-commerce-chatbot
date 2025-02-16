# E-Commerce Chatbot

## Project Overview
This project is a conversational AI system for an e-commerce platform. It allows users to interact with a product catalog, ask complex queries, and get relevant responses. The chatbot is built using **Hugging Face's GPT-2 model** and **LangChain** for dialogue management. It supports queries like:
- "Find me all products under $20."
- "What is the delivery charge for Wireless Earbuds?"
- "Show me all available electronics."

## Installation
To run the chatbot, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/farrahossama/e-commerce-chatbot.git
   cd e-commerce-chatbot

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt

3.Run the Jupyter Notebook: ( Incase you are using Google Colab, upload product_catalog.json file into files )

   ```bash
    jupyter notebook

4. Open the e-commerce-bot.ipynb notebook and run all cells.


----------------------------------

Usage

Running the Chatbot:

Open the Jupyter Notebook and run all cells.

Use the input box to type your queries (e.g., "Find me all products under $20").

The chatbot will display the results in the output box.

Example Queries:

"Find me all products under $20."

"Show me all electronics."

"What is the delivery charge for Wireless Earbuds?"

"Show me available products."

----------------------------------------

Code Structure

HuggingFaceLLM: A custom LLM class that integrates Hugging Face's GPT-2 model with LangChain.

filter_products: Filters the product catalog based on the user's query.

chatbot: Generates responses to user queries using the filtered products.

---------------------------------------

Dependencies

transformers

langchain

ipywidgets

json

logging

---------------------------------------

Open Source Compliance


This project uses only open-source libraries and datasets. No proprietary algorithms or copyrighted designs were used.
