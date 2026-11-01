# DecodeLabs_Tasks

A collection of four full-stack Generative AI projects completed during my Generative AI internship at DecodeLabs. Each internship brief was developed into a complete, product-grade AI application — FastAPI backends with Google Gemini integration, modern frontends, SQLite or JSON persistence, automated tests, and deployment configuration — demonstrating practical AI engineering, software development, problem-solving, and hands-on learning.

Each project folder has its own detailed README with setup instructions, architecture, API references, and quick-start guides.

## Projects

### 1. AI Chatbot — Oryn (Zorex AI Workspace)
**Folder:** `DecodeLabs-AI Chatbot`

A focused, local-first AI workspace for planning, learning, writing, coding, and context-aware conversations. Features persistent conversations, bounded context management, guided productivity modes (Plan / Learn / Write / Code), profile personalization, dark and light themes, and a demo mode that works without an API key. Backend: Python 3.10+, FastAPI, Uvicorn, Pydantic, google-genai SDK (Google Gemini, gemini-3.1-flash-lite), thread-safe JSON chat storage. Frontend: vanilla HTML/CSS/JavaScript (Fetch API, LocalStorage).

### 2. Image Generation Studio — Prismora (AI Visual Studio)
**Folder:** `DecodeLab-Multimodial Image Generation Studio`

A private, product-grade visual creation studio for prompt intelligence, image generation, and precision creative control. Turn ideas into structured production prompts, choose a visual direction and canvas, generate and refine images, and organize them in a private library. Stack: Python 3.13+, FastAPI, Pydantic 2, Requests, Pillow, SQLite; Google Gemini for prompt enhancement and vision QA; Cloudflare Workers AI (FLUX.1 Schnell) for generation; HTML/CSS/Vanilla JavaScript frontend. Includes 8 visual directions, 6 creative finishes, 8 canvas formats, 22 documented routes, PBKDF2-HMAC-SHA256 password hashing with session cookies, and a Pytest suite (8/8 passing) with GitHub Actions CI.

### 3. Code Reviewer & Explainer — CodeFix AI
**Folder:** `DecodeLab-Intelligent Code Reviewer and Explainer`

A full-stack AI-assisted code review platform: evidence-grounded review, validated corrections, clean-code verification, and structured explanations in one engineering workspace. Combines deterministic validation (Tree-sitter, built-in validators, AST checks, optional compiler/parser toolchains) with a multi-stage Gemini review and verification pipeline. Frontend: React 18 + Vite 5. Backend: Python 3.10+, FastAPI, Uvicorn, Pydantic, SQLite. Supports Python, the JavaScript/TypeScript ecosystem, JVM languages, the C family, Go, Rust, Swift, scripting languages, HTML, CSS, and SQL — up to 100,000 characters per submission. Ships with Docker Compose + Nginx production serving and GitHub Actions CI.

### 4. Copywriting Tone Transformer — Lexora (AI Tone Studio)
**Folder:** `DecodeLabs - Automated Copywriting Tone Transformer`

A full-stack workspace for controlled copy generation, tone transformation, and CSV campaign automation. Define a structured creative brief (audience, objective, platform, tone, formality, brand voice, model controls) and generate editable Safe/Creative/Bold variations — or process up to 200 CSV rows in bulk with the same typed generation engine, plus a standalone CLI. Stack: React 18.3 + Vite 5.4 + Tailwind CSS 3.4 frontend; Python 3.12+, FastAPI, Pydantic 2, Google Generative AI SDK (Gemini), Tenacity, SQLite backend. Includes 13 generation/transformation modes, 8 platform-aware presets, 9 tone profiles, account-based persistence (PBKDF2-HMAC-SHA256 password hashing, HTTP-only session cookies), Pytest backend tests, and GitHub Actions CI.

## Tech Stack

- **Languages:** Python, JavaScript, TypeScript
- **Generative AI:** Google Gemini (google-genai SDK), Cloudflare Workers AI (FLUX.1 Schnell)
- **Backend:** FastAPI, Pydantic, Uvicorn, SQLAlchemy-style persistence, SQLite, JSON stores
- **Frontend:** React 18, Vite 5, Tailwind CSS, vanilla HTML/CSS/JavaScript
- **Validation & Parsing:** Tree-sitter, Python AST, optional compiler toolchains
- **Security:** PBKDF2-HMAC-SHA256 password hashing, HTTP-only SameSite session cookies, environment-based secrets
- **DevOps & Tooling:** Docker, Docker Compose, Nginx, Pytest, GitHub Actions

## Getting Started

Each project folder is self-contained with its own README — start there for install steps, environment configuration, and quick-start guides. Gemini API keys stay on the backend (in each project's `.env`) and are never committed.

## Author

Muhammad Saad Jadoon — AI Engineer
