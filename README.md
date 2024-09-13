# Chatbot Hugging Face Integration

This repository contains a chatbot application using Hugging Face models and Chainlit. The chatbot is designed to provide clear and concise responses to user queries by leveraging advanced language models.

## Project Overview

The chatbot utilizes the `mistralai/Mistral-Nemo-Instruct-2407` model from Hugging Face to generate responses based on user input. The application is built with Chainlit, which handles incoming messages and integrates with the Hugging Face model for processing.

## Features

- **Hugging Face Integration**: Uses the `mistralai/Mistral-Nemo-Instruct-2407` model for natural language understanding and response generation.
- **Chainlit Integration**: Manages incoming messages and generates responses asynchronously.
- **Environment Configuration**: Utilizes environment variables for configuration settings.

## Requirements

- Python 3.7 or higher
- Required Python libraries:
  - `transformers`
  - `chainlit`
  - `torch`
  - `python-dotenv`

## Setup and Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Om-Shankar-Thakur/chatbot-huggingFace.git
   cd chatbot-huggingFace


2. **Create a Virtual Environment (Optional but recommended)**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. ***Install Dependencies***

    ```bash
    pip install -r requirements.txt

4. ***Configure Environment Variables***
Create a .env file in the root directory of the project and add your configuration. Example:
    ```bash
    # .env file
    MODEL_ID=mistralai/Mistral-Nemo-Instruct-2407

5. ***Run the Application***
   
    ```bash
    chainlit run app.py
