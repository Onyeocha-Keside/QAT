# AI Document Processing and Evaluation API

Flask-based API that allows users to upload documents, generate summaries, and ask questions using OpenAI's GPT-3.5-turbo model. Supported file types include text, PDF, and DOC files, with data stored in an SQLite database.

## Features
- Upload and process documents (TXT, PDF, DOC).
- Generate summaries using OpenAI API.
- Submit questions about documents and get JSON responses.
- Save feedback in both text files and the database.

## Installation

### Prerequisites
- Python 3.8+
- OpenAI API Key

### Setup
1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/Sanctum-AI-Document-Processing.git
   cd Sanctum-AI-Document-Processing
