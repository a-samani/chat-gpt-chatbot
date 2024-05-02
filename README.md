# Real-Time Chat Application with AI Integration

## Overview
This project is a real-time chat application powered by FastAPI and WebSocket, featuring dynamic conversation capabilities through the integration of OpenAI's GPT-4 model. It includes secure API key storage via environment variables and asynchronous server-side operations to manage user inputs and AI responses efficiently. The application also supports image generation using OpenAI's image API, demonstrating the ability to handle various media types.

## Features
- Real-time messaging with WebSocket.
- Integration of OpenAI's GPT-4 for intelligent conversation responses.
- Environment variable management for secure API key handling.
- Asynchronous server-side operations for real-time interaction.
- Responsive user interface using Jinja2Templates.
- Image generation capabilities with OpenAI's image API.

## Installation
To set up the project, follow these steps:
1. Clone the repository:
```shell
git clone https://github.com/a-samani/chat-gpt-chatbot.git
```
2. Install the required dependencies:
```shell
pip install -r requirements.txt
```
3. Set up the .env file with your OPENAI_API_SECRET_KEY.

## Usage
To run the application:
```console
uvicorn main:app --reload
```
## Usage
To run the application:

Navigate to http://127.0.0.1:8000/ in your web browser to access the chat interface.

## Contributing
Contributions are welcome! Please feel free to submit pull requests or create issues for any enhancements or bug fixes.
