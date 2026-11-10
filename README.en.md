<p align="right"><a href="./readme.md">🇧🇷 Português</a> · 🇺🇸 English</p>

<h1 align="center">Luis Carlos Macêdo Moreira</h1>

<p align="center">
  <strong>Full Stack Software Engineer</strong> · Python (Django, DRF, FastAPI) · TypeScript (Node, Deno, React) · AWS · Applied AI
  <br/>
  São Luís, Brazil (UTC−3) · Remote · English C1 (EF SET 70/100)
</p>

<p align="center">
  <img src="./imagens/Perfil_Luis_Carlos.png" alt="Luis Carlos" width="220"/>
</p>

<h2>Who is <span style="color:#9F17ED;">Luis</span>? 💭</h2>

<p>
  I'm a full stack software engineer who ships from service to interface: Python and TypeScript APIs, React frontends and AWS infrastructure as code. I've worked at three companies, with systems in production in Brazil and the United Kingdom.
</p>

<ul>
  <li>🏛️ <strong>São Luís City Hall (SEMAD)</strong>, since May 2025: lead developer of the slaughterhouse sanitary inspection system (FastAPI → DRF, digitally signed reports, dynamic RBAC and CI/CD), the HR data sync with Celery and the service feedback system (React Native kiosk + Node API + dashboard).</li>
  <li>🇬🇧 <strong>CodeLeap (London, remote)</strong>, Oct 2025 – Jun 2026: I wrote the AWS infrastructure in Terraform, moved the LLM-based code grader to Lambda + SQS, eliminated 504 timeouts with Celery and keyset pagination, and wrote 170+ tests.</li>
  <li>🚀 <strong>Dizevolv</strong>, Aug – Oct 2026: I built multi-tenant SaaS products from scratch for the legal, social security and real estate sectors, with LLMs, RAG on pgvector, WhatsApp webhooks and idempotent endpoints.</li>
  <li>🤖 Day to day I work with an agentic development lifecycle (ADLC) using <strong>Claude Code, Cursor and Codex</strong> on top of <strong>GitHub Spec Kit</strong>: spec → plan → tasks → agent implementation, with human review and CI as the quality gate.</li>
  <li>🎓 B.Sc. in Software Engineering at UNDB (2022 – 2026).</li>
</ul>

<h2>⚒ Stack</h2>

<p align="center">
  <strong>Backend</strong><br/>
  <img src="https://skillicons.dev/icons?i=py,django,fastapi,ts,nodejs,express,deno&perline=7" alt="Python, Django, FastAPI, TypeScript, Node.js, Express, Deno"/>
</p>
<p align="center">
  <strong>Data, cloud and DevOps</strong><br/>
  <img src="https://skillicons.dev/icons?i=postgres,redis,supabase,aws,terraform,docker,githubactions,sentry,linux,git&perline=10" alt="PostgreSQL, Redis, Supabase, AWS, Terraform, Docker, GitHub Actions, Sentry, Linux, Git"/>
</p>
<p align="center">
  <strong>Frontend and mobile</strong><br/>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind&perline=3" alt="React, Vite, Tailwind CSS"/>
</p>

<table>
  <tr>
    <td><strong>Python backend</strong></td>
    <td>Django, Django REST Framework, FastAPI, Pydantic v2, SQLAlchemy, Alembic, Celery (+ Beat), Redis, Django Channels</td>
  </tr>
  <tr>
    <td><strong>TypeScript backend</strong></td>
    <td>Node.js, Express, Deno (Supabase Edge Functions), Zod, Vitest</td>
  </tr>
  <tr>
    <td><strong>AWS and IaC</strong></td>
    <td>Terraform, Lambda, SQS, S3, RDS PostgreSQL, Elastic Beanstalk, ALB, ElastiCache, Route 53, IAM, Secrets Manager, Docker</td>
  </tr>
  <tr>
    <td><strong>Architecture</strong></td>
    <td>Event-driven, queues and workers, deduplicated webhooks, idempotency, retry with backoff, multi-tenancy, RBAC, JWT, OAuth 2.0</td>
  </tr>
  <tr>
    <td><strong>Data</strong></td>
    <td>PostgreSQL, pgvector, query optimization (N+1, Exists/Subquery, Prefetch, keyset pagination), schema and data migrations</td>
  </tr>
  <tr>
    <td><strong>Applied AI</strong></td>
    <td>LLMs (Gemini, Anthropic, LiteLLM), RAG with pgvector, tool-using agents with human-in-the-loop</td>
  </tr>
  <tr>
    <td><strong>Frontend and mobile</strong></td>
    <td>React, TypeScript, Vite, Tailwind CSS, TanStack Query, Recharts, React Native (Expo)</td>
  </tr>
  <tr>
    <td><strong>Quality and CI/CD</strong></td>
    <td>GitHub Actions (tests with PostgreSQL, lint, mypy, per-branch deploys, AWS OIDC), pytest, Django TestCase, Sentry, code review</td>
  </tr>
  <tr>
    <td><strong>Agentic dev</strong></td>
    <td>Claude Code, Cursor, OpenAI Codex, GitHub Spec Kit, AGENTS.md / CLAUDE.md</td>
  </tr>
