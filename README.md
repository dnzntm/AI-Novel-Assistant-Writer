# AI Novel Assistant Writer

A simple, browser-based AI companion to help you **write**, **refine**, and **develop** your novel. It focuses on three core workflows: generating chapters from a synopsis, polishing existing chapters, and brainstorming story directions.

> Note: The current version uses simulated AI responses in the browser. You can easily wire it up to real AI APIs (OpenAI, Claude, etc.) by editing one file: `index.html`.

---

## Features

### Generate Chapter from Synopsis
- Turn a short synopsis into a full chapter draft.
- Choose genre (fantasy, sci‑fi, mystery, romance, etc.).
- Select point of view (first person, third limited, third omniscient).
- Pick an approximate target length (short, medium, long).
- Word counter for your input and generated output.

### Refine Existing Chapter
- Paste your existing chapter text and get a cleaned-up version.
- Focus modes:
  - All improvements
  - Punctuation only
  - Grammar & syntax
  - Dialogue formatting
  - Sentence flow & readability
- Shows a summary list of improvements applied.
- Copy-to-clipboard and download-as-text buttons.

### Story Development Ideas
- Describe your story so far and where you’re stuck.
- Get suggestions for:
  - Plot developments
  - Character arcs
  - Twists and reveals
  - World-building angles
  - Conflict escalation and subplots
- Genre-aware prompts to keep ideas on tone.
- Output is easy to copy or download.

---

## 🏁 Getting Started

### 1. Download and Run Locally

1. Download `index.html` from this repository.
2. Double-click it or open it in any modern browser (Chrome, Firefox, Edge, Safari).
3. That’s it – no build step, server, or install needed.

### 2. Repository Structure

```text
novel-assistant-writer/
├── index.html   # Complete standalone web app (HTML + CSS + JS)
└── README.md    # Project documentation
