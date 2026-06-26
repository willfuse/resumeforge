# ⚡ ResumeForge

> AI-powered resume tailoring — paste your resume + a job description, get a fully optimized resume, cover letter, and ATS ranking. Runs entirely in your browser.

**[→ Try it live](https://willfuse.github.io/resumeforge)**

---

## What it does

ResumeForge runs your resume through a 6-step AI optimization process powered by Claude:

| Step | What happens |
|------|-------------|
| 01 · ATS Keywords | Extracts and injects the exact keywords ATS scanners and recruiters look for |
| 02 · Bullet Rewrites | Rewrites every bullet: action verb + task + method + quantified result |
| 03 · Gap Analysis | Reframes your experience to cover skill gaps using transferable language |
| 04 · Pro Summary | 3–4 line summary that positions you as the obvious hire for this exact role |
| 05 · Cover Letter | Compelling, specific cover letter — not a generic template |
| 06 · Rank + Tips | Rates your resume vs. typical applicants and tells you exactly what to improve |

## How to use

1. Get a free Claude API key at [console.anthropic.com](https://console.anthropic.com)
2. Open `index.html` in any browser (or use the [live version](https://willfuse.github.io/resumeforge))
3. Paste your API key, current resume, and target job description
4. Toggle which steps to run
5. Hit **run forge**

Your API key and resume data **never leave your browser** — all requests go directly from your machine to the Anthropic API.

## Self-host / deploy

This is a single `index.html` file with zero dependencies. You can:

- Open it locally — just double-click
- Host on GitHub Pages (this repo does exactly that)
- Drop it on any static host (Netlify, Vercel, Cloudflare Pages)

## Stack

- Vanilla HTML/CSS/JS — no framework, no build step
- [Claude Sonnet](https://www.anthropic.com/claude) via the Anthropic API
- Direct browser → API calls (requires your own API key)

## License

MIT — fork it, remix it, ship it.
