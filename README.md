# BioSearch AI — Research Paper Search Engine

> AI-powered research discovery tool for Biotech and Pharma professionals.



![Status](https://img.shields.io/badge/Status-Complete-brightgreen)



---

## The Problem

Biotech and Pharma researchers spend hours manually searching PubMed, reading abstracts, and trying to extract key findings from dozens of papers. Staying updated with latest research is a full-time job in itself.

Most professionals don't have time to read 20 papers to find 2 relevant ones.

---

## The Solution

BioSearch AI searches PubMed instantly and returns AI-generated summaries — so researchers get the key insights without reading full papers.

- Search in natural language — no complex PubMed syntax needed
- Get Title, Key Findings, Methodology per paper in seconds
- Direct PubMed links for papers worth reading in full
- Full report delivered to Gmail on demand

---

## Time & Effort Saved

| Task | Manual | BioSearch AI |
|---|---|---|
| Searching PubMed | 30-60 mins | 10 seconds |
| Reading abstracts | Hours | AI summary in seconds |
| Extracting key findings | Manual note-taking | Auto-generated |
| Getting email report | Not available | One click |

---

## Final Output

- ✅ Research paper cards — Title, Summary, Key Findings, Date, PubMed link
- ✅ AI-generated insights per paper
- ✅ Gmail HTML report with all results
- ✅ Search history saved for future reference

---

## What It Does

BioSearch AI searches PubMed and returns AI-generated summaries of research papers. Built for Biotech and Pharma professionals who need fast, intelligent access to latest research.

- **Smart search** — natural language queries via PubMed API
- **AI summaries** — Title, Abstract summary, Key Findings, Methodology per paper
- **Published date + PubMed links** — direct access to source
- **Search history** — past searches saved and accessible
- **Gmail delivery** — results sent to email on demand
- **General chat** — ask follow-up questions about any biotech topic

---

## Frontend (Lovable)

- Clean navy + gold UI built on Lovable
- Search bar for quick queries
- Results displayed as cards — Title, Summary, Key Findings, Date, PubMed link
- Search History panel on sidebar
- AI chat interface for follow-up questions
- Fully responsive web application

---

## Tech Stack

| Layer | Tool |
|---|---|
| Frontend | Lovable (navy + gold UI) |
| Automation | n8n webhook workflow |
| LLM | Gemini 2.5 Flash |
| Research API | PubMed API |
| Email | Gmail HTML |

---

## Architecture

```
User enters search query (Lovable frontend)
        ↓
n8n Webhook receives query
        ↓
PubMed API fetches matching papers
        ↓
Gemini 2.5 Flash generates summaries
        ↓
Results returned to frontend as cards
        ↓
Gmail sends report on request
```

---

## Technical Notes

- Gemini Chat Model used for tool calling support
- PubMed API fetches paper metadata + abstracts
- AI Agent processes and summarizes each result
- Webhook connects Lovable frontend to n8n backend

---

*Built by Deman Meshram | BSc Biotechnology + AI Automation*
