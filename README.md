# Birthday Video Generator

Create magical, personalized birthday videos with AI-powered scenes, effects, and music! This web app lets you generate a custom birthday video by entering the recipient's name, your name, a custom message, and selecting scenes and effects. The app uses Google's Gemini/Veo APIs for AI video generation, with a canvas fallback for instant results.

## Features

- 🎉 Multiple scenes: Party, Garden, Beach, Sunset
- 🌐 Language support: Hinglish, English, Hindi
- ✨ Video effects: Balloons, Confetti, Fireworks, Background Music
- 📝 Custom birthday message and sender name
- 🖼️ Beautiful, responsive UI with animated backgrounds
- 🪄 AI-powered video generation (with fallback to animated canvas video)
- 📥 Download your generated video

## 🎬 Demo

See the Birthday Video Generator in action:

![Birthday Video Demo](demo.gif)

![WhatsApp Image 2025-08-30 at 00 52 31_f5b78e1e](https://github.com/user-attachments/assets/dbdd94ad-b5e1-4a58-989c-c975f7194760)

## How to Use

1. **Open `index.html` in your browser.**
2. Fill in the birthday person's name and (optionally) your name.
3. Enter a custom birthday message or use the suggested one.
4. Choose your preferred scene and effects.
5. Select the language for the message.
6. Click **"Generate Birthday Video ✨"**.
7. Wait for the video to be generated (AI or fallback).
8. Download your video or create another!

## Project Structure

- [`index.html`](index.html): Main HTML file containing all code (HTML, CSS, JavaScript).

## Notes

- The app attempts to use Google's Gemini/Veo APIs for AI video generation. If the API is unavailable, it falls back to generating an animated video using HTML5 Canvas.
- No backend server is required; everything runs in the browser.
- For real deployment, you should secure your API keys and consider backend proxying.

## Requirements

- Modern web browser (Chrome, Edge, Firefox, Safari)
- Internet connection (for AI video generation)

## Disclaimer

This project is for educational/demo purposes. The AI video generation depends on the availability and access to Google's Gemini/Veo APIs.

---

**Enjoy creating magical birthday wishes!
