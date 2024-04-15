# LLM-Chat-Bot

## Overview
The LLM-Chat-Bot is an application where users can submit queries on a specific topic, and the chatbot, powered by Gemini Pro, will provide accurate and reliable responses. This system is designed to ensure responses are free from hallucinations and are strictly based on the provided document context.

## Installation

To set up the chatbot, follow these steps:

1. **Install Required Packages**
   Ensure you have Python and pip installed on your system, and then run the following command to install dependencies from the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt

# Usage

Once you have the application running, you will be prompted to input a query:

1. Provide a query related to the content of the PDF document named "Wiki Document.pdf".
2. The chatbot will process your input and respond accordingly. If your query is outside the scope of the document, the response will be:
   I don't know. The provided context does not mention anything about <query's content>.

# Contributing
Contributions are welcome! Please feel free to fork the repository, make changes, and submit pull requests. If you have any questions or suggestions, please open an issue in the repository.
