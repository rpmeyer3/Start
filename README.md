# Hey, I'm Ryan Meyer

**Software Engineering Student** · Building full-stack applications, ML pipelines, and data-driven solutions.

I'm a Computer Science / Software Engineering student at the University of Georgia with hands-on experience shipping production-grade web apps, deep learning systems, and enterprise data pipelines. I love tackling hard problems, from training attention-based neural networks under extreme noise to automating 45K+ file workflows for real business operations.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rmeyer3)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.ryanmeyer.dev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ryanpaulmeyer@gmail.com)

<!-- -->

## Technical Skills

| Category | Technologies |
|---|---|
| **Languages** | Python · JavaScript · TypeScript · SQL · HTML · CSS · YAML |
| **Frontend** | React · Next.js · Vite · Tailwind CSS · Framer Motion · Radix UI |
| **Backend** | FastAPI · Django REST Framework · Flask · Node.js · Gunicorn |
| **AI / ML** | PyTorch · scikit-learn · OpenAI Whisper · Hugging Face Transformers · Google Gemini API |
| **Databases** | PostgreSQL (Supabase) · SQLite |
| **Data & Analytics** | Pandas · Power BI · Azure Maps · Firecrawl · Playwright |
| **DevOps & Tools** | Docker · GitHub Actions · Vercel · Render · Railway · Git |

<!-- -->

## Projects

