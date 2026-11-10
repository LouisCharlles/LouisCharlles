<h1 align="center">Luis Carlos Macêdo Moreira</h1>

<p align="center">
  <strong>Engenheiro de Software Full Stack</strong> · Python (Django, DRF, FastAPI) · TypeScript (Node, Deno, React) · AWS · IA aplicada
  <br/>
  São Luís, MA · Remoto · Inglês C1 (EF SET 70/100)
</p>

<p align="center">
  <img src="./imagens/Perfil_Luis_Carlos.png" alt="Luis Carlos" width="220"/>
</p>

<h2>Quem é <span style="color:#9F17ED;">Luis</span>? 💭</h2>

<p>
  Sou engenheiro de software full stack e gosto de entregar do serviço à interface: APIs em Python e TypeScript, frontends em React e infraestrutura na AWS descrita como código. Já trabalhei em três empresas, com sistemas em produção no Brasil e no Reino Unido.
</p>

<ul>
  <li>🏛️ <strong>Prefeitura de São Luís (SEMAD)</strong>, desde mai/2025: sou o principal desenvolvedor do sistema de inspeção sanitária de abatedouros (FastAPI → DRF, laudos assinados digitalmente, RBAC dinâmico e CI/CD), da sincronização de RH com Celery e do sistema de avaliação de atendimento (totem React Native + API Node + dashboard).</li>
  <li>🇬🇧 <strong>CodeLeap (Londres, remoto)</strong>, out/2025 – jun/2026: escrevi a infraestrutura AWS em Terraform, levei o avaliador de código com LLM para Lambda + SQS, acabei com timeouts 504 com Celery e paginação por keyset e escrevi mais de 170 testes.</li>
  <li>🚀 <strong>Dizevolv</strong>, ago – out/2026: construí do zero SaaS multi-tenant para os setores jurídico, previdenciário e imobiliário, com LLMs, RAG com pgvector, webhooks de WhatsApp e endpoints idempotentes.</li>
  <li>🤖 No dia a dia trabalho em esteira agêntica (ADLC) com <strong>Claude Code, Cursor e Codex</strong> sobre o <strong>GitHub Spec Kit</strong>: especificação → plano → tarefas → implementação pelo agente, com revisão humana e CI como portão de qualidade.</li>
  <li>🎓 Engenharia de Software na UNDB (2022 – 2026).</li>
</ul>

<h2>⚒ Stack</h2>

<p align="center">
  <strong>Backend</strong><br/>
  <img src="https://skillicons.dev/icons?i=py,django,fastapi,ts,nodejs,express,deno&perline=7" alt="Python, Django, FastAPI, TypeScript, Node.js, Express, Deno"/>
</p>
<p align="center">
  <strong>Dados, cloud e DevOps</strong><br/>
  <img src="https://skillicons.dev/icons?i=postgres,redis,supabase,aws,terraform,docker,githubactions,sentry,linux,git&perline=10" alt="PostgreSQL, Redis, Supabase, AWS, Terraform, Docker, GitHub Actions, Sentry, Linux, Git"/>
</p>
<p align="center">
  <strong>Frontend e mobile</strong><br/>
  <img src="https://skillicons.dev/icons?i=react,vite,tailwind&perline=3" alt="React, Vite, Tailwind CSS"/>
</p>

<table>
  <tr>
    <td><strong>Backend Python</strong></td>
    <td>Django, Django REST Framework, FastAPI, Pydantic v2, SQLAlchemy, Alembic, Celery (+ Beat), Redis, Django Channels</td>
  </tr>
  <tr>
    <td><strong>Backend TypeScript</strong></td>
    <td>Node.js, Express, Deno (Supabase Edge Functions), Zod, Vitest</td>
  </tr>
  <tr>
    <td><strong>AWS e IaC</strong></td>
    <td>Terraform, Lambda, SQS, S3, RDS PostgreSQL, Elastic Beanstalk, ALB, ElastiCache, Route 53, IAM, Secrets Manager, Docker</td>
  </tr>
  <tr>
    <td><strong>Arquitetura</strong></td>
    <td>Orientada a eventos, filas e workers, webhooks com deduplicação, idempotência, retry com backoff, multi-tenancy, RBAC, JWT, OAuth 2.0</td>
  </tr>
  <tr>
    <td><strong>Dados</strong></td>
    <td>PostgreSQL, pgvector, otimização de consultas (N+1, Exists/Subquery, Prefetch, paginação por keyset), migrations de schema e de dados</td>
  </tr>
  <tr>
    <td><strong>IA aplicada</strong></td>
    <td>LLMs (Gemini, Anthropic, LiteLLM), RAG com pgvector, agentes com ferramentas e supervisão humana</td>
  </tr>
  <tr>
    <td><strong>Frontend e mobile</strong></td>
    <td>React, TypeScript, Vite, Tailwind CSS, TanStack Query, Recharts, React Native (Expo)</td>
  </tr>
  <tr>
    <td><strong>Qualidade e CI/CD</strong></td>
    <td>GitHub Actions (testes com PostgreSQL, lint, mypy, deploy por branch, OIDC na AWS), pytest, Django TestCase, Sentry, code review</td>
  </tr>
  <tr>
    <td><strong>Dev agêntico</strong></td>
    <td>Claude Code, Cursor, OpenAI Codex, GitHub Spec Kit, AGENTS.md / CLAUDE.md</td>
  </tr>
