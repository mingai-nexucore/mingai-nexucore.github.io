# MingAI

> A fast, modern AI assistant built for productivity, coding, and creative thinking.

**MingAI** is a sleek, single-file web chat interface powered by AI. Built by **NexuCore**, it features a polished dark/light UI, persistent chat history, streaming responses, image generation, file attachments, web search, multi-language support, and customizable AI behavior — all with zero backend required.

---

## Features

- **Streaming responses** — AI replies appear in real time as they're generated
- **Image generation** — Switch to MingImage 1.3 to generate images from text prompts
- **Online research** — Toggle web search to let MingAI pull in live, up-to-date information from the internet
- **File attachments** — Attach code, text, and document files directly to your messages for MingAI to read and analyze
- **Chat history** — Conversations are saved locally and accessible from the sidebar
- **Markdown rendering** — Full markdown support including syntax-highlighted code blocks
- **Customizable system prompt** — Tailor MingAI's personality and behavior via Settings
- **Multi-language interface** — The UI supports 17 languages including English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Russian, Chinese, Japanese, Korean, Arabic, Hindi, Turkish, Indonesian, and Pirate
- **Dark & Light themes** — Toggle between themes, preference is saved automatically
- **Copy buttons** — Copy full responses or individual code blocks with one click
- **Suggestion cards** — Quick-start prompts on the home screen for common tasks
- **Mobile responsive** — Fully functional on phones and tablets with a slide-out sidebar

---

## Usage

| Action | How |
|---|---|
| Send a message | Type and press **Enter** (Shift+Enter for new line) |
| Generate an image | Switch to **MingImage 1.3** tab and describe your image |
| Enable web search | Click **+** → toggle **Online Research** |
| Attach a file | Click **+** → **Attach File** |
| New chat | Click **New chat** in the sidebar |
| Switch chats | Click any conversation in the sidebar |
| Delete a chat | Hover a conversation and click the trash icon |
| Open settings | Click the gear icon in the top-right corner |
| Toggle theme | Settings → Light Mode toggle |
| Change language | Settings → Language |
| Custom AI behavior | Settings → AI Behavior / System Prompt |

---

## Models

| Model | Purpose |
|---|---|
| **MingAI 2.1** | Text chat, coding, writing, analysis, file reading |
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
- **localStorage** — Client-side chat history persistence

---

## Project Structure

```
mingai/
└── index.html      # Entire application — UI, styles, and logic in one file
```

---

## License

This project is proprietary software created by **NexuCore**. All rights reserved.

---

*MingAI — Made by NexuCore*
