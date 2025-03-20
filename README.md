# ChatBot

A simple chatbot interface built with HTML, CSS, and JavaScript, using the OpenRouter API for responses.

## Features

- Clean, responsive UI.
- Input field for user questions.
- Fetches and displays chatbot responses with Markdown support.

## How to Use

1. Open `index.html` in a browser.
2. Enter a question in the input field.
3. Click "Ask!" to get a response.

## Technologies Used

- **HTML5**, **CSS3**, **JavaScript**
- **Bootstrap 4.3.1** for styling.
- **Marked.js** for Markdown rendering.

## API Integration

- **Endpoint**: `https://openrouter.ai/api/v1/chat/completions`
- **Method**: `POST`
- **Headers**: Authorization, Content-Type, etc.
- **Body**:
  ```json
  {
    "model": "deepseek/deepseek-r1:free",
    "messages": [{ "role": "user", "content": "Your question here" }]
  }