</table>

<h2>📌 Projetos em destaque</h2>

<table>
  <tr>
    <td><strong>Avaliação do Atendimento (SEMAD)</strong></td>
    <td>Totem Android em React Native/Expo, API Node/Express + PostgreSQL e dashboard React com indicadores, gráficos e exportação em PDF/Excel. Deploy em Docker com instalador de um comando e backup diário.</td>
    <td><a href="https://github.com/LouisCharlles/avaliacao-atendimento-semad-dashboard">API + dashboard</a> · <a href="https://github.com/LouisCharlles/avaliacao-do-atendimento-semad-totem">totem</a></td>
  </tr>
  <tr>
    <td><strong>Inspeção Sanitária de Abatedouros (SEMAD)</strong></td>
    <td>Digitalizou um processo manual: laudos assinados digitalmente, trilha de auditoria, JWT com RBAC dinâmico e CI/CD no GitHub Actions. Backend migrado de FastAPI para DRF.</td>
    <td>privado</td>
  </tr>
  <tr>
    <td><strong>Avaliador de código com LLM (CodeLeap)</strong></td>
    <td>AWS Lambda acionada por SQS com falha parcial por mensagem, LiteLLM, Secrets Manager e deploy via OIDC. Benchmark de acurácia do LLM contra revisores humanos.</td>
    <td>privado</td>
  </tr>
  <tr>
    <td><strong>Plataforma jurídica com IA (Dizevolv)</strong></td>
    <td>Varre fontes públicas, faz a triagem das oportunidades e gera dossiês em PDF compostos por LLM com RAG (Django, Celery, pgvector).</td>
    <td>privado</td>
  </tr>
  <tr>
    <td><strong>Bonding</strong></td>
    <td>App social de conexões: Django + Channels (WebSocket), presença em Redis, Stripe e verificação facial com AWS Rekognition. Frontend web em React e app mobile em Expo.</td>
    <td><a href="https://github.com/LouisCharlles/bonding">backend</a> · <a href="https://github.com/LouisCharlles/soul-match-glide">web</a></td>
  </tr>
  <tr>
    <td><strong>Autoescola Bless</strong></td>
    <td>Landing page em React + Tailwind CSS, em produção.</td>
    <td><a href="https://autoescola-bless.com.br">site</a></td>
  </tr>
</table>

<h2>🌟 Status do GitHub</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LouisCharlles&theme=tokyonight&layout=compact&custom_title=Tecnologias&langs_count=9" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api?username=LouisCharlles&theme=transparent&bg_color=353D41&border_color=123547&show_icons=true&icon_color=EB9326&title_color=EB9326&text_color=FFF&hide_title=true&hide=stars&rank_icon=github" alt="GitHub Stats"/>
</p>

<h2>📚 Certificações</h2>

<ul>
  <li><strong>Django Web Framework</strong> e <strong>Django REST Framework</strong></li>
  <li><strong>Python 3</strong>: do básico ao avançado (171h)</li>
  <li><strong>Origamid</strong>: React Completo, JavaScript Completo ES6+ e Front-End/UX/UI (260h)</li>
  <li><strong>Design Patterns com Java</strong>: do GoF ao Spring</li>
  <li><strong>Bootcamp Santander</strong>: Back-End com Java (87h)</li>
  <li><strong>EF SET</strong>: inglês C1 (70/100)</li>
</ul>

<h2>💪 Minha mensagem final</h2>
<p>
  <strong>Seja forte, não pare de escalar a montanha, o verdadeiro prazer está na subida e não no topo. 🌄</strong>
</p>

<h2>💻 Conecte-se comigo</h2>
<a href="https://www.linkedin.com/in/luiscarlosmoreira">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://github.com/LouisCharlles">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="mailto:luiscmacedo84@gmail.com">
  <img src="https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail">
</a>
<a href="https://wa.me/559884022032">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
</a>
