<h1 align="center">Hi 👋, I'm Hüseyin Samet Çıkrıkcı</h1>

<p align="center">
  <a href="mailto:hsamet.cikrikci@gmail.com">
    <img src="https://img.shields.io/badge/Email-hsamet.cikrikci%40gmail.com-555?style=flat&logo=gmail&logoColor=white" />
  </a>
    
  <a href="https://codepen.io/sametcikrikci" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/CodePen-sametcikrikci-000?style=flat&logo=codepen&logoColor=white" />
  </a>
  
   <a href="https://www.linkedin.com/in/huseyin-samet-cikrikci" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/LinkedIn-H%C3%BCseyin%20Samet%20%C3%87%C4%B1kr%C4%B1kc%C4%B1-0A66C2?style=flat&logo=linkedin&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-LLM%20Apps%20%26%20System%20Architecture-111?style=flat" />
  <img src="https://img.shields.io/badge/Prompt%20Engineering-Advanced-111?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/System%20Architecture-Event--Driven-111?style=flat&logo=architecture&logoColor=white" />
</p>

---

## ⚡ 2026 — Focus
- **Prompt Engineering**: tool-calling, RAG, agent tasarımı, prompt kontratları, evaluation (eval), guardrails
- **System Architecture**: event-driven tasarım, kuyruk/messaging, caching, ölçeklenebilir servisler
- **Cross-platform**: **Tauri + Rust** (performans/footprint) + gerektiğinde **Electron** (hızlı prototip / plugin ekosistemi), **Swift** (native macOS), **.NET MAUI** (Windows)

> Hedef: “demo değil”, **production mantığıyla çalışan** sistemler.

---

## 🧠 Prompt Engineering
- **Prompt Contract**: giriş/çıkış şeması, JSON schema, tool parametre disiplini  
- **RAG Kalite**: chunking, kaynak güvenilirliği, hallucination azaltma, cite/trace yaklaşımı  
- **Agent Tasarımı**: plan→execute döngüsü, fail-safe fallback, retry/backoff, rate-limit farkındalığı  
- **Eval Mindset**: golden set + regresyon testleri, prompt versiyonlama, ölçülebilir kalite

**Ayrışma noktası:** “prompt yazmak” değil, **promptu ürünleştirmek** (ölçülebilir + sürdürülebilir).

---

## 🏗️ System Architecture
- **Event-driven**: RabbitMQ, idempotency, retry policy, dead-letter queue
- **Caching**: Redis (cache-aside / write-through), TTL stratejileri, rate limiting
- **API tasarımı**: versioning, backward compatibility, contract-first düşünce
- **Observability**: log/metric/trace, latency budget, backpressure
- **Üretim disiplini**: config/secrets, environment ayrımı (dev/stage/prod), CI/CD

> “Nerede patlar?” sorusunu sormayan mimari, mimari değildir.

---

## 🛠️ Currently Working On
| Project | What it is | Stack | Architecture focus | Status |
|---|---|---|---|---|
| **LLM Workspace (RAG + Tools)** | Not/knowledge → RAG → tool-based action | Next.js, React, Tailwind, shadcn/ui | prompt contracts, eval, guardrails | WIP |
| **Async Job Pipeline** | Queue tabanlı worker sistemi | RabbitMQ, Redis | idempotency, retry/backoff, DLQ | WIP |
| **Local-first Desktop App** | Hafif, hızlı cross-platform desktop | Tauri, Rust (+ Swift edge) | IPC, storage, updater, security baseline | WIP |

---

## 🧩 Tools & Technologies (Learning / Using)

### Frontend
<p align="left">
  <a href="https://react.dev/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React" width="45" height="45"/></a>
  <a href="https://nextjs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" alt="Next.js" width="45" height="45"/></a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="45" height="45"/></a>
  <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" width="45" height="45"/></a>
  <a href="https://vuejs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg" alt="Vue.js" width="45" height="45"/></a>
  <a href="https://www.chartjs.org" target="_blank" rel="noreferrer"><img src="https://www.chartjs.org/media/logo-title.svg" alt="Chart.js" width="80" height="45"/></a>
  <a href="https://ui.shadcn.com/" target="_blank" rel="noreferrer"><img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white" alt="shadcn/ui" height="45"/></a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" alt="TypeScript" width="45" height="45"/></a>
</p>

### Backend / Automation
<p align="left">
  <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" width="45" height="45"/></a>
  <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" alt="Django" width="45" height="45"/></a>
  <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" alt="Flask" width="45" height="45"/></a>
  <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/selenium/selenium-original.svg" alt="Selenium" width="45" height="45"/></a>
  <a href="https://github.com/puppeteer/puppeteer" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/pptrdev/pptrdev-official.svg" alt="Puppeteer" width="45" height="45"/></a>
</p>

### Database / Messaging
<p align="left">
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="45" height="45"/></a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="MySQL" width="45" height="45"/></a>
  <a href="https://redis.io/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" alt="Redis" width="45" height="45"/></a>
  <a href="https://www.rabbitmq.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rabbitmq/rabbitmq-original.svg" alt="RabbitMQ" width="45" height="45"/></a>
  <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="45" height="45"/></a>
</p>

### Cross-platform / Native
<p align="left">
  <a href="https://www.rust-lang.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" alt="Rust" width="45" height="45"/></a>
  <a href="https://tauri.app/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tauri/tauri-original.svg" alt="Tauri" width="45" height="45"/></a>
  <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/swift/swift-original.svg" alt="Swift" width="45" height="45"/></a>
  <a href="https://www.electronjs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/electron/electron-original.svg" alt="Electron" width="45" height="45"/></a>
  <a href="https://nodejs.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" alt="Node.js" width="45" height="45"/></a>
</p>

### DevOps / Tools
<p align="left">
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" width="45" height="45"/></a>
  <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" width="45" height="45"/></a>
  <a href="https://postman.com" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" width="45" height="45"/></a>
  <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" alt="Bash" width="45" height="45"/></a>
  <a href="https://www.linux.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" alt="Linux" width="45" height="45"/></a>
  <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" width="45" height="45"/></a>
</p>

### Design / 3D / Game Dev
<p align="left">
    <a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg" alt="Figma" width="45" height="45"/></a>
    <a href="https://www.adobe.com/products/illustrator.html" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/illustrator/illustrator-plain.svg" alt="Illustrator" width="45" height="45"/></a>
    <a href="https://www.adobe.com/products/photoshop.html" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/photoshop/photoshop-plain.svg" alt="Photoshop" width="45" height="45"/></a>
    <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/xd/xd-plain.svg" alt="Adobe XD" width="45" height="45"/></a>
    <a href="https://www.blender.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/blender/blender-original.svg" alt="Blender" width="45" height="45"/></a>
    <a href="https://unity.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/unity/unity-original.svg" alt="Unity" width="45" height="45"/></a>
    <a href="https://www.unrealengine.com/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/unrealengine/unrealengine-original.svg" alt="Unreal Engine" width="45" height="45"/></a>
  </p>

### Hardware
<p align="left">
    <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" width="45" height="45"/></a>
</p>

---

## 🚀 What I’m building / exploring
- **LLM destekli üretkenlik**: not/knowledge → RAG → action (tool-based)
- **Event-driven backend**: job queue + cache + API (retry/idempotency/DLQ mantığıyla)
- **Local-first cross-platform**: Tauri ile hızlı, küçük, native hissi veren app’ler
