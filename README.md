<div align="center">

# Hi there, I'm Maikel Hernández 👋

### 💻 Full Stack Developer · React · TypeScript · NestJS
**Building AI-powered products and reliable backends · Computer Engineering @ TEC Costa Rica** 🇨🇷

[![Portfolio](https://img.shields.io/badge/Portfolio-maikel--portafolio-6E56CF?style=for-the-badge&logo=vercel&logoColor=white)](https://maikel-portafolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maikel%20Hernández-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maikel-hernández-ruiz-539004165)
[![Email](https://img.shields.io/badge/Email-maikelhernandezr4201%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maikelhernandezr4201@gmail.com)

</div>

---

## 🚀 About Me

- 💻 **Full Stack Developer** - React 19 + strict TypeScript on the frontend, NestJS + SQL Server on the backend
- 🤖 I build **AI-powered features**: RAG systems with pgvector, Anthropic Claude SDK (tool use), Gemini API, SSE streaming
- ⚙️ I care about **production-grade backends**: idempotency, at-least-once delivery, HMAC signing, retries with backoff, k6 load testing
- 🏗️ Shipped **60+ user stories** on a real SaaS platform (microservices on Azure Kubernetes Service)
- 📜 Finishing **Computer Engineering** at Tecnológico de Costa Rica (TEC)
- 🌎 Based in Costa Rica 🇨🇷 · Working remotely · Spanish (native) / English (advanced)

## 🛠️ Languages and Tools

<div align="center">

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,ts,js,vite,tailwind,html,css&perline=7)](https://skillicons.dev)

**Backend & Data**

[![Backend](https://skillicons.dev/icons?i=nestjs,nodejs,postgres,supabase,firebase,py,java&perline=7)](https://skillicons.dev)

**DevOps & Cloud**

[![DevOps](https://skillicons.dev/icons?i=docker,kubernetes,azure,nginx,vercel,git,github&perline=7)](https://skillicons.dev)

</div>

## 📌 Featured Projects

### [DocuMind](https://github.com/MaikelHR/documind) - AI document assistant with verifiable citations *(live in production)*

> Full **RAG pipeline** end-to-end: Gemini embeddings → cosine similarity ranking (pgvector) → token-by-token **SSE streaming** with live citation markers. Upload your own PDFs and they compete in the same ranking as the corpus, and every citation highlights the exact original passage.
>
> **Stack:** React 19 · TypeScript · Vite · Tailwind · Node serverless (Vercel) · Supabase (PostgreSQL + pgvector) · Gemini API
>
> 🔗 **[Try it live →](https://documind-lake.vercel.app)**

### [Hookwire](https://github.com/MaikelHR/Hookwire) - Webhook delivery service with retries and HMAC signing *(live in production)*

> A reliable webhook pipeline with **no Redis or broker**: PostgreSQL is the queue, claimed with `FOR UPDATE SKIP LOCKED` so concurrent workers never deliver the same event twice. Exponential backoff with dead-letter and replay, **Stripe-style HMAC signatures** (constant-time verify), and **at-least-once** semantics with idempotency. Validated with k6 load tests against the live deploy.
>
> **Stack:** React 19 · TypeScript · Vite · Tailwind · Node serverless (Vercel) · Neon PostgreSQL · TanStack Query · k6
>
> 🔗 **[Try it live →](https://hookwire.vercel.app)**

### [Vision Live](https://github.com/MaikelHR/vision-live) - Real-time object detection in the browser *(live)*

> On-device ML with **no backend and no API keys**: opens your webcam and runs an object detection model (YOLOS, 80 COCO classes) on every frame, drawing boxes, labels and confidence over the live video. All compute happens on the user's machine via **Transformers.js on ONNX Runtime**, with **WebGPU** acceleration and a fallback to WebAssembly. The model downloads once and is cached, so it works offline afterwards, and camera frames never leave the device, so privacy comes from the architecture itself.
>
> **Stack:** React · TypeScript · Vite · Tailwind · Transformers.js · ONNX Runtime · WebGPU (WASM fallback) · Canvas 2D
>
> 🔗 **[Try it live →](https://vision-live.vercel.app)**

### [Cristales de la Cueva](https://github.com/MaikelHR/cristales-de-cueva) - Pixel-art platformer on a hand-rolled engine *(live)*

> A browser platformer with metroidvania touches, built to learn game dev from the ground up. Custom engine with a **fixed-timestep loop** (accumulator locked to 60 steps/s), so the physics feel the same on any machine regardless of screen frame rate. **Every asset is drawn in code**: each sprite is a pixel grid with its palette, the atmosphere (light shafts, embers, fog, parallax) is generated at runtime, and the sound effects are synthesized with the Web Audio API. No external files at all. Careful **game feel** (coyote time, jump buffering, hit-stop, screen shake), keyboard and gamepad with adaptive on-screen prompts, and a full game loop with rooms, unlockable abilities, a boss, localStorage records and a speedrun timer. Production build weighs ~14 kB gzip with zero third-party dependencies.
>
> **Stack:** TypeScript · Vite · HTML5 Canvas · Web Audio API · Gamepad API · Vercel
>
> 🔗 **[Try it live →](https://cristales-de-cueva.vercel.app)**

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=MaikelHR&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&disable_animations=true" alt="GitHub Stats" height="165">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MaikelHR&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&disable_animations=true" alt="Top Languages" height="165">

<img src="https://streak-stats.demolab.com?user=MaikelHR&theme=tokyonight&hide_border=true&disable_animations=true" alt="GitHub Streak" height="165">

</div>

---

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote">

![Profile Views](https://komarev.com/ghpvc/?username=MaikelHR&color=6E56CF&style=flat-square&label=Profile+views)

</div>