</table>

<h2>📌 Featured projects</h2>

<table>
  <tr>
    <td><strong>Service Feedback (SEMAD)</strong></td>
    <td>Android kiosk in React Native/Expo, Node/Express + PostgreSQL API and a React dashboard with indicators, charts and PDF/Excel export. Dockerized deploy with a one-command installer and daily backups.</td>
    <td><a href="https://github.com/LouisCharlles/avaliacao-atendimento-semad-dashboard">API + dashboard</a> · <a href="https://github.com/LouisCharlles/avaliacao-do-atendimento-semad-totem">kiosk</a></td>
  </tr>
  <tr>
    <td><strong>Slaughterhouse Sanitary Inspection (SEMAD)</strong></td>
    <td>Turned a paper process digital: digitally signed reports, audit trail, JWT with dynamic RBAC and CI/CD on GitHub Actions. Backend migrated from FastAPI to DRF.</td>
    <td>private</td>
  </tr>
  <tr>
    <td><strong>LLM-based code grader (CodeLeap)</strong></td>
    <td>AWS Lambda triggered by SQS with per-message partial failure, LiteLLM, Secrets Manager and OIDC deploys. Accuracy benchmark of the LLM against human reviewers.</td>
    <td>private</td>
  </tr>
  <tr>
    <td><strong>Legal AI platform (Dizevolv)</strong></td>
    <td>Scans public sources, screens the opportunities and generates PDF dossiers composed by an LLM with RAG (Django, Celery, pgvector).</td>
    <td>private</td>
  </tr>
  <tr>
    <td><strong>Bonding</strong></td>
    <td>Social connection app: Django + Channels (WebSocket), presence in Redis, Stripe and face verification with AWS Rekognition. React web frontend and Expo mobile app.</td>
    <td><a href="https://github.com/LouisCharlles/bonding">backend</a> · <a href="https://github.com/LouisCharlles/soul-match-glide">web</a></td>
  </tr>
  <tr>
    <td><strong>Autoescola Bless</strong></td>
    <td>Landing page in React + Tailwind CSS, live in production.</td>
    <td><a href="https://autoescola-bless.com.br">site</a></td>
  </tr>
</table>

<h2>🌟 GitHub stats</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LouisCharlles&theme=tokyonight&layout=compact&custom_title=Languages&langs_count=9" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api?username=LouisCharlles&theme=transparent&bg_color=353D41&border_color=123547&show_icons=true&icon_color=EB9326&title_color=EB9326&text_color=FFF&hide_title=true&hide=stars&rank_icon=github" alt="GitHub Stats"/>
</p>

<h2>📚 Certifications</h2>

<ul>
  <li><strong>Django Web Framework</strong> and <strong>Django REST Framework</strong></li>
  <li><strong>Python 3</strong>: from beginner to advanced (171h)</li>
  <li><strong>Origamid</strong>: Complete React, Complete JavaScript ES6+ and Front-End/UX/UI (260h)</li>
  <li><strong>Design Patterns in Java</strong>: from GoF to Spring</li>
  <li><strong>Santander Bootcamp</strong>: Java Back-End (87h)</li>
  <li><strong>EF SET</strong>: English C1 (70/100)</li>
</ul>

<h2>💪 Final message</h2>
<p>
  <strong>Stay strong and keep climbing the mountain: the real joy is in the climb, not at the summit. 🌄</strong>
</p>

<h2>💻 Get in touch</h2>
<a href="https://www.linkedin.com/in/luiscarlosmoreira">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://github.com/LouisCharlles">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="mailto:luiscmacedo84@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>
<a href="https://wa.me/559884022032">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
</a>
