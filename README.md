# GENAI1: AI Landing Page & Chatbox

This project is a simple AI-powered landing page with a 3D falling stars effect and a background image. Clicking the **Get Started** button opens an AI chatbox page, where you can interact with Google's Gemini model directly from your browser.

---

## Features
- **Animated landing page** with 3D falling stars and a moving background image.
- **Get Started** button opens a chatbox that simulates running `node LLM.js`.
- **AI chatbox**: Ask anything and get live responses from Gemini (Google GenAI).

---

## How to Use

1. **Open the Project Folder**
   - Go to `C:/Users/subam/GENAI1` in File Explorer.

2. **Open the Landing Page**
   - Double-click `index.html` to open it in your web browser.

3. **Start Chatting**
   - Click the **Get Started** button.
   - A new tab will open with the AI chatbox.
   - The first message is the output of your `LLM.js` script ("Explain how AI works in a few words").
   - Type your own questions and press **Send** to chat with the AI.

---

## Files
- `index.html` — The animated landing page.
- `chat.html` — The AI chatbox page.
- `LLM.js` — Node.js script for Gemini API (for reference; not needed for web chat).
- `package.json` — Project dependencies (for Node.js usage).

---

## Requirements
- Modern web browser (Chrome, Edge, Firefox, etc.)
- Internet connection (to access Gemini API and background image)

---

## Security Note
- The Gemini API key is included in the frontend for demo purposes. **Do not use this setup in production or share your API key publicly.**
- For production, use a backend server to keep your API key secret.

---

## Customization
- To use your own background image, edit the `.background-image` CSS in `index.html`.
- To change the AI prompt, edit the initial call in `chat.html`.

---

## License
This project is for educational/demo use only. 