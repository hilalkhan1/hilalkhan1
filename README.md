<h1 align="center">Hilal Khan</h1>
<p align="center"><b>AI &amp; Automation Engineer</b> · I build the systems that turn repeat work into software, and the tooling that proves they work.</p>

<p align="center">
  <a href="https://hilalkhanai.netlify.app">Portfolio</a> ·
  <a href="https://linkedin.com/in/khanhilal">LinkedIn</a> ·
  <a href="https://kaggle.com/hilalkhan">Kaggle</a> ·
  <a href="https://twitter.com/hilalkh52">X</a> ·
  <a href="mailto:hilalkhan.ai.dev@gmail.com">hilalkhan.ai.dev@gmail.com</a>
</p>

---

### Professional experience

#### AI & Automation Engineer, [Digital TEN X](https://digitaltenx.qa/) · *Jun 2026 – Present*
I lead AI and automation work across the agency, from internal SaaS products to how client websites are built and delivered.

- **Building AI-powered products.** I design, build and deploy internal SaaS end to end, from architecture and data model to CI/CD and production hosting. The work includes LLM content pipelines, CRM and marketing tools, and client-site management.
- **LLM integration.** I build workflows on the Claude API and Agent SDK with structured JSON output, approval steps and fallbacks, and add speech-to-text (Whisper) and AI image generation where a workflow needs them.
- **Automating delivery.** I automate the design-to-site pipeline (Figma → HTML → Astro, Shopify or WordPress/Elementor) with custom Claude Code skills, and use Playwright to check every build against its source.
- **Business process automation.** I connect the tools the team and its clients already use (Meta, LinkedIn, GoHighLevel, Asana, Gmail, WhatsApp Business, Stripe) through APIs, n8n workflows and webhooks.
- **Cloud & infrastructure.** I run serverless apps on Cloudflare (Workers, Workflows, D1, R2, Queues, Durable Objects) and servers on AWS EC2, with GitHub Actions deploys, and I handle security hardening and audits.
- **Web performance & AI visibility.** I tune Core Web Vitals, structured data and AI-search readiness (llms.txt, AI-crawler policy) on bilingual client sites.