### **Pattern Delineation: Deep Learning Image Segmentation**
- **Engineered** a 31.5M-parameter Attention U-Net with CBAM and anti-alias blur-pool downsampling, achieving a **validation Dice score of 0.886** and IoU of 0.796 on segmenting organic shapes under extreme variable noise (SNR from >30 dB to <0 dB).
- **Implemented** a 4-phase curriculum learning strategy (Easy → Extreme noise) with custom composite loss (Dice + BCE + Boundary Tversky), training 80 epochs on an RTX 4070 Ti SUPER with mixed-precision (fp16).
- **Built** a full deployment pipeline (FastAPI backend on Railway, glassmorphism web dashboard on Vercel, and 379 MB model checkpoint hosted on Hugging Face) featuring interactive confidence heatmap overlays and dual-pane comparison viewers.
- **Stack:** PyTorch · FastAPI · OpenCV · Docker · Vercel · Railway · Hugging Face
- [View Project](https://github.com/rpmeyer3/pattern-delineation)

<!-- -->

### **Film Hub: Full-Stack Movie Theater Booking Platform**
- **Architected** a full-stack cinema booking system with Next.js 16 / React 19 frontend and Django REST Framework backend, enabling end-to-end movie browsing, showtime selection, seat reservation, and PCI-aware payment processing.
- **Designed** a real-time seat availability system with showroom management, supporting concurrent bookings across multiple theaters and showtimes with Supabase PostgreSQL as the persistence layer.
- **Developed** a comprehensive user experience including authentication, favorites, reviews, profile management, and an admin panel for movie/showroom CRUD operations, with Resend-powered transactional emails for password resets.
- **Stack:** Next.js · React 19 · Django REST · Tailwind CSS · Supabase (PostgreSQL) · Vercel · Render
- [View Project](https://github.com/rpmeyer3/film-hub) · [Live Demo](https://film-hub-theta.vercel.app)

<!-- -->

### **Byte's Bank: AI-Powered Financial Dashboard** *(UGA Hacks 11)*
- **Built** a wizarding-themed bank statement analyzer that parses uploaded PDF statements, classifies transactions into 10 spending categories using a **Naive Bayes ML classifier** (TF-IDF + Multinomial NB), and delivers AI-generated financial advice via Google Gemini with ElevenLabs text-to-speech narration.
- **Integrated** Supabase Auth (PKCE + Row Level Security) with a React 18 frontend featuring drag-and-drop upload, gamified wizard-rank progression (Muggle → Order of Merlin), and a mobile-first responsive design with Framer Motion animations.
- **Deployed** on Vercel (frontend) and Render (backend) with a FastAPI service layer handling PDF extraction via pdfplumber, ML inference, and Gemini API orchestration.
- **Stack:** React · FastAPI · scikit-learn · Google Gemini · Supabase · ElevenLabs · Vercel
- [View Project](https://github.com/rpmeyer3/bytes-bank) · [Live Demo](https://byte-bank-mauve.vercel.app)

<!-- -->

### **SORAS AI: Audio Summarization App** *(UGA Hacks X)*
- **Developed** an end-to-end audio intelligence pipeline that transcribes uploaded audio files using **OpenAI Whisper**, summarizes transcripts with **Google T5** via Hugging Face Transformers, and plays back summaries through Google Cloud Text-to-Speech, all in a single unified processing endpoint.
- **Collaborated** on a 4-person team, owning UI/UX design and frontend integration with a React 19 / Vite stack and Flask 3.0 backend serving ML inference and TTS endpoints.
- **Stack:** React 19 · Flask · OpenAI Whisper · Hugging Face T5 · Google Cloud TTS · SQLite
- [View Project](https://github.com/rpmeyer3/UgaHacksX)

<!-- -->

### **Norica NA Market Analysis: Data-Driven Market Entry Strategy**
- **Scraped** and analyzed U.S. air rifle retailer data (Pyramyd Air, Airgun Depot) using Firecrawl and Playwright to shift Norica's market approach from "Product Mix" to a data-backed "Sales Mix" strategy, identifying competitor gaps in the Recoil-Free segment.
- **Visualized** feature-to-sales correlations and regional profitability scores in Power BI dashboards with Azure Maps geospatial heat maps, using review volume/velocity and best-seller rankings as sales proxies.
- **Stack:** Python · Pandas · Firecrawl · Playwright · Power BI · Azure Maps · Supabase (PostgreSQL)
- [View Project](https://github.com/rpmeyer3/norica-na-market-analysis-)

<!-- -->

### **Numbers Numbers: Enterprise RFP Data Pipeline**
- **Automated** a 7-step data processing pipeline that scans, extracts, and reconciles Request for Proposal (RFP) data across **45,231 file paths**, filtering down to 8,742 relevant files using fuzzy string matching (fuzzywuzzy + Levenshtein distance) against CRM account databases.
- **Engineered** an intelligent "failed twice" exclusion system that permanently flags unreliable entries, combined with centralized configuration, automatic backups, multi-encoding support (UTF-8/UTF-16), and batch-orchestrated progress tracking.
- **Stack:** Python · Pandas · fuzzywuzzy · openpyxl · Windows Batch scripting
- [View Project](https://github.com/rpmeyer3/numbers-numbers)

<!-- -->

### **Personal Portfolio Website**
- **Designed** a modern, responsive developer portfolio featuring dark/light theme toggling, animated starfield backgrounds, scroll-reveal animations, and section-based navigation, built with React 19, Vite 7, and Tailwind CSS 4.
- **Stack:** React 19 · Vite · Tailwind CSS · Radix UI · Lucide React
- [View Project](https://github.com/rpmeyer3/p-dubyah)

<!-- -->

## Currently Learning

- Exploring advanced deep learning architectures and deployment at scale
- Deepening expertise in cloud infrastructure, CI/CD, and DevOps workflows
- Building more full-stack applications with Next.js and modern React patterns

<!-- -->

## Connect With Me

- **LinkedIn:** [linkedin.com/in/rmeyer3](https://linkedin.com/in/rmeyer3)
- **Portfolio:** [www.ryanmeyer.dev](https://www.ryanmeyer.dev/)
- **Email:** [ryanpaulmeyer@gmail.com](mailto:ryanpaulmeyer@gmail.com)

<!-- -->

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rpmeyer3&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rpmeyer3&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</p>
