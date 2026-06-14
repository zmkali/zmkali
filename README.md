# Zayaan Ali

#### CS Student • Product Builder • ML Engineer

Final-year Computer Science student at BITS Pilani Dubai, building at the intersection of AI, product, and operations.

---

## Profile

- Head of Operations at R13 Labs, an early-stage EdTech startup
- Experience building AI-powered products end-to-end — from UI design to ML pipelines to deployment
- Strong focus on RAG systems, applied ML, and full-stack product development
- Interested in AI Systems, Agentic Workflows, and Operations-driven Product Building

---

## Core Projects

### Aqademiq — AI-Powered Student Productivity App

AI academic study hub featuring an integrated AI assistant (Ada), smart schedule management, grade tracking, Google Calendar sync, and study planning — currently in private beta with 500+ users ahead of iOS and Android launch.

- Built the PWA using React 18, TypeScript, and Vite with Tailwind CSS and shadcn/ui components, backed by Supabase (PostgreSQL + Deno Edge Functions) and deployed at a custom domain
- Co-designed the entire mobile app UI in Figma and converted all screens into a Flutter/Capacitor codebase using AI-assisted tools
- Integrated AI assistant "Ada" with OCR-based schedule parsing, contextual study insights, and Google Calendar OAuth sync with persistent token management
- Recognised as Innovative Education Platform of the Year — CorporateLiveWire Innovation & Excellence Awards 2026 (UK)

---

### Stress Detection & Adaptive Psychoacoustic Intervention

Dual-dataset machine learning pipeline detecting student stress from wrist-worn sensor signals.

- Built using WESAD and DEAP physiological datasets, achieving 91.33% accuracy
- Engineered 10 physiological features from EDA, BVP, and skin temperature signals with 5-fold stratified cross-validation
- Developed a cross-dataset bridge connecting stress detection to emotion zones, generating real-time personalised binaural beat and haptic intervention prescriptions via a live Streamlit application

---

### Hallucination Detection in Retrieval-Augmented Language Models (RALMs)

Token-level uncertainty quantification pipeline for detecting hallucinations in RAG systems.

- Designed using Information Gain, KL Divergence, and Confidence Drop metrics computed over GPT-2 probability distributions
- Built a logistic regression composite model achieving 0.734 AUROC on RAGTruth
- Evaluated across 6 LLMs including GPT-4, GPT-3.5, Llama-2 variants, and Mistral-7B, with zero-shot cross-domain transfer to HaluEval yielding 0.925 AUROC

---

### Prism Stem Splitter

Production-grade web application for separating audio tracks into 6 isolated stems (vocals, drums, bass, guitar, piano, other) using Meta's HTDemucs model.

- Engineered an audio separation pipeline using HTDemucs achieving high Signal-to-Distortion Ratio (SDR), with FFmpeg preprocessing to normalise and convert arbitrary audio formats into standardised model inputs
- Architected an asynchronous FastAPI REST API handling file uploads, background job processing, and real-time progress polling — returning a job ID immediately so the frontend can track long-running inference tasks
- Implemented dynamic hardware acceleration detection across NVIDIA CUDA, Apple MPS, and CPU backends, making the application hardware-agnostic out of the box

---

## Technical Stack

### AI / ML Systems

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=3776AB)
![PyTorch](https://img.shields.io/badge/PyTorch-000000?style=for-the-badge&logo=pytorch&logoColor=EE4C2C)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-000000?style=for-the-badge&logo=scikitlearn&logoColor=F7931E)
![NumPy](https://img.shields.io/badge/NumPy-000000?style=for-the-badge&logo=numpy&logoColor=013243)
![SciPy](https://img.shields.io/badge/SciPy-000000?style=for-the-badge&logo=scipy&logoColor=8CAAE6)

### Mobile & Frontend

![React](https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Vite](https://img.shields.io/badge/Vite-000000?style=for-the-badge&logo=vite&logoColor=646CFF)
![Flutter](https://img.shields.io/badge/Flutter-000000?style=for-the-badge&logo=flutter&logoColor=02569B)
![Dart](https://img.shields.io/badge/Dart-000000?style=for-the-badge&logo=dart&logoColor=0175C2)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-000000?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![Figma](https://img.shields.io/badge/Figma-000000?style=for-the-badge&logo=figma&logoColor=F24E1E)

### Backend & APIs

![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=009688)
![Supabase](https://img.shields.io/badge/Supabase-000000?style=for-the-badge&logo=supabase&logoColor=3FCF8E)
![n8n](https://img.shields.io/badge/n8n-000000?style=for-the-badge&logo=n8n&logoColor=EA4B71)
![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=47A248)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=4479A1)

### Languages

![Java](https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=437291)
![C](https://img.shields.io/badge/C-000000?style=for-the-badge&logo=c&logoColor=A8B9CC)

---

## Experience

**Head of Operations — R13 Labs India Pvt Ltd** *(Sept 2025 – Present)*

- First operations hire at a 12-person EdTech startup; designed operational infrastructure spanning communications, project management, CRM, finance visibility, and HR onboarding
- Co-developed a 26-week company-wide Gantt roadmap spanning Technical, Marketing, Operations, and Finance workstreams tracking app launch milestones, university outreach, and a 10,000-user growth target across 4 phases

**Software Engineer Intern — TechnoCit Software Solutions** *(Jun 2025 – Oct 2025)*

- Developed an agentic banking chatbot and multi-country web scraping systems using n8n
- Engineered RAG pipelines using vector embeddings and semantic similarity search

---

## Achievements

- MIF Finalist — Mookerji Innovation Fund · AWS & GCP Cloud Credits Recipient
- CorporateLiveWire Innovation & Excellence Award 2026 (UK)

---

## Connect

LinkedIn: [zayaanalimk](https://www.linkedin.com/in/zayaanalimk/) · Email: zayalimk@gmail.com · Dubai, UAE
