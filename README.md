# SummarizeMe - AI Text Summarizer App

## Project Overview

**SummarizeMe** is an AI-powered text summarizer web application that leverages the Hugging Face Inference API to provide accurate and efficient text summarization. Users can input long articles or documents, and the app generates a concise summary, preserving the main ideas and key points of the content. The app is built using Node.js for the backend, HTML/CSS/JavaScript for the frontend, and integrates with the Hugging Face API for AI-powered summarization.

## Features

- **Text Input**: Users can input long text, articles, or documents into the input field.
- **AI Summarization**: Using the Hugging Face Inference API, the app processes the text and generates a summary.
- **User-Friendly Interface**: Simple and intuitive UI for seamless interaction.
- **Real-Time Summarization**: Summaries are generated in real-time as users input their text.
- **Responsiveness**: The app is designed to be responsive and works well on both desktop and mobile devices.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js
- **AI API**: Hugging Face Inference API (for text summarization)
- **Hosting**: Replit / GitHub Codespaces (for deployment)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/udayvelupuri1/AI-Text-Summarizer.git
   cd AI-Text-Summarizer
   ```

2. **Install dependencies**:
   Install the required Node.js dependencies:
   ```bash
   npm install
   ```

3. **Set up Hugging Face API**:
   - Create an account on [Hugging Face](https://huggingface.co/).
   - Obtain an API key for the Hugging Face Inference API.
   - Add the API key to the environment variables or directly in the code.

4. **Run the application**:
   - Start the application using Node.js:
   ```bash
   node app.js
   ```
   - Access the app in your browser at `http://localhost:3000`.

## How It Works

- **Frontend**: The user interface allows users to input text or upload documents. The entered text is sent to the backend for processing.
- **Backend**: The Node.js server handles requests from the frontend, sends the text to the Hugging Face Inference API for summarization, and returns the generated summary.
- **Hugging Face API**: The Hugging Face API processes the text using advanced AI models and generates the summary, which is sent back to the frontend for display.

## Contributing

Contributions are welcome! If you would like to contribute to the project, feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
