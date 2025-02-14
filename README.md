# PDF Chatbot

## Overview
The **PDF Chatbot** is an AI-powered tool that allows users to interact with **PDF, Word, and Excel** documents using a conversational interface. It utilizes **Flask** for the backend and integrates **TinyLLaMA** via **Ollama** for AI-powered text generation. The chatbot can process documents, extract key information, and provide meaningful responses based on user queries.

## Features
- **Supports PDF, Word, Excel, and CSV files**
- **Summarizes and processes document content**
- **Allows user queries based on uploaded files**
- **Uses TinyLLaMA for AI-driven responses**
- **Flask-based backend with a simple web interface**

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- Ollama
- Required Python libraries

### Clone the Repository
```sh
git clone <repository_url>
cd pdf-chatbot
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Run the Application
```sh
python app.py
```
The application will start in **debug mode** and can be accessed at `http://127.0.0.1:5000/`.

## Usage
### Uploading Files
1. Navigate to the web interface.
2. Upload a **PDF, Word, Excel, or CSV file**.
3. The chatbot will extract and summarize the content.

### Querying the Chatbot
- Enter a **text query** to ask questions based on the uploaded document.
- The chatbot will generate a response using **TinyLLaMA**.

## Project Structure
```
📂 pdf-chatbot/
│-- app.py               # Main Flask application
│-- templates/
│   ├── chat.html        # Web interface for chatbot
│-- uploads/             # Directory for storing uploaded files
│-- requirements.txt     # Required Python dependencies
```

## Technologies Used
- **Python (Flask)** – Backend framework
- **Ollama** – LLM integration
- **TinyLLaMA** – AI-powered text generation
- **PyPDF2, pandas, python-docx** – Document processing

## License
This project is licensed under the **MIT License**.

## Contributions
Feel free to contribute! Fork the repository, make your changes, and submit a pull request.

---
🚀 Happy Coding!


