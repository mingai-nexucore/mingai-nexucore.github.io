# MingAI
> A fast, modern AI assistant built for productivity, coding, and creative thinking.

**MingAI** is a sleek, single-file web chat interface powered by AI. Built by **NexuCore**, it features a polished dark/light UI, persistent chat history, streaming responses, image generation, image vision, file attachments, text-to-speech, web search, multi-language support, and customizable AI behavior — all with zero backend required.

---

## Features

- **Streaming responses** — AI replies appear in real time as they're generated
- **Image generation** — Switch to MingImage 1.3 to generate images from text prompts
- **Image vision** — Attach images to your messages and MingAI 2.4 will analyze and reason about them
- **Text-to-speech** — Listen to any AI response read aloud with automatic language detection
- **Online research** — Toggle web search to let MingAI pull in live, up-to-date information from the internet
- **File attachments** — Attach code, text, document, and image files directly to your messages
- **PDF analysis** — Attach any PDF and MingAI 2.4 will read and analyze its full contents
- **Chat history** — Conversations are saved to your browser's local storage when signed out, or synced to your Google account when signed in
- **Google Sign-In** — Sign in with your Google account to save and access your conversation history across any device or browser
- **Markdown rendering** — Full markdown support including syntax-highlighted code blocks
- **Customizable system prompt** — Tailor MingAI's personality and behavior via Settings
- **Multi-language interface** — The UI supports 17 languages including English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Russian, Chinese, Japanese, Korean, Arabic, Hindi, Turkish, Indonesian, and Pirate
- **Dark & Light themes** — Toggle between themes, preference is saved automatically
- **Copy buttons** — Copy full responses or individual code blocks with one click
- **Suggestion cards** — Quick-start prompts on the home screen for common tasks
- **Mobile responsive** — Fully functional on phones and tablets with a slide-out sidebar

---

## Account & Chat Saving

All core features work **without an account** — text chat, image generation, image vision, PDF analysis, file attachments, and web search have no restrictions.

**Chat history saving** depends on whether you are signed in:

| State | Chat History |
|---|---|
| **Signed out** | Saved to your browser's local storage only. Clearing browser data will erase history. |
| **Signed in with Google** | Saved to your account and accessible from any device or browser. |

Sign in using the **Sign in** button in the top-right corner of the app.

---

## Usage

| Action | How |
|---|---|
| Send a message | Type and press **Enter** (Shift+Enter for new line) |
| Generate an image | Switch to **MingImage 1.3** tab and describe your image |
| Attach an image | Click **+** → **Attach File** → select an image file |
| Enable web search | Click **+** → toggle **Online Research** |
| Attach a file | Click **+** → **Attach File** |
| Analyze a PDF | Click **+** → **Attach File** → select a PDF file |
| Listen to a response | Click the 🔊 button below any AI response |
| New chat | Click **New chat** in the sidebar |
| Switch chats | Click any conversation in the sidebar |
| Delete a chat | Hover a conversation and click the trash icon |
| Sign in | Click **Sign in** in the top-right corner and choose Google |
| Sign out | Click your name in the top-right corner → **Sign out** |
| Open settings | Click the gear icon in the top-right corner |
| Toggle theme | Settings → Light Mode toggle |
| Change language | Settings → Language |
| Custom AI behavior | Settings → AI Behavior / System Prompt |

---

## Models

| Model | Purpose |
|---|---|
| **MingAI 2.4** | Text chat, coding, writing, analysis, file reading, image vision, PDF analysis |
| **MingImage 1.3** | AI image generation from text prompts |

---

## Customization

In the **Settings** panel you can provide a custom system prompt to change how MingAI responds. For example:

- `"Always respond in a formal tone."`
- `"You are a senior software engineer. Prioritize clean, idiomatic code."`
- `"Respond only in Spanish."`

Your custom instructions are layered on top of MingAI's core behavior and saved across sessions.

---

## Tech Stack

- **Vanilla HTML/CSS/JavaScript** — no frameworks
- **[Marked.js](https://marked.js.org/)** — Markdown parsing
- **[highlight.js](https://highlightjs.org/)** — Syntax highlighting
- **[Firebase Auth](https://firebase.google.com/)** — Google Sign-In
- **Web Speech API** — Built-in browser text-to-speech
- **localStorage** — Client-side chat history persistence (when signed out)

---

## Project Structure

```
mingai/
├── assets/
│   ├── logo.ico
│   ├── logo.png
│   └── thumb.png
├── docs/
│   └── index.html
├── home/
│   └── index.html
├── 404.html
├── google63dcf8c758126a2c.html
├── README.md
└── index.html      # Entire application — UI, styles, and logic in one file
```

---

## License

This project is proprietary software created by **NexuCore**. All rights reserved.

---

*MingAI — Made by NexuCore*
