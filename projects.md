# DevDay Bengaluru Hackathon — Ranked App Catalog & Technical Review

**10 October 2026 · Bengaluru · 150 attendees · 45 reported submissions**

> **Source of ranking:** Participant-supplied ordering of 40 positions.The public [build board](https://devday-bengaluru-build-board.hello429616.chatgpt.site/) shows an announcement heading but did not expose its dynamic individual project records in the accessible response. Project descriptions below are based on publicly readable project repositories and/or live pages, researched on **11 October 2026**. Tech-stack statements distinguish documented components from undisclosed ones.

## Overview

| Metric | Count / interpretation |
|---|---|
| Attendees | **~150** (participant-reported) |
| Submitted applications | **45** (participant-reported; project records not independently counted) |
| Ranked positions supplied | **40** |
| Duplicate positions | **2**: ranks **16–17** refer to Roody AI; **29–30** refer to px0-flow |
| **Distinct applications in supplied list** | **38** |
| Remaining distinct submissions to identify, assuming 45 unique submissions | **7** (not 5: two duplicate ranked rows) |
| Submission-to-attendee ratio | **30 submissions per 100 attendees**, not an attendee-participation rate |
| App-level evidence | **31 distinct GitHub repositories** plus **7 site-only apps** |
| Event/build board | [Community hackathon build board](https://devday-bengaluru-build-board.hello429616.chatgpt.site/) |

### How to read this catalog

- **Rank** reproduces the supplied sequence, not a verified official prize placement. The numbers should be called “reported order” until the organizer confirms them.
- **Core message** describes the product’s promise or user pain; **workflow** describes how the proposed app addresses it.
- **Tech stack** contains reported/observed technologies from the linked repositories or sites as inspected, **not a claim that every dependency was exercised in the live demo**.
- **Repository-backed** means a public repo and README support the description. **Site-limited** means the linked live page exposed only part of the behavior. Model/stack fields absent from sources are explicitly unverified.
- **Projects can have been developed before or extended after 10 October.** The source reflects its state when accessed on 11 October and is not automatically a frozen event submission snapshot.

## Event context and judging framework

| Item | Published or participant-reported details |
|---|---|
| Community event | DevDay Exchange Community Meetup & Hackathon, Bengaluru — unofficial and separate from the official DevDay Exchange |
| When | **Saturday, 10 October 2026**, **10:00 AM–2:30 PM IST** |
| Where | **Polaris School of Technology, Bengaluru** |
| Reported turnout | Approximately **150 attendees** and **45 submitted apps** |
| Organizers / listed hosts | Tushar Mehta, Kushal Vijay, Rhiannon Payne, Pauline P. Narvas, Polaris School of Technology and Mayank Raj (as listed on the [Luma event page](https://luma.com/0bdmf0sw)) |
| Published judging ideas | **Usefulness, technical execution, originality and functionality** |
| Prize pool announced | **10 tickets** to the official Bengaluru DevDay Exchange (16 October 2026); recipients and exact official positions not independently verified here |

**Reading the ranking:** the provided order is a valuable participant record, but should not be presented as an independently confirmed official scorecard. This matters especially at positions 16/17 and 29/30, where the same repository URL appears twice. The final event-wide total and rank list need reconciliation against the organizer's actual submission export.

---

## 1. All supplied apps — ranking-order master table

| Reported position | Application | Core message (why this app exists) | Documented technology stack / integrations | Source |
|---:|---|---|---|---|
| **1** | **DawaiDost** | Catch medicine shortages at rural clinics before patients reach empty shelves. | Next.js 16, React 19, TypeScript, MapLibre GL, D3, OpenAI SDK, Vitest. OpenAI Decisions, Realtime, Responses, transcription and TTS APIs. | [Repo](https://github.com/RahilKothari9/DawaiDost) · [Demo](https://dawai-dost-lilac.vercel.app) |
| **2** | **RaktSetu** | Find and route available blood stock to urgent medical requests, with an officer retaining final control. | Python, FastAPI/API routes, OpenAI Decisions API, typed policy rules, pytest, Vercel/static officer console, e-RaktKosh stock integration. | [Repo](https://github.com/SayedZahur786/RaktSetu) · [Demo](https://raktsetu-beta.vercel.app) |
| **3** | **Sarthi** | Log the small facts of daily life in ChatGPT without silently treating an AI estimate as a fact. | Next.js, TypeScript, React, Drizzle ORM, ChatGPT plugin using MCP Apps, OpenAI Decisions API, account-scoped persistence, Vercel. | [Repo](https://github.com/SawhneySatvik/Sarthi/tree/hack/devday-chatgpt) · [Demo](https://sarthi-gray.vercel.app/mcp/info) |
| **4** | **Architect** | Make software understandable by tracing source-backed feature flows and architecture, not merely generating code. | Next.js, TypeScript, React Flow, Python/FastAPI, Tree-sitter, optional OpenAI structured outputs, Supabase PostgreSQL + Storage, Vercel. | [Repo](https://github.com/Harshakoliki/Architect) · [Demo](https://productarchitect.vercel.app) |
| **5** | **BoloRider** | Give delivery riders a multilingual, low-touch voice companion for everyday tasks. | Web app with client-side audio UI, OpenAI Responses API (gpt-4.1-mini vision), OpenAI Realtime voice, browser audio/WebRTC, server API routes, deployed… | [Repo](https://github.com/shhhivam12/bolorider) · [Demo](https://bolo-rider.shiiim.chatgpt.site) |
| **6** | **ScamSense** | Train people to recognize SMS scams through an interactive contest against an AI judgment. | Next.js, JavaScript/TypeScript web app, Vercel server/backend, OpenAI Decisions API, scripted case bank and automated tests. | [Repo](https://github.com/therahulgoel/scamsense) · [Demo](https://scamsense-lemon.vercel.app) |
| **7** | **Ghost Hands** | Teach desktop tasks by demonstrating the actual clicks, narrating them, then coaching users to repeat them. | Python, PyQt6 Windows overlay, Windows UI Automation, screenshot capture, OpenAI Responses computer-use (GPT-6.1 Sol), OpenAI STT/TTS, queues and local step… | [Repo](https://github.com/Arham-Begani/ghost-hands) · [Demo](https://ghost-hands-six.vercel.app) |
| **8** | **DemoPilot** | Turn an imperfect project brief into a timed, evidence-conscious demonstration. | Vite, React, TypeScript, Node/Express for development, Vercel Functions, OpenAI Decisions API, deterministic demo fallback. | [Repo](https://github.com/Yash-1706/openai-dev-day-polaris) · [Demo](https://openai-dev-day-polaris.vercel.app) |
| **9** | **AMU** | Give coding agents dependency and impact evidence before they edit unfamiliar code. | Python CLI and MCP inspection layer, Entire graph provider, source relationship evidence, tests, web companion artifacts. | [Repo](https://github.com/abslock128w/AMU) |
| **10** | **antislop** | Make AI-written changes defensible through reproducible evidence, not a vague “looks good” verdict. | Python 3.11+, FastAPI, Docker runner/worker, Z3, SQLite queue, JavaScript frontend, pytest, GitHub integration. | [Repo](https://github.com/nomercy77/antislop) · [Demo](https://antislop.bee3.in) |
| **11** | **The Gauntlet** | Present an arena for ideas; encourage concept comparison and challenge-based exploration. | Web application on Vercel. Framework, backend, model APIs, and database not disclosed in the accessible page. | [Site](https://the-gauntlet-ten-sable.vercel.app) |
| **12** | **OSS Mentor** | Help first-time contributors choose a genuinely available issue and understand their code before opening a PR. | No-build React frontend, Python/FastAPI, GitHub REST API, OpenAI Responses API, source-grounded agent tools, deterministic suitability scoring. | [Repo](https://github.com/Karan-Raj-KR/OSS-Mentor) · [Demo](https://oss-mentor-seven.vercel.app) |
| **13** | **MazikDLP** | Stop sensitive enterprise content from leaving the browser inside prompts to public AI tools. | Chrome Manifest V3 extension, React dashboard, Python/FastAPI, PostgreSQL, Redis, Docker, Presidio/spaCy detection, OCR/image-redaction support. | [Repo](https://github.com/CyberZik/MazikDLP) |
| **14** | **Shopping Assistant** | Translate a shopping brief into an evidence-based, inspectable shortlist with hard budgets and soft preferences. | Python 3.11+, MCP server/CLI, OpenAI Decisions API, ChatGPT plugin, local demo catalog, test harness. | [Repo](https://github.com/NavtejReddy/shopping_assistant) |
| **15** | **BuildScout / Hackathon Scout** | Spend less time searching for hackathons and more time selecting a realistic project to build. | Web app hosted on Vercel plus linked ChatGPT Site. Specific frontend/backend, crawl/schedule services, and AI model not disclosed. | [Site](https://laksh-hackathon-scout.vercel.app) |
| **16** | **Roody AI Companion** | Provide a voice-first floating companion that understands the page and code visible while someone works. | Chrome extension (Manifest JSON, JavaScript), OpenAI Realtime voice, browser capture/page APIs, Node/server components, Vercel demo. | [Repo](https://github.com/F1VISABYARUN/Roody-ai) · [Demo](https://roodyaicompanion.vercel.app) |
| **17** | **Roody AI Companion — duplicate listing** | Same application as rank #16, not a separately verified submission. | Same stack as rank #16: Chrome extension, JavaScript, OpenAI Realtime, server routes, Vercel. | [Repo](https://github.com/F1VISABYARUN/Roody-ai) · [Demo](https://roodyaicompanion.vercel.app) |
| **18** | **VideoMem** | Index video once and answer repeated questions without repeatedly sending video frames to a vision model. | Python, OpenCV, OpenAI Responses API (gpt-4.1-mini vision), JSON/hash-map indexes, Streamlit, evaluation script. | [Repo](https://github.com/kunal3108/videomem) |
| **19** | **Dsider** | Help parents turn a child’s robotics/build idea into an affordable, checkable purchase-and-action plan. | Hosted ChatGPT Site, site describes research plus OpenAI Decisions evaluation. Specific code framework and backend implementation not publicly disclosed. | [Site](https://dsider.circuitheroes.chatgpt.site) |
| **20** | **YouFeedLens** | Keep YouTube recommendations aligned to a learner’s chosen domain instead of distracting them with unrelated cards. | Chrome extension (JavaScript Manifest), Node.js backend, OpenAI Decisions API, Docker/Fly.io configuration, Vercel marketing site. | [Repo](https://github.com/im-gozmit/youfeedlens) · [Demo](https://youfeedlens.vercel.app) |
| **21** | **Speech-Machine** | Give speakers actionable feedback on pace, filler words, eye contact and delivery from recorded or uploaded practice sessions. | Next.js 14, React 18, TypeScript, Tailwind, Zustand, Recharts, MediaPipe, FastAPI, SQLAlchemy, PostgreSQL, Redis/arq, faster-whisper, Docker, optional MLX… | [Repo](https://github.com/SSusantAchary/speech-machine) |
| **22** | **ROYAL’S AI BusinessOS** | Give Indian MSMEs one place for invoices, stock, CRM, expenses and practical operational summaries. | Next.js, TypeScript, Prisma, SQLite local database, bcrypt sessions, Vitest, Node, adapters for future external providers. | [Repo](https://github.com/faruk00095/royals-ai-businessos) |
| **23** | **Octillion** | Expose product, customer and agent trace evidence to assistants through read-only MCP tools and a visual dashboard. | TypeScript/Node, MCP Apps/MCP-UI, PostgreSQL/PGlite, optional S3, ClickHouse and Langfuse, Docker Compose, end-to-end smoke tests. | [Repo](https://github.com/SoumilB7/Octillion) |
| **24** | **Quartermaster (OFC Decision)** | Regression-test Oracle Fusion Cloud changes before quarterly updates hit production, and package audit evidence. | Python 3.11+, Playwright, pytest, local `qm` service/CLI, OpenAI Decisions API optional judgment, Word report export. | [Repo](https://github.com/0x-Shashi/OFC_Decission) |
| **25** | **Mintaro — Milestone Escrow** | Reduce freelancer–client payment disputes with milestone-based escrow rather than all-or-nothing transfers. | Solidity smart contracts, Hardhat, JavaScript, web frontend, Avalanche Fuji testnet, AVAX/ERC-20 transfers. | [Repo](https://github.com/mohammedsafwankhan/trustless-escrows) |
| **26** | **The Understudy** | Teach a browser task once, turn it into an editable skill, and repeat it with visible human control. | Vite, TypeScript, frontend src/, Node server routes, browser automation agent architecture (specific driver requires code-level verification). | [Repo](https://github.com/tanisha-kiran/understudy) |
| **27** | **Handbrake** | Let AI agents automate the routine browser clicks while pausing on risky actions such as payment, sending and deleting. | Node.js/JavaScript, MCP, Playwright Chromium, OpenAI Decisions API, GPT-6.1 Sol computer-use, Codex/Claude Code compatibility, Vercel demonstration. | [Repo](https://github.com/aashish00021/handbrake) · [Demo](https://handbrake-eosin.vercel.app) |
| **28** | **Guardian GPT** | Interrupt UPI and “digital arrest” scams before a risky transfer, with a trusted-person approval path. | JavaScript/Node, OpenAI Decisions API, GPT-6.1 Sol, MCP/ChatGPT plugin surface, Agents API, Dots-oriented design, demonstration web UI. | [Repo](https://github.com/Drix10/guardian-gpt) |
| **29** | **px0-flow** | Show how a code change travels from a user-facing screen through APIs, services and database effects. | Go CLI/TUI and source-navigation engine, Git/LSP, graph visualization, web assets, Go tests. | [Repo](https://github.com/valpetaltechlabs/px0-Flow) |
| **30** | **px0-flow — duplicate listing** | Same project as rank #29, not a separately verified submission. | Same Go CLI/TUI, Git/LSP, graph and tests as rank #29. | [Repo](https://github.com/valpetaltechlabs/px0-Flow) |
| **31** | **Agent Black Box** | Make AI agents propose actions, but enforce permissions with deterministic rules and a complete audit trail. | Python, Streamlit, SQLite, MCP server, OpenAI Responses/GPT-6.1 Sol, optional Decisions API, policy engine, synthetic fixtures. | [Repo](https://github.com/pagadalagopihemanth/agent-black-box) |
| **32** | **Neighbourhood Finds** | Find interesting local places using neighborhood-aware categories, community picks and conversational search. | Web app hosted as ChatGPT Site, map/list search UI and curated place data. Exact application framework, AI provider and backend unverified. | [Site](https://neighbourhood-finds.reshma-nurix.chatgpt.site/?scope=all) |
| **33** | **Proposal Engine** | Convert a client brief into a proposal whose price and schedule can be traced to past delivery hours. | JavaScript/Node, Netlify Functions, ChatGPT Apps SDK / MCP, OpenAI Responses API and embeddings optional, deterministic TF-IDF/rules fallback. | [Repo](https://github.com/sanket-fls/proposal) |
| **34** | **Spec2Proof** | Turn a business requirement into executable acceptance tests and a reviewed, reproducible fix. | Python 3.10+ standard library, unittest, local HTTP server, MCP Apps / ChatGPT plugin, HTML/JavaScript workbench, no model API required for core demo. | [Repo](https://github.com/bismillahkani/spec2proof) |
| **35** | **Spring Winter** | Not enough accessible public information to establish the application’s core message accurately. | Tech stack not independently verifiable from supplied domain. | [Site](https://springwinter.dev) |
| **36** | **Pickture** | Replace endless movie browsing with one choice suited to your mood and existing subscriptions. | Web app, TMDB API, OMDb API, browser-local choice/history. Framework and model provider not disclosed. | [Site](https://pickture.fun/#/welcome) |
| **37** | **Better Wardrobe** | Put fashion inspiration, similar items and one’s own wardrobe into a coherent discovery workspace. | Web prototype with app source in GitHub, OpenAI optional Decisions API path (off by default), hosted Vercel/ChatGPT Sites previews. Exact runtime… | [Repo](https://github.com/ChoudharyAyan/Better-Wardrobe-ChatGPT-Hackathon) · [Demo](https://better-wardrobe-hackathon.vercel.app) |
| **38** | **Ozark AML Agent Demo** | Help an analyst investigate suspicious transactions using evidence, deterministic risk scoring and supervised AI drafting. | Python 3.11+, Streamlit, MCP HTTP server, deterministic rules, optional external LLM prose via configurable Astra-compatible endpoint. | [Repo](https://github.com/vinpuj/ozark-aml-agent-demo) · [Demo](https://c98seejruejgf9nkgekpj5.streamlit.app/) |
| **39** | **PlotTwist** | Make entertainment and skill practice interactive by letting each choice redirect the story. | React, TypeScript, Vite, Node server, Netlify Functions, OpenAI Decisions/Responses, STT, Images and optional Realtime, localStorage/IndexedDB, Vitest. | [Repo](https://github.com/futurelabstudios/plottwist) · [Demo](https://plottwistbyfuturelab.netlify.app) |
| **40** | **Agent Arcade** | Make a lighthearted browser arcade where players choose a model-themed fighter and play games. | Browser game hosted at agentarcade.fun, browser-local saved player profile. Specific JS framework, backend and AI API usage not verifiable. | [Site](https://agentarcade.fun) |

**Deduplication:** #17 is the same repository and application as #16; #30 is the same repository and application as #29. They have separate numbered rows **only** to preserve the provided ordering. Neither is treated as a second distinct project when counting categories or repository totals.

## 2. Detailed app profiles in supplied rank order

### 01. DawaiDost

**Category:** Healthcare / public supply  
**Core message:** Catch medicine shortages at rural clinics before patients reach empty shelves.

**How it works:** Hindi-speaking pharmacists report shelf counts; deterministic stock forecasts identify risk and safe donors; an OpenAI decision recommendation is reviewed by a district health officer.

**Tech stack / AI features:** Next.js 16; React 19; TypeScript; MapLibre GL; D3; OpenAI SDK; Vitest. OpenAI Decisions, Realtime, Responses, transcription and TTS APIs.

**Links:** [Source repository](https://github.com/RahilKothari9/DawaiDost) · [Live app / demo](https://dawai-dost-lilac.vercel.app)

**Evidence and limits:** README details a 50-case synthetic Decisions evaluation and human approval. Figures are team-reported, not independently reproduced. **Verification:** repository-backed.

### 02. RaktSetu

**Category:** Healthcare / emergency coordination  
**Core message:** Find and route available blood stock to urgent medical requests, with an officer retaining final control.

**How it works:** Consult e-RaktKosh blood availability; score supply/distance/compatibility context; recommend, hold, block, or declare no stock; officer confirms requests.

**Tech stack / AI features:** Python; FastAPI/API routes; OpenAI Decisions API; typed policy rules; pytest; Vercel/static officer console; e-RaktKosh stock integration.

**Links:** [Source repository](https://github.com/SayedZahur786/RaktSetu) · [Live app / demo](https://raktsetu-beta.vercel.app)

**Evidence and limits:** Uses synthetic requests and real stock lookups per README; no actual blood dispatched automatically. **Verification:** repository-backed.

### 03. Sarthi

**Category:** Personal life / ChatGPT plugin  
**Core message:** Log the small facts of daily life in ChatGPT without silently treating an AI estimate as a fact.

**How it works:** Conversational capture of spending, habits, nutrition, skills and todos; direct statements log, model-inferred values become confirmable cards; users can undo changes.

**Tech stack / AI features:** Next.js; TypeScript; React; Drizzle ORM; ChatGPT plugin using MCP Apps; OpenAI Decisions API; account-scoped persistence; Vercel.

**Links:** [Source repository](https://github.com/SawhneySatvik/Sarthi/tree/hack/devday-chatgpt) · [Live app / demo](https://sarthi-gray.vercel.app/mcp/info)

**Evidence and limits:** The specified GitHub branch was not rendered reliably; plugin behavior independently supported by the live /mcp/info page and root repository. **Verification:** repository + published plugin page.

### 04. Architect

**Category:** Developer understanding / code visualization  
**Core message:** Make software understandable by tracing source-backed feature flows and architecture, not merely generating code.

**How it works:** Scan source archives, detect relationships and routes, draw evidence-linked component/feature graphs, interrogate flow boundaries and optionally create an AI explanation with consent.

**Tech stack / AI features:** Next.js; TypeScript; React Flow; Python/FastAPI; Tree-sitter; optional OpenAI structured outputs; Supabase PostgreSQL + Storage; Vercel.

**Links:** [Source repository](https://github.com/Harshakoliki/Architect) · [Live app / demo](https://productarchitect.vercel.app)

**Evidence and limits:** Scanning can run without OpenAI; claims about faster onboarding are hypotheses, not measured impact. **Verification:** repository-backed.

### 05. BoloRider

**Category:** Gig workers / accessibility  
**Core message:** Give delivery riders a multilingual, low-touch voice companion for everyday tasks.

**How it works:** Read a ride screenshot into confirmed order fields, answer ride and earnings questions in Hindi/English/Kannada, help find fuel/contact customers, and support SOS workflows.

**Tech stack / AI features:** Web app with client-side audio UI; OpenAI Responses API (gpt-4.1-mini vision); OpenAI Realtime voice; browser audio/WebRTC; server API routes; deployed ChatGPT Site.

**Links:** [Source repository](https://github.com/shhhivam12/bolorider) · [Live app / demo](https://bolo-rider.shiiim.chatgpt.site)

**Evidence and limits:** The product is meant to reduce phone handling, not prove safe riding while operating a vehicle; user review is required for screenshot extraction. **Verification:** repository-backed.

### 06. ScamSense

**Category:** Fraud literacy / education  
**Core message:** Train people to recognize SMS scams through an interactive contest against an AI judgment.

**How it works:** Present five fictional Indian SMS scenarios, ask the player to classify each message, compare with a real Decisions API response, reveal clues and share a scorecard.

**Tech stack / AI features:** Next.js; JavaScript/TypeScript web app; Vercel server/backend; OpenAI Decisions API; scripted case bank and automated tests.

**Links:** [Source repository](https://github.com/therahulgoel/scamsense) · [Live app / demo](https://scamsense-lemon.vercel.app)

**Evidence and limits:** Educational game using fictional SMS; not a demonstrated production anti-fraud classifier. **Verification:** repository-backed.

### 07. Ghost Hands

**Category:** Desktop training / computer use  
**Core message:** Teach desktop tasks by demonstrating the actual clicks, narrating them, then coaching users to repeat them.

**How it works:** User requests a Windows action; GPT computer-use model proposes screen steps; guarded ghost cursor performs safe actions with narration; learner replays the steps.

**Tech stack / AI features:** Python; PyQt6 Windows overlay; Windows UI Automation; screenshot capture; OpenAI Responses computer-use (GPT-6.1 Sol); OpenAI STT/TTS; queues and local step logs.

**Links:** [Source repository](https://github.com/Arham-Begani/ghost-hands) · [Live app / demo](https://ghost-hands-six.vercel.app)

**Evidence and limits:** The board URL originally paired with rank #7 is the event-wide board, NOT this project demo. GitHub README supplies the actual project site. **Verification:** repository-backed.

### 08. DemoPilot

**Category:** Hackathon demos / presentations  
**Core message:** Turn an imperfect project brief into a timed, evidence-conscious demonstration.

**How it works:** Create a run-of-show, speaker script, visible proof points, limitation disclosures and rehearsal plan; optional Decisions API chooses demo focus.

**Tech stack / AI features:** Vite; React; TypeScript; Node/Express for development; Vercel Functions; OpenAI Decisions API; deterministic demo fallback.

**Links:** [Source repository](https://github.com/Yash-1706/openai-dev-day-polaris) · [Live app / demo](https://openai-dev-day-polaris.vercel.app)

**Evidence and limits:** Optimizes presentation planning, not product validation or automatic repository inspection. **Verification:** repository-backed.

### 09. AMU

**Category:** Developer tooling / code impact  
**Core message:** Give coding agents dependency and impact evidence before they edit unfamiliar code.

**How it works:** Local CLI/MCP retrieves source-backed relationships from an Entire graph, reports blast radius and evidence freshness, and helps plan test coverage.

**Tech stack / AI features:** Python CLI and MCP inspection layer; Entire graph provider; source relationship evidence; tests; web companion artifacts.

**Links:** [Source repository](https://github.com/abslock128w/AMU)

**Evidence and limits:** Provider graph coverage and freshness are surfaced; not every edge is necessarily known. **Verification:** repository-backed.

### 10. antislop

**Category:** Code verification / trust  
**Core message:** Make AI-written changes defensible through reproducible evidence, not a vague “looks good” verdict.

**How it works:** Pin immutable Git commit; run static checks, sandboxed tests, bounded contracts, restricted Z3 proof where supported; attach attestations and optional expert review.

**Tech stack / AI features:** Python 3.11+; FastAPI; Docker runner/worker; Z3; SQLite queue; JavaScript frontend; pytest; GitHub integration.

**Links:** [Source repository](https://github.com/nomercy77/antislop) · [Live app / demo](https://antislop.bee3.in)

**Evidence and limits:** Restricted proof scope. Payments, public deployment and GitHub grants are described as mock/configuration-dependent. **Verification:** repository-backed.

### 11. The Gauntlet

**Category:** Ideas / challenge arena  
**Core message:** Present an arena for ideas; encourage concept comparison and challenge-based exploration.

**How it works:** Public site is titled “The Gauntlet — An arena for ideas”; interactive journey and decision mechanics were not readable from available text.

**Tech stack / AI features:** Web application on Vercel. Framework, backend, model APIs, and database not disclosed in the accessible page.

**Links:** [Live app / demo](https://the-gauntlet-ten-sable.vercel.app)

**Evidence and limits:** Purpose inferred conservatively from site title; project details and stack not independently established. **Verification:** site-limited.

### 12. OSS Mentor

**Category:** Open source / developer education  
**Core message:** Help first-time contributors choose a genuinely available issue and understand their code before opening a PR.

**How it works:** Live-check issue assignment, competing PRs, claim comments and project AI rules; retrieve source context; coach hint-first; require an understanding checkpoint from the diff.

**Tech stack / AI features:** No-build React frontend; Python/FastAPI; GitHub REST API; OpenAI Responses API; source-grounded agent tools; deterministic suitability scoring.

**Links:** [Source repository](https://github.com/Karan-Raj-KR/OSS-Mentor) · [Live app / demo](https://oss-mentor-seven.vercel.app)

**Evidence and limits:** Builder credits are documented in project README; current prototype extends pre-existing work. **Verification:** repository-backed.

### 13. MazikDLP

**Category:** Security / AI data loss prevention  
**Core message:** Stop sensitive enterprise content from leaving the browser inside prompts to public AI tools.

**How it works:** Chrome extension intercepts prompts; detection and organization policy assess secrets, PII and India-specific identifiers; mask, block, warn, or audit.

**Tech stack / AI features:** Chrome Manifest V3 extension; React dashboard; Python/FastAPI; PostgreSQL; Redis; Docker; Presidio/spaCy detection; OCR/image-redaction support.

**Links:** [Source repository](https://github.com/CyberZik/MazikDLP)

**Evidence and limits:** Repository evaluation metrics are team-reported; compliance relevance is not a certification. **Verification:** repository-backed.

### 14. Shopping Assistant

**Category:** Commerce / shopping  
**Core message:** Translate a shopping brief into an evidence-based, inspectable shortlist with hard budgets and soft preferences.

**How it works:** ChatGPT/MCP interprets confirmed criteria; deterministic price checks enforce constraints; Decisions evaluates semantic matches; returns ranked links with unknown facts explicit.

**Tech stack / AI features:** Python 3.11+; MCP server/CLI; OpenAI Decisions API; ChatGPT plugin; local demo catalog; test harness.

**Links:** [Source repository](https://github.com/NavtejReddy/shopping_assistant)

**Evidence and limits:** Prototype supports specified/test catalogs; it is not proven across arbitrary retailers. **Verification:** repository-backed.

### 15. BuildScout / Hackathon Scout

**Category:** Developer opportunity discovery  
**Core message:** Spend less time searching for hackathons and more time selecting a realistic project to build.

**How it works:** Browse shortlists of hackathons for Bengaluru, Hyderabad or online; save opportunities and use a protected owner workspace for updating discoveries.

**Tech stack / AI features:** Web app hosted on Vercel plus linked ChatGPT Site. Specific frontend/backend, crawl/schedule services, and AI model not disclosed.

**Links:** [Live app / demo](https://laksh-hackathon-scout.vercel.app)

**Evidence and limits:** Site explicitly says scheduled source updates are not connected; current cards may require refresh or manual review. **Verification:** site-limited.

### 16. Roody AI Companion

**Category:** Browser productivity / voice  
**Core message:** Provide a voice-first floating companion that understands the page and code visible while someone works.

**How it works:** Chrome extension orb reads page and editor content, optional screenshots or screen sharing, gives spoken explanations and proactive context check-ins.

**Tech stack / AI features:** Chrome extension (Manifest JSON, JavaScript); OpenAI Realtime voice; browser capture/page APIs; Node/server components; Vercel demo.

**Links:** [Source repository](https://github.com/F1VISABYARUN/Roody-ai) · [Live app / demo](https://roodyaicompanion.vercel.app)

**Evidence and limits:** Duplicate project URL appears again at rank #17; count as one unique app. **Verification:** repository-backed.

### 17. Roody AI Companion — duplicate listing

**Category:** Duplicate / same project as #16  
**Core message:** Same application as rank #16, not a separately verified submission.

**How it works:** Same workflow as rank #16.

**Tech stack / AI features:** Same stack as rank #16: Chrome extension, JavaScript, OpenAI Realtime, server routes, Vercel.

**Links:** [Source repository](https://github.com/F1VISABYARUN/Roody-ai) · [Live app / demo](https://roodyaicompanion.vercel.app)

**Evidence and limits:** Intentional preservation of user-provided ranking position; duplicate is not an additional distinct app. **Verification:** duplicate listing.

### 18. VideoMem

**Category:** Video understanding / AI memory  
**Core message:** Index video once and answer repeated questions without repeatedly sending video frames to a vision model.

**How it works:** Sample frames every two seconds; extract timestamped visual observations; persist an indexed JSON memory; retrieve objects/events and synthesize timestamp-grounded answers.

**Tech stack / AI features:** Python; OpenCV; OpenAI Responses API (gpt-4.1-mini vision); JSON/hash-map indexes; Streamlit; evaluation script.

**Links:** [Source repository](https://github.com/kunal3108/videomem)

**Evidence and limits:** Claims of lower repeated-query vision usage follow its architecture; project benchmarks should be checked before asserting measured savings. **Verification:** repository-backed.

### 19. Dsider

**Category:** Education / parent-assisted making  
**Core message:** Help parents turn a child’s robotics/build idea into an affordable, checkable purchase-and-action plan.

**How it works:** Describe outcome, deadline, location and budget; research parts and workshops; check compatibility, price and schedule; choose online/local/hybrid purchase steps.

**Tech stack / AI features:** Hosted ChatGPT Site; site describes research plus OpenAI Decisions evaluation. Specific code framework and backend implementation not publicly disclosed.

**Links:** [Live app / demo](https://dsider.circuitheroes.chatgpt.site)

**Evidence and limits:** Component prices and vendor availability depend on current sources, not illustrative drone examples. **Verification:** site-limited.

### 20. YouFeedLens

**Category:** Attention / learning  
**Core message:** Keep YouTube recommendations aligned to a learner’s chosen domain instead of distracting them with unrelated cards.

**How it works:** Chrome extension extracts visible recommendation metadata, classifies topical relevance in bounded batches, blurs confidently off-topic videos, and leaves uncertain items alone.

**Tech stack / AI features:** Chrome extension (JavaScript Manifest); Node.js backend; OpenAI Decisions API; Docker/Fly.io configuration; Vercel marketing site.

**Links:** [Source repository](https://github.com/im-gozmit/youfeedlens) · [Live app / demo](https://youfeedlens.vercel.app)

**Evidence and limits:** A topic-relevance filter, not a misinformation or video-quality classifier. **Verification:** repository-backed.

### 21. Speech-Machine

**Category:** Communication coaching / speech analytics  
**Core message:** Give speakers actionable feedback on pace, filler words, eye contact and delivery from recorded or uploaded practice sessions.

**How it works:** Capture/upload video and reading text; transcribe; compute live and post-session delivery metrics; compare sessions and review transcript/coaching output.

**Tech stack / AI features:** Next.js 14; React 18; TypeScript; Tailwind; Zustand; Recharts; MediaPipe; FastAPI; SQLAlchemy; PostgreSQL; Redis/arq; faster-whisper; Docker; optional MLX Audio and local LLM.

**Links:** [Source repository](https://github.com/SSusantAchary/speech-machine)

**Evidence and limits:** Repository state was inspected after the event and may include capabilities not present in the exact 10 Oct demonstration. **Verification:** repository-backed.

### 22. ROYAL’S AI BusinessOS

**Category:** Small business / operations  
**Core message:** Give Indian MSMEs one place for invoices, stock, CRM, expenses and practical operational summaries.

**How it works:** Business membership and scoped data, GST-aware invoicing, payments, expenses, customer/product records, idempotent reminder tasks and read-only business answers.

**Tech stack / AI features:** Next.js; TypeScript; Prisma; SQLite local database; bcrypt sessions; Vitest; Node; adapters for future external providers.

**Links:** [Source repository](https://github.com/faruk00095/royals-ai-businessos)

**Evidence and limits:** README explicitly says external AI is not connected and “ROYAL AI” answers come from saved records, not an LLM. **Verification:** repository-backed.

### 23. Octillion

**Category:** Developer observability / MCP  
**Core message:** Expose product, customer and agent trace evidence to assistants through read-only MCP tools and a visual dashboard.

**How it works:** Ask an assistant about product state, user cohorts or trace runs; MCP tools query their appropriate data sources and return text plus structured UI.

**Tech stack / AI features:** TypeScript/Node; MCP Apps/MCP-UI; PostgreSQL/PGlite; optional S3, ClickHouse and Langfuse; Docker Compose; end-to-end smoke tests.

**Links:** [Source repository](https://github.com/SoumilB7/Octillion)

**Evidence and limits:** Zero-config local mode uses embedded PGlite and lacks external search and Langfuse features. **Verification:** repository-backed.

### 24. Quartermaster (OFC Decision)

**Category:** Enterprise testing / ERP  
**Core message:** Regression-test Oracle Fusion Cloud changes before quarterly updates hit production, and package audit evidence.

**How it works:** Write tests in plain text; run browser or Oracle REST checks; capture screenshots and audit-friendly Word evidence; gate production-impacting actions.

**Tech stack / AI features:** Python 3.11+; Playwright; pytest; local `qm` service/CLI; OpenAI Decisions API optional judgment; Word report export.

**Links:** [Source repository](https://github.com/0x-Shashi/OFC_Decission)

**Evidence and limits:** README says AI is advisory and human gatekeeper approves actions. **Verification:** repository-backed.

### 25. Mintaro — Milestone Escrow

**Category:** Freelancing / Web3 escrow  
**Core message:** Reduce freelancer–client payment disputes with milestone-based escrow rather than all-or-nothing transfers.

**How it works:** Clients fund milestones; freelancers can withdraw on completion; contract tracks cancellation and dispute state on a public test network.

**Tech stack / AI features:** Solidity smart contracts; Hardhat; JavaScript; web frontend; Avalanche Fuji testnet; AVAX/ERC-20 transfers.

**Links:** [Source repository](https://github.com/mohammedsafwankhan/trustless-escrows)

**Evidence and limits:** Testnet MVP, not evidence of audited contracts or production money handling. **Verification:** repository-backed.

### 26. The Understudy

**Category:** Browser automation / teach-by-doing  
**Core message:** Teach a browser task once, turn it into an editable skill, and repeat it with visible human control.

**How it works:** Observe a demonstration, summarize steps into a plain-language Skill Card, obtain approval, then perform the repeatable browser flow while surfacing progress.

**Tech stack / AI features:** Vite; TypeScript; frontend src/; Node server routes; browser automation agent architecture (specific driver requires code-level verification).

**Links:** [Source repository](https://github.com/tanisha-kiran/understudy)

**Evidence and limits:** Prototype; precise browser automation driver and model provider not confirmed from accessible README excerpt. **Verification:** repository-backed.

### 27. Handbrake

**Category:** Agent safety / human approvals  
**Core message:** Let AI agents automate the routine browser clicks while pausing on risky actions such as payment, sending and deleting.

**How it works:** MCP browser controller classifies proposed actions; low-risk operations continue; high-risk operations request native approval/elicitation.

**Tech stack / AI features:** Node.js/JavaScript; MCP; Playwright Chromium; OpenAI Decisions API; GPT-6.1 Sol computer-use; Codex/Claude Code compatibility; Vercel demonstration.

**Links:** [Source repository](https://github.com/aashish00021/handbrake) · [Live app / demo](https://handbrake-eosin.vercel.app)

**Evidence and limits:** Developer-reported risk classification/latency should not be assumed universal; approval depends on MCP client behavior. **Verification:** repository-backed.

### 28. Guardian GPT

**Category:** Payment fraud / decision support  
**Core message:** Interrupt UPI and “digital arrest” scams before a risky transfer, with a trusted-person approval path.

**How it works:** Analyze surrounding chat/call/screenshot/payment context; classify allow/warn/hold and route a proposed action for family authorization.

**Tech stack / AI features:** JavaScript/Node; OpenAI Decisions API; GPT-6.1 Sol; MCP/ChatGPT plugin surface; Agents API; Dots-oriented design; demonstration web UI.

**Links:** [Source repository](https://github.com/Drix10/guardian-gpt)

**Evidence and limits:** Repository claims demo results on a limited case set; temporary tunnel URL is not a durable app deployment. **Verification:** repository-backed.

### 29. px0-flow

**Category:** Developer review / code change graphs  
**Core message:** Show how a code change travels from a user-facing screen through APIs, services and database effects.

**How it works:** Augment px0 code navigation with a Change Flow graph; inspect modified symbols across layers and jump to the associated diff.

**Tech stack / AI features:** Go CLI/TUI and source-navigation engine; Git/LSP; graph visualization; web assets; Go tests.

**Links:** [Source repository](https://github.com/valpetaltechlabs/px0-Flow)

**Evidence and limits:** Duplicate repository appears again at #30; counts as one distinct app. **Verification:** repository-backed.

### 30. px0-flow — duplicate listing

**Category:** Duplicate / same project as #29  
**Core message:** Same project as rank #29, not a separately verified submission.

**How it works:** Same change-impact graph workflow.

**Tech stack / AI features:** Same Go CLI/TUI, Git/LSP, graph and tests as rank #29.

**Links:** [Source repository](https://github.com/valpetaltechlabs/px0-Flow)

**Evidence and limits:** Position kept to preserve original provided order. **Verification:** duplicate listing.

### 31. Agent Black Box

**Category:** Enterprise agent governance  
**Core message:** Make AI agents propose actions, but enforce permissions with deterministic rules and a complete audit trail.

**How it works:** A planner proposes synthetic enterprise operations; Python policy ALLOW/BLOCK/REVIEW decides execution; review approvals are single-use; SQLite retains traces.

**Tech stack / AI features:** Python; Streamlit; SQLite; MCP server; OpenAI Responses/GPT-6.1 Sol; optional Decisions API; policy engine; synthetic fixtures.

**Links:** [Source repository](https://github.com/pagadalagopihemanth/agent-black-box)

**Evidence and limits:** No real banking or supplier actions; all business transactions in the demo are synthetic. **Verification:** repository-backed.

### 32. Neighbourhood Finds

**Category:** Hyperlocal discovery / Bengaluru  
**Core message:** Find interesting local places using neighborhood-aware categories, community picks and conversational search.

**How it works:** Explore curated HSR Layout places with filters for food, cafés, budget, work-friendliness and neighborhood scenes; switch between list and map.

**Tech stack / AI features:** Web app hosted as ChatGPT Site; map/list search UI and curated place data. Exact application framework, AI provider and backend unverified.

**Links:** [Live app / demo](https://neighbourhood-finds.reshma-nurix.chatgpt.site/?scope=all)

**Evidence and limits:** Public site shows a curated HSR dataset; do not infer full-city or live provider coverage. **Verification:** site-limited.

### 33. Proposal Engine

**Category:** Agency services / pricing  
**Core message:** Convert a client brief into a proposal whose price and schedule can be traced to past delivery hours.

**How it works:** Extract requirements; retrieve similar work; deterministically calculate P50/P90 hours, schedules and prices; explain risks and generate proposal text.

**Tech stack / AI features:** JavaScript/Node; Netlify Functions; ChatGPT Apps SDK / MCP; OpenAI Responses API and embeddings optional; deterministic TF-IDF/rules fallback.

**Links:** [Source repository](https://github.com/sanket-fls/proposal)

**Evidence and limits:** Numbers are computed from historical cases, never invented by the LLM. **Verification:** repository-backed.

### 34. Spec2Proof

**Category:** Software requirements / verification  
**Core message:** Turn a business requirement into executable acceptance tests and a reviewed, reproducible fix.

**How it works:** Compile ten acceptance criteria from sample refund policy; run Python unittest against seeded bugs; propose a small patch; require approval and export proof ZIP.

**Tech stack / AI features:** Python 3.10+ standard library; unittest; local HTTP server; MCP Apps / ChatGPT plugin; HTML/JavaScript workbench; no model API required for core demo.

**Links:** [Source repository](https://github.com/bismillahkani/spec2proof)

**Evidence and limits:** The compiler and repair are intentionally bounded to seeded fixture—not arbitrary code or general LLM code repair. **Verification:** repository-backed.

### 35. Spring Winter

**Category:** Undetermined / website only  
**Core message:** Not enough accessible public information to establish the application’s core message accurately.

**How it works:** Provided site returned no readable project description in the available interface.

**Tech stack / AI features:** Tech stack not independently verifiable from supplied domain.

**Links:** [Live app / demo](https://springwinter.dev)

**Evidence and limits:** Needs screenshot, source code or project card to identify app function. **Verification:** site-limited.

### 36. Pickture

**Category:** Media / streaming recommendation  
**Core message:** Replace endless movie browsing with one choice suited to your mood and existing subscriptions.

**How it works:** Pick streaming services and mood, answer four questions, compare IMDb/Rotten Tomatoes/Metacritic scores, and avoid repeated suggestions.

**Tech stack / AI features:** Web app; TMDB API; OMDb API; browser-local choice/history. Framework and model provider not disclosed.

**Links:** [Live app / demo](https://pickture.fun/#/welcome)

**Evidence and limits:** No specific LLM integration or working stack can be inferred solely from UI. **Verification:** site-limited.

### 37. Better Wardrobe

**Category:** Fashion / personal commerce  
**Core message:** Put fashion inspiration, similar items and one’s own wardrobe into a coherent discovery workspace.

**How it works:** Explore garments from reference images, related shopping matches, existing catalog and saved wardrobe choices; support a Mall/Discover navigation.

**Tech stack / AI features:** Web prototype with app source in GitHub; OpenAI optional Decisions API path (off by default); hosted Vercel/ChatGPT Sites previews. Exact runtime dependencies require manifest inspection.

**Links:** [Source repository](https://github.com/ChoudharyAyan/Better-Wardrobe-ChatGPT-Hackathon) · [Live app / demo](https://better-wardrobe-hackathon.vercel.app)

**Evidence and limits:** AI image/product search requires provider configuration; sample content should not be mistaken for live retailer search. **Verification:** repository-backed.

### 38. Ozark AML Agent Demo

**Category:** Financial compliance / AML analyst  
**Core message:** Help an analyst investigate suspicious transactions using evidence, deterministic risk scoring and supervised AI drafting.

**How it works:** Retrieve mock cases through MCP tools; apply explicit Python risk rules; summarize evidence; stop high-risk actions for analyst review; mock SAR workflow.

**Tech stack / AI features:** Python 3.11+; Streamlit; MCP HTTP server; deterministic rules; optional external LLM prose via configurable Astra-compatible endpoint.

**Links:** [Source repository](https://github.com/vinpuj/ozark-aml-agent-demo) · [Live app / demo](https://c98seejruejgf9nkgekpj5.streamlit.app/)

**Evidence and limits:** Mock data, no banking integrations or actual SAR submission. **Verification:** repository-backed.

### 39. PlotTwist

**Category:** Storytelling / learning  
**Core message:** Make entertainment and skill practice interactive by letting each choice redirect the story.

**How it works:** Play branching illustrated stories or learn through decision-led courses; user choices shape consequences; optional generated dialogue, transcription and illustrations.

**Tech stack / AI features:** React; TypeScript; Vite; Node server; Netlify Functions; OpenAI Decisions/Responses, STT, Images and optional Realtime; localStorage/IndexedDB; Vitest.

**Links:** [Source repository](https://github.com/futurelabstudios/plottwist) · [Live app / demo](https://plottwistbyfuturelab.netlify.app)

**Evidence and limits:** Author-created stories work without API key; realtime voice path still requires device verification per README. **Verification:** repository-backed.

### 40. Agent Arcade

**Category:** Games / playful AI brands  
**Core message:** Make a lighthearted browser arcade where players choose a model-themed fighter and play games.

**How it works:** Choose a fighter (including Dot), pick games, save an optional local player name, and track browser-local ranking.

**Tech stack / AI features:** Browser game hosted at agentarcade.fun; browser-local saved player profile. Specific JS framework, backend and AI API usage not verifiable.

**Links:** [Live app / demo](https://agentarcade.fun)

**Evidence and limits:** Fan-made, not affiliated with named AI companies; the site does not establish that agents are actually executing the game. **Verification:** site-limited.

## 3. What participants built — thematic distribution

**Editorial categorization of the 38 distinct apps above**, not organizer-issued labels. Each app has exactly one primary category here; real use cases overlap.

| Primary application class | Distinct apps | Share of the 38 listed distinct apps | Positions |
|---|---:|---:|---|
| Health and care | 2 | 5% | #1, #2 |
| Consumer security / safety | 6 | 16% | #6, #13, #27, #28, #31, #38 |
| Developer tools / engineering | 11 | 29% | #4, #7, #8, #9, #10, #12, #23, #24, #26, #29, #34 |
| Personal / work and education | 8 | 21% | #3, #5, #15, #16, #19, #21, #22, #33 |
| Shopping / commerce / local | 5 | 13% | #14, #25, #32, #36, #37 |
| Creative / entertainment | 3 | 8% | #11, #39, #40 |
| Information / attention / video | 2 | 5% | #18, #20 |
| Unknown / no readable project description | 1 | 3% | #35 |
| **Total** | **38** | **100% (rounded row percentages)** | Excludes duplicated ranks #17 and #30 |

### Engineering patterns demonstrated

**Bounded or structured decisions with deterministic execution.** DawaiDost, RaktSetu, ScamSense, DemoPilot, Shopping Assistant, Guardian, Agent Black Box, Handbrake and others limit the output space of model-driven classifications or actions. A recommended decision is not automatically granted authority to move money, medicine, blood or enterprise records. See each project’s own README for its actual human-review boundary.

**Trust and provenance as product features.** Architect, AMU, antislop, VideoMem, Proposal Engine and Spec2Proof tie explanations to source code, time-stamped observations, comparable past work or executable test evidence. This can make generated outputs easier to inspect; it is not the same as independently proving correctness.

**Hands-free and multimodal input.** DawaiDost, BoloRider, Ghost Hands, Roody, Sarthi, Speech-Machine and PlotTwist use voice, screenshots, audio or video to reduce reliance on lengthy forms. Their architectures vary substantially, from browser speech APIs and local ASR to OpenAI real-time audio and computer-use tools.

**MCP / ChatGPT extension ecosystem.** Sarthi, OSS Mentor, Shopping Assistant, Octillion, Handbrake, Proposal Engine and Spec2Proof illustrate different ideas for connecting tools and/or interactive panels to assistants. Do not assume that every web dashboard is a ChatGPT plugin merely because it appeared at a DevDay event.

### Stack vocabulary — what the presence of a name means

| Component | What it typically supplies | Example app(s) from this list | Caveat |
|---|---|---|---|
| OpenAI Decisions API | Typed choice/score/predicate judgments | DawaiDost, RaktSetu, ScamSense, Sarthi, Handbrake | Policy code must still enforce actual permissions |
| OpenAI Responses API | Structured extraction/generation, tools, multimodal reasoning | BoloRider, VideoMem, Architect, PlotTwist | Many projects have no-key fallback or optional integrations |
| OpenAI Realtime / speech APIs | Low-latency voice interaction and transcription | DawaiDost, BoloRider, Roody | Browser and network conditions affect actual latency |
| MCP / ChatGPT plugin surface | Assistant-accessible tools or custom UI | Sarthi, Shopping Assistant, Octillion, Spec2Proof | Plugin compatibility depends on its host and installation state |
| Next.js / React | Frontend and sometimes API routing | DawaiDost, Sarthi, Architect, Speech-Machine | Not evidence of a particular model or vector database |
| Python / FastAPI / Streamlit | Backends, analysis, or dashboards | RaktSetu, antislop, MazikDLP, Speech-Machine, Agent Black Box | Functionality and deployment readiness differ |
| SQLite / PostgreSQL | Persisted state and review traces | ROYAL’S OS, Speech-Machine, Octillion | Production performance cannot be inferred from use alone |
| Browser extension / computer-use | In-context assistance or intercept/automation | Roody, YouFeedLens, MazikDLP, Ghost Hands, Handbrake | Security permissions and UI drift are important |

## 4. Examples worth studying technically

These are **technical exemplars**, not a second ranking or a statement about prize entitlement.

| If you want to learn… | Study | Reason to inspect |
|---|---|---|
| Decision support with human sign-off | [DawaiDost](https://github.com/RahilKothari9/DawaiDost), [RaktSetu](https://github.com/SayedZahur786/RaktSetu) | Deterministic numeric/policy logic, bounded recommendations, approval steps |
| Codebase graph and AI coding safety | [Architect](https://github.com/Harshakoliki/Architect), [AMU](https://github.com/abslock128w/AMU), [px0-flow](https://github.com/valpetaltechlabs/px0-Flow) | Evidence-linked dependency and change-flow reasoning |
| Verification and reproducibility | [antislop](https://github.com/nomercy77/antislop), [Spec2Proof](https://github.com/bismillahkani/spec2proof) | Layered assurance, bounded proofs and acceptance tests |
| Browser agent consent | [Handbrake](https://github.com/aashish00021/handbrake), [Ghost Hands](https://github.com/Arham-Begani/ghost-hands) | Risky-action brakes, visible cursor actions and teach-back |
| Agent governance and audit | [Agent Black Box](https://github.com/pagadalagopihemanth/agent-black-box), [Guardian](https://github.com/Drix10/guardian-gpt) | Hard authorization boundaries distinct from AI recommendations |
| Audio, video and local AI | [Speech-Machine](https://github.com/SSusantAchary/speech-machine), [VideoMem](https://github.com/kunal3108/videomem), [BoloRider](https://github.com/shhhivam12/bolorider) | ASR, frame reuse, voice task design and multimodal grounding |
| MCP app design | [Sarthi](https://github.com/SawhneySatvik/Sarthi), [Octillion](https://github.com/SoumilB7/Octillion), [OSS Mentor](https://github.com/Karan-Raj-KR/OSS-Mentor) | Assistant-facing tools, structured content and domain workflows |

## 5. Data-quality issues and open items

1. **Reported ranking versus official awards.** The 1–40 sequence is the order given by the event participant. The accessible event board only exposes an application shell with projects loading, not a confirmable 1–40 judging table. **Do not label each rank an officially certified award position** without organizer documentation.
2. **Duplicates:** positions 16/17 and 29/30 are repeated identical GitHub repositories. Ask whether the second positions represent distinct submissions, links accidentally pasted twice, or different builds not captured in the URLs.
3. **Seven unnamed submissions:** based on 45 distinct apps minus 38 distinct links. Their project titles, ranking and stack should remain **unfilled** until a reliable record is available.
4. **Site-only technical uncertainty:** The Gauntlet (#11), BuildScout (#15), Dsider (#19), Neighbourhood Finds (#32), Spring Winter (#35), Pickture (#36) and Agent Arcade (#40) supply little or no directly inspectable repository metadata. Each remains described at the level its public evidence permits.
5. **Evolving repos:** some READMEs describe pre-existing features and post-event commits. A frozen commit SHA/tag from the day of judging is preferable to treating the current main branch as the exact submitted build.
6. **Model marketing versus functionality:** no-key fallback, demo fixtures, stub provider adapters, synthetic transactions, and planned APIs are identified per app. Do not count them as demonstrated live integrations.
7. **Data sources:** some sites load project content only after JavaScript; page titles alone cannot establish complete behaviors or backend dependencies.


## 6. Additional verification rubric for anyone extending this README

For each app, preserve: exact board title, immutable submission ID, full team, timestamp, app tagline, repository commit hash, screenshots or demo video, actual AI models and API paths, third-party services, deployment URLs, safety/approval design, tests/evals, and limitations. Record whether each item is **repository-confirmed**, **owner-reported**, **site-only**, or **not disclosed**. A tech-stack line should never be inferred from a project name or screenshots.

### Recommended project card template

```yaml
reported_order: 1
official_award_rank: null  # unverified
title: "Application name"
core_message: "Why the product exists"
audience: "Who benefits"
workflow: "Input -> action -> checked output"
stack:
  frontend: []
  backend: []
  models_apis: []
  persistence: []
repository_url: null
submission_commit_sha: null
demo_url: null
evidence: ["README", "demo"]
verification: "unverified"
```

## 7. Sources

- **User-provided ranking and links:** supplied in this conversation, 40 numbered positions. Used **only** as the source of rank order, not as independent judging documentation.
- **Build board:** https://devday-bengaluru-build-board.hello429616.chatgpt.site/ — shell displays announced results heading and asynchronously loaded project section; individual project records unavailable to the text retrieval interface.
- **Organizer event listing:** https://luma.com/0bdmf0sw — identity, venue, schedule, organizers, judging design.
- **Individual primary sources:** GitHub README or public app website linked in each ranking row and app profile. Project-authored claims, examples and metrics remain attributed to the owner.
- **Access / research date:** Sunday, **11 October 2026**. Links may change after the hackathon.

---

**Current coverage:** 40 supplied rank positions, 38 unique applications described, 31 distinct GitHub repos and 7 apps without repositories in the supplied list, 7 unknown distinct submissions remaining if the event total of 45 is exact. **This document is a rich participant-order catalog, not a certified winners announcement.**
