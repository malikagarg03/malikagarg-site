# malikagarg.xyz

A personal website for building and experimenting with simple tools,
dashboards, and operational workflows.

------------------------------------------------------------------------

## 🧠 Core Idea

This site is used to rapidly prototype small, useful systems that
convert messy, real-world inputs into structured, easy-to-understand
views.

The focus is on: - simplicity - speed of development - real-world
usability

------------------------------------------------------------------------

## 🚀 Current Pages

### Homepage

Path: /

-   Personal landing page
-   Section order: About → Tools → Writing
-   Projects and Quick Links sections are commented out in the HTML (not deleted) — currently not relevant

------------------------------------------------------------------------

### Digital Garden

URL: https://my-digital-garden-taupe-xi.vercel.app

-   Personal notes and knowledge base published from Obsidian
-   Hosted separately on Vercel (not part of this repo)
-   Linked from the homepage as a project card

------------------------------------------------------------------------

### RTGS Diesel Dashboard 1

URL: https://rtgs-deisel-dashboard.netlify.app

-   Main petrol pump dry-out tracking dashboard for Andhra Pradesh
-   Hosted separately on Netlify (not part of this repo)

------------------------------------------------------------------------

### RTGS Diesel Dashboard 2

Path: /rtgs-diesel-dashboard/

-   Static dashboard prototype with snapshot timeline
-   District breakdown by OMC (IOCL, HPCL, BPCL)

------------------------------------------------------------------------

### AI as Your Thinking Partner

Path: /prompt-library/ai-thinking-partner.html

-   Facilitated workshop tool (MCTP-IV) for officers developing a funding proposal
-   Passcode-gated stages guide a continuing AI conversation: frame the problem, broaden options, challenge the thinking, AI-led interview, stress-test it
-   Saves proposal and takeaways to localStorage and downloads them as HTML files

------------------------------------------------------------------------

### Incident Response Prompt Generator

Path: /prompt-library/incident-response.html

-   Tool for police officers handling a live incident
-   Structures thinking in 60 seconds and generates an AI prompt
-   Prompt can be sent to ChatGPT, Claude, Gemini, or Perplexity

------------------------------------------------------------------------

### Read With AI

Path: /prompt-library/read-with-ai.html

-   Tool for officers learning their posting's local language
-   Takes one pasted article and builds a five-step sequence of AI prompts: context, vocabulary quiz, sentence-by-sentence read, and the issue behind it
-   Includes a bonus menu of standalone prompts for vocabulary, writing, roleplay, and comprehension practice

------------------------------------------------------------------------

### Learn Better with AI

Path: /prompt-library/learn-better-with-ai.html

-   Facilitated workshop tool for an NPA (National Police Academy) Phase 1 session
-   Five passcode-gated prompts (given live by the facilitator) turn a specific lecture into a retrieval, clarification, and simulation exercise, plus a master prompt to run the same method on any future lecture
-   Includes a PPT download for the session's example lecture and an embedded Google Form exit ticket
-   Progress saved to localStorage so unlocked stages persist on refresh
-   Links out to the Build My AI Learning Partner tool for anyone doing an online course

------------------------------------------------------------------------

### Build My AI Learning Partner

Path: /prompt-library/ai-learning-partner.html

-   Tool for anyone taking an online course, built with IPS probationers in mind
-   Guided form captures who the learner is, the course, their purpose, prior knowledge, interests, and where they want to apply it
-   Assembles one reusable AI instruction — for a ChatGPT/Claude Project or custom instructions — that turns lecture transcripts, slides, or readings into a personalised learning conversation, plus two follow-up prompts for starting each new lecture
-   Entirely client-side; form contents are never stored or transmitted

------------------------------------------------------------------------

### Google Sheet Experiment

Path: /google-sheet-experiment/

-   Interactive data entry + live display
-   Used to test input → display workflows
-   Not linked from homepage (accessible directly by URL)

------------------------------------------------------------------------

### Substack

URL: https://substack.com/@malikagarg03/posts

-   Essays and posts
-   Hosted on Substack, linked from the homepage Writing section

------------------------------------------------------------------------

## 🧩 Common Pattern

Input → Data → Processing → Display

-   Input can be manual entry, file upload, or external data
-   Data is structured into a usable format
-   Processing includes filtering, summarising, or highlighting
-   Display presents information clearly for quick understanding

------------------------------------------------------------------------

## 🎯 Purpose of the Project

-   Rapid prototyping of operational tools\
-   Converting scattered inputs into structured views\
-   Building reusable components

------------------------------------------------------------------------

## ⚠️ Important Notes

-   Static site (GitHub Pages)
-   No backend
-   Not for sensitive data
-   Focus on experimentation
-   GA4 analytics active on all pages (Measurement ID stored in `.analytics`, gitignored)

------------------------------------------------------------------------

## 🔧 How to Extend

Create folder → add index.html → build logic → update README

------------------------------------------------------------------------

## 🧠 Philosophy

Keep things: - simple\
- fast\
- useful

Avoid overengineering.

------------------------------------------------------------------------

## 🔄 Workflow

Idea → Prototype → Use → Improve → Reuse

------------------------------------------------------------------------

## 📌 Future Direction

-   File upload and parsing\
-   Map-based visualisation\
-   Alert systems\
-   Multi-source dashboards

------------------------------------------------------------------------

## 🧠 Key Principle

This is not just a website --- it is a tool-building environment.
