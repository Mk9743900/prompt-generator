# Prompt Generator
> Build production-ready AI prompts from scratch — or fix broken ones instantly.

![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-brightgreen) ![Free](https://img.shields.io/badge/Cost-Free-blue) ![Powered by Gemini](https://img.shields.io/badge/Powered%20by-Gemini%202.5-orange)

🌐 **Live Site:** [https://Mk9743900.github.io/prompt-generator](https://Mk9743900.github.io/prompt-generator)

---

## What is this?

Most people write bad prompts and get bad results from AI. This tool fixes that.

It has two modes:

- **Builder mode** — Fill in your task, role, audience, tone, and format. Get a structured, production-ready prompt instantly.
- **Fixer mode** — Paste any bad prompt. Get a score out of 10, a list of specific issues, and a fully rewritten version.

---

## Sample Output

**Input prompt (bad):**
> *"tell me about data"*

**After Fixer mode:**
```
You are a Senior Data Analyst. Given the following dataset [INSERT DATA],
explain the key trends, anomalies, and insights to a non-technical
business stakeholder. Format your response as:
1. Summary (2-3 lines)
2. Key Findings (bullet points)
3. Recommended Action
Keep it under 300 words.
```
**Score:** 1/10 → 9/10

---

**Input prompt (complex business use case):**
> *"Act as a Lead Business Analyst. Write a prompt to identify why a subscription-based SaaS product saw a 15% increase in churn last quarter..."*

**Generated output includes:**
- Cohort definition by acquisition quarter & feature engagement
- Behavioral analysis — login frequency, session duration, ghost features
- Hypothesis generation linked to behavioral patterns
- Prioritized actionable recommendations with anticipated impact

---

## Features

- **Two modes** — Build from scratch or fix existing prompts
- **Tone selector** — Professional, Direct, Friendly, Technical, Casual
- **Format selector** — Bullets, Steps, Prose, Table, Structured sections
- **Instant scoring** — Fixer mode scores your prompt 1-10 with specific issues
- **One-click copy** — Copy generated prompts instantly
- **Dark mode** — Automatically follows your system preference
- **Fully responsive** — Works on mobile and desktop

---

## How to Use

1. Open the [live site](https://Mk9743900.github.io/prompt-generator)
2. Paste your **Gemini API key** in the key box → click **Save key**
   - Get a free key at [aistudio.google.com](https://aistudio.google.com)
   - Key is stored in memory only — never saved or sent anywhere
3. Choose **Builder** or **Fixer** mode
4. Fill in details or paste your prompt → hit generate

---

## Tech Stack

| What | How |
|---|---|
| Frontend | Pure HTML, CSS, JavaScript — zero dependencies |
| AI Model | Google Gemini 2.5 Flash API |
| Hosting | GitHub Pages (free) |
| Build tools | None — single file, ships as-is |

---

## Why I built this

As a Data Analyst upskilling into Data Science, I found that most people — including myself — write vague, structureless prompts and wonder why AI gives generic answers.

The quality of your output is directly tied to the quality of your prompt. This tool makes prompt engineering accessible to anyone.

---

## Local Setup

No installation needed. Just clone and open:

```bash
git clone https://github.com/Mk9743900/prompt-generator.git
cd prompt-generator
open index.html
```

Add your Gemini API key when prompted in the browser.

---

## What I Learned Building This

- Prompt engineering principles — role, context, format, constraints
- Gemini API integration — REST calls, JSON parsing, error handling
- GitHub Pages deployment — git workflow, static hosting
- API key security — never hardcode keys in public repos
- Debugging API errors — model names, token limits, rate limits

---

## Roadmap

- [ ] Save prompt history locally
- [ ] Export prompts as PDF
- [ ] Add more AI model options
- [ ] Backend proxy to hide API key for public use

---

## Author

**Mohammed** — Data Analyst → Data Scientist  
[GitHub](https://github.com/Mk9743900)

---

*Built with curiosity and zero budget.*
