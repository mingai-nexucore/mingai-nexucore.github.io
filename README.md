# MingAI

> A fast, modern AI assistant built for productivity, coding, and creative thinking.

**MingAI** is a sleek, single-file web chat interface powered by AI. Built by **NexuCore**, it features a polished dark/light UI, persistent chat history, streaming responses, and customizable AI behavior — all with zero backend required.

---

## Features

- **Streaming responses** — AI replies appear in real time as they're generated
- **Chat history** — Conversations are saved locally and accessible from the sidebar
- **Markdown rendering** — Full markdown support including syntax-highlighted code blocks
- **Customizable system prompt** — Tailor MingAI's personality and behavior via Settings
- **Dark & Light themes** — Toggle between themes, preference is saved automatically
- **Copy buttons** — Copy full responses or individual code blocks with one click
- **Suggestion cards** — Quick-start prompts on the home screen for common tasks
- **Mobile responsive** — Fully functional on phones and tablets with a slide-out sidebar

---

## Getting Started

MingAI is a single HTML file — no build step, no dependencies to install.

1. Clone or download this repository
2. Open `index.html` in any modern browser
3. Start chatting

```bash
git clone https://github.com/your-username/mingai.git
cd mingai
open index.html
```

---

## Usage

| Action | How |
|---|---|
| Send a message | Type and press **Enter** (Shift+Enter for new line) |
| New chat | Click **New chat** in the sidebar |
| Switch chats | Click any conversation in the sidebar |
| Delete a chat | Hover a conversation and click the trash icon |
| Open settings | Click the gear icon in the top-right corner |
| Toggle theme | Settings → Light Mode toggle |
| Custom AI behavior | Settings → AI Behavior / System Prompt |

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
