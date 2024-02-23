# ChatGPT-like Chat App

This project implements a simple chat application using OpenAI's API to generate responses. It utilizes Streamlit for the user interface and OpenAI's assistant API for text generation.

## Overview

The application allows users to initiate a chat session with an AI assistant, similar to ChatGPT. Users can interact with the assistant by typing messages, and the assistant responds accordingly based on the context of the conversation.

## Features

- Integration with OpenAI's API for text generation.
- User-friendly interface built with Streamlit.
- Ability to upload files for the assistant to reference during the conversation.
- Support for scraping text from websites, converting it to PDF, and uploading it to the assistant for reference.
- Option to configure OpenAI API key for authentication.

## Getting Started

To run the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies listed in the `requirements.txt` file.
3. Set up your OpenAI API key and configure it within the application.
4. Run the Streamlit application using the command `streamlit run app.py`.
5. Start a chat session by uploading files or providing text input.

## Dependencies

- openai
- streamlit
- BeautifulSoup
- requests
- pdfkit

## Usage

1. Configure your OpenAI API key in the sidebar of the application.
2. Upload files or provide text input to start a chat session.
3. Interact with the AI assistant by typing messages in the chat interface.
4. The assistant will respond based on the conversation context and provided input.
