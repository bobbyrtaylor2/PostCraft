# PostCraft — AI-Powered Social Media Studio

> **Free. Browser-based. Built for nonprofits and small businesses.**
> Generate platform-perfect social media posts using the AI provider of your choice — no subscription, no login, no data collection.

---

## Table of Contents

- [What Is PostCraft?](#what-is-postcraft)
- [Who Is It For?](#who-is-it-for)
- [Features](#features)
- [Supported Platforms](#supported-platforms)
- [Supported AI Providers](#supported-ai-providers)
- [Getting Started](#getting-started)
- [Using LM Studio (Local AI)](#using-lm-studio-local-ai)
- [Content Calendar & CSV Export](#content-calendar--csv-export)
- [Privacy & Data Policy](#privacy--data-policy)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

---

## What Is PostCraft?

PostCraft is a single-file HTML tool that uses AI to write social media posts tailored to each platform's character limits, tone, and best practices. Fill in the **5 W's** (Who, What, Where, Why, When), choose your platform and tone, and PostCraft generates a ready-to-publish post in seconds.

It runs entirely in your browser. There is no server, no database, no account to create, and nothing to install.

---

## Who Is It For?

PostCraft was built specifically for:

- 🏛️ **Nonprofit organizations** — Tell your mission-driven stories consistently without a dedicated marketing team or budget
- 🏪 **Small businesses** — Maintain a professional social media presence without paying $50–$300/month for enterprise tools
- 👤 **Solo operators** — Founders, executive directors, and owner-operators who wear every hat and need to move fast
- 📣 **Community advocates** — Anyone with an important story to tell and limited time to tell it

---

## Features

| Feature | Details |
|---|---|
| 🤖 **Multi-AI Support** | Claude, GPT-4o, Gemini 2.5 Flash, and local LM Studio models |
| 📱 **6 Platforms** | 𝕏/Twitter, Instagram, LinkedIn, Facebook, Threads, TikTok |
| ✍️ **5 W's Framework** | Structured storytelling: Who, What, Where, Why, When |
| 📏 **Auto-Sized Posts** | Each post is written to the exact character limit of the chosen platform |
| 🗓️ **Content Calendar** | Schedule posts with date/time, view all upcoming content in one place |
| 📤 **CSV Export** | Export your full content calendar for use in spreadsheets or scheduling tools |
| 🖼️ **Photo Upload** | Attach images for preview; photos are displayed in the post preview pane |
| ✏️ **In-App Editing** | Edit any AI-generated post before copying or scheduling it |
| 🔒 **Full Privacy** | All data stays in your browser — nothing is sent to any external server |
| 🆓 **Completely Free** | No subscription, no freemium tier, no hidden costs |

---

## Supported Platforms

| Platform | Character Limit | Writing Style |
|---|---|---|
| 𝕏 / Twitter | 280 | Punchy, hook-driven, tight CTAs |
| Instagram | 2,200 | Story-forward, emoji-rich, hashtag block |
| LinkedIn | 3,000 | Long-form professional, first-person authority |
| Facebook | 63,206 | Conversational, community-focused |
| Threads | 500 | Authentic, casual, hot-take friendly |
| TikTok | 2,200 | Fast-paced, Gen-Z aware, trending hashtags |

---

## Supported AI Providers

PostCraft works with four AI providers. You can switch between them at any time.

### 🤖 Claude (Anthropic)
Anthropic's Claude Sonnet 4 — strong at nuanced, long-form writing and platform tone-matching.
- **Requires:** An Anthropic API key from [console.anthropic.com/api-keys](https://console.anthropic.com/api-keys)
- **Cost:** Pay-per-use via Anthropic's API pricing

### ✦ OpenAI (GPT-4o)
OpenAI's flagship model — fast and broadly capable.
- **Requires:** An OpenAI API key from [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
- **Cost:** Pay-per-use via OpenAI's API pricing

### 🔵 Google Gemini (3.0 Flash Preview)
Google's Gemini 3.0 Flash Preview — fast, efficient, and well-suited for high-volume use.
- **Requires:** A Gemini API key from [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
- **Cost:** Free tier available; pay-per-use beyond that

### 🖥️ LM Studio (Local Models)
Run any locally-hosted model through LM Studio's OpenAI-compatible API server.
- **Requires:** [LM Studio](https://lmstudio.ai) installed and running on your machine
- **Cost:** Completely free — no API fees, no internet required
- **Privacy:** Your content never leaves your device

> **API keys are stored only in your browser's local storage.** They are never transmitted to any server other than the AI provider you are actively using.

---

## Getting Started

PostCraft requires no installation. It runs as a single HTML file in any modern browser.

**Step 1 — Download**

Download `postcraft.html` and save it anywhere on your computer.

**Step 2 — Open in Browser**

Double-click `postcraft.html`, or drag it into Chrome, Firefox, or Edge.

> Safari is supported but Chrome or Firefox is recommended for best compatibility.

**Step 3 — Add Your API Key**

Click **⚙ API Keys** in the top-right corner. Add your API key for your preferred AI provider and click **✓ Save Keys**.

**Step 4 — Select Your Provider & Platform**

Click the AI provider card you want to use (Claude, OpenAI, Gemini, or LM Studio), then click the platform pill for where you'll be posting.

**Step 5 — Fill In the 5 W's**

| Field | Example |
|---|---|
| **Who** | Our food bank volunteers |
| **What** | Packed 10,000 meals in a single weekend |
| **Where** | Cleveland, Ohio |
| **Why** | To support families facing food insecurity this winter |
| **When** | Saturday, March 15 |

Add optional hashtags, select a tone, and attach a photo if you have one.

**Step 6 — Generate**

Click **✦ Generate Post**. Your AI-written post appears in the preview pane on the right. Copy it, edit it, or add it directly to your content calendar.

---

## Using LM Studio (Local AI)

LM Studio allows you to run AI models entirely on your own computer — no API key, no internet connection required after the model is downloaded. This is ideal for organizations with strict data privacy requirements.

**Requirements:**
- [LM Studio](https://lmstudio.ai) installed (free, available for Mac, Windows, Linux)
- At least one model downloaded inside LM Studio
- 8GB RAM minimum; 16GB+ recommended for larger models

**Setup:**

1. Open LM Studio and navigate to the **Developer** tab
2. Click **Start Server** — the server runs at `http://localhost:1234` by default
3. Load a model using the model selector at the top of the Developer tab
4. In PostCraft, click **⚙ API Keys**
5. Confirm the Server URL (`http://localhost:1234`) and click **↻ Fetch**
6. Select your loaded model from the dropdown and click **✓ Save Keys**
7. Click the **LM Studio** provider card to activate it

**Recommended models for social media writing:**
- `mistral-7b-instruct` — fast, great for short-form content
- `llama-3-8b-instruct` — well-rounded for all platform styles
- `phi-3-medium-instruct` — efficient, strong tone adaptation

---

## Content Calendar & CSV Export

PostCraft includes a lightweight content calendar to help you plan posts in advance.

**To schedule a post:**
1. Generate a post you're happy with
2. Set a **Publish Date** and **Publish Time** in the Schedule section
3. Click **+ Add to Content Calendar**

Your scheduled posts appear in the calendar table, showing the AI provider used, platform, post preview, date, time, and the 5 W's context.

**To export:**
Click **↓ Export CSV** to download your full calendar as a `.csv` file compatible with Excel, Google Sheets, Airtable, or any scheduling tool that accepts CSV imports.

> ⚠️ The content calendar is stored in your browser's local storage. Clearing your browser data will clear the calendar. Export regularly to keep a permanent record.

---

## Privacy & Data Policy

PostCraft is built with privacy as a first principle.

- ✅ **No account required** — there is no PostCraft account, login, or registration
- ✅ **No data collection** — PostCraft does not collect, store, or transmit any of your content
- ✅ **No analytics** — no tracking pixels, no usage logging, no third-party scripts
- ✅ **API keys stay local** — keys are stored only in your browser's local storage and sent only directly to the AI provider you select
- ✅ **No server** — PostCraft is a static HTML file; there is no backend
- ✅ **LM Studio option** — for complete air-gap privacy, use LM Studio so content never leaves your device

The only external network requests PostCraft makes are the API calls you initiate when you click **Generate Post**, sent directly to your chosen AI provider.

---

## FAQ

**Do I need to pay to use PostCraft?**
PostCraft itself is completely free. You will pay only for the AI API calls you make — and only if you exceed the free tier of your chosen provider. Google Gemini offers a generous free tier. LM Studio is entirely free.

**Can I use PostCraft offline?**
Yes, if you use LM Studio as your AI provider. The PostCraft HTML file itself works offline — only the AI generation requires a connection (unless using LM Studio locally).

**Is my content safe?**
Your content is sent only to the AI provider you select — the same privacy terms apply as if you used that provider's own app. PostCraft itself never sees or stores your content.

**Can multiple team members use PostCraft?**
Yes — share the `postcraft.html` file with your team. Each person opens it independently in their own browser. The content calendar and API keys are stored per-browser, so each user maintains their own settings.

**What browsers are supported?**
Chrome, Firefox, and Edge are fully supported. Safari works but may have minor styling differences. Internet Explorer is not supported.

**Can I host PostCraft on my website?**
Yes. Since it's a single HTML file, you can upload it to any web server or host it on GitHub Pages, Netlify, or any static hosting service.

**The AI generated a post that's too short. What do I do?**
Make sure you've filled in as many of the 5 W's as possible — the more context you provide, the richer and longer the output. You can also click **✎ Edit** to expand the post manually before scheduling it.

---

## Contributing

PostCraft is open to contributions. If you'd like to suggest a feature, report a bug, or submit improvements:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add: description of change'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request with a clear description of what you changed and why

**Areas where contributions are especially welcome:**
- Additional platform support (Pinterest, Bluesky, Mastodon)
- Translations / internationalization
- Accessibility improvements
- Additional tone/style presets
- Integration guides for popular scheduling tools

---

## License

PostCraft is released as a free tool for nonprofit organizations and small businesses. You are free to use, share, and modify it for non-commercial purposes. Attribution is appreciated but not required.

---

<div align="center">

**Built with ♥ for the organizations that make communities stronger.**

*PostCraft — because your story deserves to be told.*

</div>
