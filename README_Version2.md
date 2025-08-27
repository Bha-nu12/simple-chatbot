# Simple AI Chatbot

This repository contains a simple AI chatbot using HTML, Tailwind CSS, and JavaScript.  
The chatbot UI is modern and clean, and can be connected to Google's Gemini API (or similar) for AI-powered responses.

## Features

- Responsive, elegant interface with Tailwind CSS
- User and Bot chat bubbles
- Loading indicator for bot response
- Handles rate limiting with exponential backoff
- Conversation history for context
- Easily customizable code

## Getting Started

1. **Clone the repository** or download the files.
2. **Open `simple_ct.html`** in your web browser.
3. **Enter your Gemini API key** in the `apiKey` variable inside the JS of `simple_ct.html` (if you want to use Gemini).
4. **Start chatting!**

## API Integration

- The provided code uses the Gemini API endpoint.
- You need a Google AI API Key to use the Gemini response feature.
- To use another provider, update the `apiUrl` and adjust the payload as needed.

## File List

- `simple_ct.html` - Main chatbot UI and logic
- `README.md` - This file

## Example Usage

- Type your message and hit "Send"
- View responses in real-time

---

Feel free to customize for your own AI provider or bot logic!