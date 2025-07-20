# GENAI1: AI Landing Page & Chatbox

---

## 🚀 Live Demo

The project is now live! You can try it here:

👉 [https://lustrous-genie-713a9b.netlify.app/](https://lustrous-genie-713a9b.netlify.app/)

Visit the link above to experience the AI-powered landing page and chatbox in action. Share this link with anyone—you can access it from any device, anywhere!

---

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

---

Great news! You already have your project on GitHub at:  
[https://github.com/Subamprasad/GEN-AI](https://github.com/Subamprasad/GEN-AI)

To make your project accessible via HTTPS so anyone can use it from any device, you just need to enable **GitHub Pages** for your repository. Here’s how:

---

## How to Enable GitHub Pages for Your Project

1. **Go to your repository:**  
   [https://github.com/Subamprasad/GEN-AI](https://github.com/Subamprasad/GEN-AI)

2. **Click on the “Settings” tab** (top right of the repo page).

3. **Scroll down to the “Pages” section** (in the left sidebar, or scroll down if using the new UI).

4. **Set the source:**
   - Under “Branch”, select `main`.
   - Under “/ (root)”, select the root folder.
   - Click **Save**.

5. **Wait a minute.**  
   GitHub will build your site. After a short time, you’ll see a green success message with your new HTTPS link.  
   It will look like:  
   ```
   https://subamprasad.github.io/GEN-AI/
   ```

6. **Share this link!**  
   Anyone can now open your project from any device using this HTTPS link.

---

### Example

If your username is `Subamprasad` and your repo is `GEN-AI`, your link will be:  
**https://subamprasad.github.io/GEN-AI/**

---

## Important Security Note

Your current setup exposes your Gemini API key in the frontend.  
- This is fine for demos and learning, but **do not use this in production** or share your API key publicly for real applications.
- For production, use a backend server to keep your API key secret.

---

## Reference

You can find more about GitHub Pages in the [GitHub Docs](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

---

Let me know when you’ve enabled GitHub Pages, or if you need step-by-step screenshots or further help! 