📝 AI-Powered Text Summarizer
A Python project that uses Google's Gemini API to summarize text using the powerful gemini-1.5-flash model. This project demonstrates how to securely connect to the Gemini API, send a prompt, and format the model's response for a clean, readable output.

✨ Features
Generative AI: Leverages the gemini-1.5-flash model for fast and efficient text summarization.

Secure API Key Management: Safely handles API keys using Google Colab's built-in Secrets Manager.

Clean Output Formatting: Includes a custom helper function to format the raw model output into clean, human-readable Markdown.

Step-by-Step Reasoning: Prompts the model to provide a clear, reasoned, and step-by-step breakdown of its process.

🚀 Getting Started
This project is designed to be run in a Google Colab notebook, which provides a free and pre-configured environment.

Prerequisites
A Google Account.

A Gemini API key from Google AI Studio.

Setup
Get Your API Key: Follow the official guide to get your API key. If you are asked to create a project, follow the prompts in the Google Cloud Console.

Get Your API Key Here

Store Your Key Securely: In your Google Colab notebook, click the key icon on the left-hand side. Add a new secret with the name GOOGLE_API_KEY and paste your key in the "Secret value" field.

Clone the Project: You can either download this notebook file (.ipynb) and upload it to Colab, or copy the code directly into a new Colab notebook cell.

🛠️ Usage
Simply run the code in your Google Colab notebook. The script will automatically install the required libraries, connect to the Gemini API using your key, and execute the summarization task.