#### Co-Founder & AI Developer, CAI&ET (Center for AI & Emerging Technologies) · *Sep 2025 – May 2026*
- Designed and taught AI, machine learning and Python courses, including a [Python Programming Bootcamp](https://github.com/hilalkhan1/PythonProgrammingBootcamp), and mentored students on applied AI and model deployment.
- Built the center's education management platform for courses, content and applications. Stack: Django REST Framework, React, PostgreSQL, Redis, Docker and AWS.
- Developed AI-driven teaching tools and internal automation for the center's day-to-day work.

#### AI Developer, Digital 10X · *Jun 2025 – Sep 2025*
- Built automation and trading systems in Python and FastAPI, including real-time signal processing and task automation pipelines.
- Improved data pipeline performance and cut manual workload.

---

### Featured work

| Project | What it is | Stack |
|---|---|---|
| **[PerseveREST](https://github.com/hilalkhan1/PerseveREST)** | A black-box REST API testing tool for the ICSE 2027 REST League, built on RestTestGen. It adds malformed-request and field-by-field invalid-value strategies. It was evaluated over 60-minute runs on 11 APIs in the RESTgym harness, and a 4-page paper goes with it. | Java · Docker · RESTgym · Azure |
| **PostPilot** | Write once, publish to Facebook Pages, Instagram and LinkedIn now or on a schedule, all on free tiers. Postgres is the queue (`FOR UPDATE SKIP LOCKED`, driven by a cron heartbeat). Each post is tracked per destination, so a partial failure retries only what failed. | Next.js · TypeScript · Drizzle · Neon · Supabase |
| **D10X Blog Engine** | An AI publishing pipeline for client sites. It researches, writes, translates and illustrates articles and sends them for one-click client approval. Output goes to WordPress, GitHub-backed static sites or webhooks, with social posts pushed to GoHighLevel. A video-to-article route uses ffmpeg, Whisper and Claude. | Cloudflare Workers · Workflows · D1 · R2 · Claude · Workers AI |
| **LeadByDigitalTenX** | A CRM and growth platform, our in-house alternative to GoHighLevel. Phase 1 covers contacts, a sales pipeline, forms and surveys, team invites, and email sequences run by a Durable Object. | Turborepo · Hono · Drizzle · Supabase Postgres · Better Auth · React |
| **SiteManagementByD10X** | One dashboard for every client website: daily update checks, a digest email and one-click remote updates. A multi-tenant hub talks to a self-updating WordPress connector over HMAC-signed requests. It runs in production on AWS. | Laravel 13 · Filament 5 · PHP 8.5 · MySQL · AWS EC2 |
| **HTML → Elementor** | A WordPress plugin that converts a static HTML/CSS/JS site into native, editable Elementor widgets, not raw-HTML blocks. The admin's browser renders each page and captures computed styles. Each section is then mapped by a deterministic PHP engine or by Claude, linted, and imported. | PHP · JavaScript · Claude API |
| **FB-Connector** | A Meta Ads connector that finds *every* ad account a user can reach. It unions direct, business-owned and client-shared accounts and paginates on `paging.next` only. I built it after reverse-engineering why common connectors miss accounts. | TypeScript · Graph API |

<details>
<summary><b>Earlier projects</b></summary>

- *Prototype for a Resource-Constrained Self-Driving Vehicle* (BS thesis, team of three). Classical lane detection, a fine-tuned YOLOv5s detector (mAP@0.5 89.3), an ultrasonic reflex stop and Arduino control.
- [NeoHacks 2025](https://github.com/hilalkhan1/NeoHacks2025Hackathon): an ML pipeline on TCGA head-and-neck cancer data (Team NeuralBits).
- Solar production and load forecasting (Kaggle) · [robot control by hand gestures](https://github.com/hilalkhan1/robot_controlling_using_hand_gestures) · [GIKI Softcom speed-programming solutions](https://github.com/hilalkhan1/GIKI-soft-com)

</details>

---

### Toolbox

#### 🤖 AI & Automation

| Area | Tools |
|---|---|
| **LLMs & agents** | Claude API · Claude Agent SDK · Claude Code (custom skills) · MCP · Groq · structured JSON output · prompt pipelines with human approval |
| **Machine learning** | PyTorch · TensorFlow · Keras · scikit-learn · Hugging Face Transformers · YOLO · OpenCV · pandas · NumPy |
| **Speech, vision & media** | Whisper (whisper.cpp) · ffmpeg · yt-dlp · Workers AI (FLUX image generation) |
| **Workflow automation** | n8n · Cloudflare Workflows & Queues · GitHub Actions · cron-driven job queues |
| **Browser automation & QA** | Playwright · headless Chrome (CDP) · visual and computed-style regression checks |
| **Integrations** | Meta Graph API (Ads, Pages, Instagram) · LinkedIn API · WhatsApp Business API · GoHighLevel · Asana · Gmail · Stripe |

#### 🛠️ Engineering

| Area | Tools |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · PHP · Java · SQL · C/C++ |
| **Backend & web** | FastAPI · Hono · Laravel + Filament · Django REST · Next.js · Astro · React |
| **Data** | PostgreSQL (Supabase, Neon) · MySQL · SQLite / Cloudflare D1 · Redis · Drizzle ORM |
| **Cloud & ops** | Cloudflare (Workers, D1, R2, Durable Objects, Access) · AWS (EC2, S3) · Azure · Docker · nginx · Linux / WSL |
| **CMS & e-commerce** | WordPress plugin development · Elementor · WP-CLI · Shopify themes (Liquid, CLI, Admin API) |

---

### Education & certifications

- **BS Computer Science (Artificial Intelligence)**, Abdul Wali Khan University Mardan (2021–2025) · CGPA 3.37/4.00, top 10% of class
- **AWS Certified AI Practitioner** · **Claude Certified Developer – Foundations**
- Advanced Deep Neural Networks Bootcamp, GIKI · Machine Learning Specialization, DeepLearning.AI & Stanford · CS50's Introduction to AI with Python, Harvard · CS50's Introduction to Programming with Python, Harvard · CS50's Introduction to Computer Science, Harvard · C and C++ Programming Specialization, Coursera

### Honors

- 🏆 **Winner, NeoHacks 2025 AI Hackathon** (GIKI) · Top 3, Speed Programming, SOFTCOM'25 (GIKI) · Top 10, Speed Programming, SOFTCOM'23 (GIKI) · Prime Minister's Laptop Scheme Awardee (2023)
