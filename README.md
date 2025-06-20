# AI Chatbot using Gemini API

This is a simple, responsive AI chatbot built using vanilla JavaScript. It integrates with Google’s Gemini 2.0 Flash API to generate real-time, intelligent responses based on user input.

## Features

- Connects with Gemini API to fetch AI-generated replies
- Simple and clean chat interface
- Auto-scroll to latest messages
- Lightweight and dependency-free
- Cleans up markdown-style formatting from API output

  https://aichatbot11.w3spaces-preview.com/index.html

## Getting Started

1. **Clone the repository**

   bash
   [git clone https://github.com/your-username/ai-chatbot-gemini.git
   cd ai-chatbot-gemini](https://github.com/sherin-11/Ai-Chatbot.git)


2. **Open `index.html` in your browser**
   No setup or build tools required.

3. **Add your Gemini API key**
   In `script.js`, replace the placeholder in the URL with your API key:

   ```js
   const Api_Url = "https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=YOUR_API_KEY"
   ```

## How It Works

* User enters a message in the input field.
* The chatbot displays the user’s message.
* After a short delay, a request is sent to the Gemini API.
* The response is parsed and shown in the chat interface.

## Author

Sherin Mary Rajee
Final-year CSE student at College of Engineering, Trivandrum
Portfolio: [https://know-abt-me.vercel.app/](https://know-abt-me.vercel.app/)


