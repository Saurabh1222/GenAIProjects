# 📝 AI-Powered Text Summarizer

A Python project that uses Google's **Gemini API** to summarize text using the powerful `gemini-1.5-flash` model.  
This project demonstrates how to securely connect to the Gemini API, send a prompt, and format the model's response for a clean, readable output.

---

## ✨ Features

- **Generative AI**: Leverages the `gemini-1.5-flash` model for fast and efficient text summarization.  
- **Secure API Key Management**: Uses Google Colab's built-in Secrets Manager to keep your API keys safe.  
- **Clean Output Formatting**: Includes a helper function to turn raw model output into clean Markdown.  
- **Step-by-Step Reasoning**: Prompts the model to provide clear reasoning in a structured format.  

---

## 🚀 Getting Started

This project is designed for **Google Colab**, which provides a free, pre-configured environment.

### 🔧 Prerequisites

- A Google Account  
- A Gemini API key from [Google AI Studio](https://makersuite.google.com/app)

---

## ⚙️ Setup

### 1. Get Your API Key
Follow [this guide](https://ai.google.dev/gemini-api/docs/get-api-key) to create a project and get your API key.

### 2. Store Key Securely in Colab
- Click the 🔑 icon (Secrets) on the left side of Colab.
- Add a new secret:
  - **Name**: `GOOGLE_API_KEY`
  - **Value**: *your actual API key*

### 3. Run the Project
- Upload or paste the notebook code into Google Colab.
- The script will:
  - Install required libraries
  - Connect to Gemini API
  - Summarize the input text

---

## 📦 Libraries Used

| Library              | Purpose                                               |
|----------------------|-------------------------------------------------------|
| `google-generativeai` | To access and use Gemini models via API              |
| `IPython.display`     | To display Markdown output nicely in Colab/notebooks |
| `textwrap`            | To indent and format the response into blockquotes   |
| `os`                  | For environment or file handling (if needed)         |
| `google.colab.userdata` | To securely fetch the API key in Colab             |

---

## 🛠️ Usage

Just run the code in Colab. It will:

1. Load the Gemini model
2. Accept your input text
3. Return a clean and structured summary.


