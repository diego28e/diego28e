<div align="center">
  <img src="https://github.com/diego28e/diego28e/raw/main/banner.png" alt="Diego Espinosa — AI-Focused Full Stack Engineer" width="100%" />
</div>

<div align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1300&color=2DD4BF&center=true&vCenter=true&width=600&lines=AI-Focused+Full+Stack+Engineer;Founding+Engineer+%40+Idiomas+OCW;AI+tutors+%C2%B7+voice+agents+%C2%B7+RAG;I+build+AI-native+products%2C+end+to+end" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/diego28e/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:diego28e@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://academiadelcodigo.com/">
    <img src="https://img.shields.io/badge/Academia_del_C%C3%B3digo-121826?style=for-the-badge&logo=googlechrome&logoColor=C8F24E" alt="Academia del Código" />
  </a>
  <a href="https://cp.certmetrics.com/amazon/en/public/verify/credential/ab29fcec227b4dca90808ec24776dbb2">
    <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Certified Cloud Practitioner" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=diego28e&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS" alt="Profile Views" />
</div>

---

## 👋 Hey, I'm Diego

I'm an **AI-focused full stack engineer** based in Medellín, Colombia. For the last **6 years** I've been the **founding engineer** of a language-learning platform — building every system from a blank slate and keeping it online at **99.98% uptime**. These days most of my time goes into shipping **AI-native features that change how a product actually works**: AI tutors you can talk to, voice agents, RAG pipelines, and AI-generated content that's verified before anyone sees it — core capabilities, not bolt-ons.

- 🔭 &nbsp;**Currently** — Lead Engineer @ Idiomas OCW, building an AI-native LMS (NestJS · React 19 · AWS CDK)
- 🛠️ &nbsp;**Also building** — [Academia del Código](https://academiadelcodigo.com/), an AI learning platform for LLM engineering, and [Learning Kit](https://github.com/intellectif/learning-kit), an open-source learning SDK on npm that powers both platforms
- 🤖 &nbsp;**I love** — turning LLMs (Gemini, Claude, OpenAI) into real product features with LiveKit, ElevenLabs, Deepgram & pgvector
- 💬 &nbsp;**Ask me about** — AI integration, real-time voice tutors, AWS architecture, and shipping fast as a small team
- 📫 &nbsp;**Reach me** — diego28e@gmail.com · [LinkedIn](https://www.linkedin.com/in/diego28e/)

---

## 🚀 Featured Projects

<table>
  <tr>
    <td>
      <h3>🧠 Academia del Código — AI learning platform for LLM engineering <sub>— production · open code</sub></h3>
      <p>A bilingual platform that teaches developers to build LLM applications with LangChain &amp; LangGraph: a 129-lesson course where every lesson opens a <b>runnable Jupyter notebook</b> in the learner's own lab (JupyterHub), an <b>AI tutor learners can talk to</b> (streaming speech in and out), and <b>adaptive daily practice</b> — FSRS spaced repetition over a 700+ skill prerequisite graph. Its AI-written exercises are <b>proven before any learner sees them</b>: code tasks run in a gVisor sandbox (the reference must pass, a wrong version must fail), questions are answered blind by a second model, and failures are repaired from the sandbox's real output. Long jobs run on a Postgres-backed worker beyond serverless limits; videos flow through S3, MediaConvert and signed CloudFront URLs with English &amp; Spanish captions generated automatically.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Prisma_7-2D3748?style=flat-square&logo=prisma&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Claude_%C2%B7_Gemini-8E75FF?style=flat-square&logo=googlegemini&logoColor=white" />
        <img src="https://img.shields.io/badge/JupyterHub-F37626?style=flat-square&logo=jupyter&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker_%C2%B7_gVisor-2496ED?style=flat-square&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900" />
      </p>
      <a href="https://academiadelcodigo.com/"><b>Live →</b></a> &nbsp;·&nbsp; <a href="https://github.com/diego28e/script-playground"><b>Code →</b></a>
    </td>
  </tr>
  <tr>
    <td>
      <h3>🎓 Idiomas OCW — AI-Native Language Learning LMS <sub>— flagship · production</sub></h3>
      <p>A full multilingual LMS built end-to-end: self-paced courses, Stripe billing, and BigBlueButton live classrooms. Ships a <b>real-time AI Voice Tutor</b> via Gemini Live + LiveKit with server-controlled session timing, long-term memory via Zep, and a BullMQ-driven automated evaluation pipeline. Includes multimodal <b>WhatsApp AI agents</b> (sales + support) using Gemini 2.5 Flash with function-calling for live pricing, OGG voice-note transcription, and pgvector-backed RAG. An automated micro-lesson pipeline parses diarized ElevenLabs class transcripts to extract vocabulary and schedules timezone-aware WhatsApp practice sessions. Deployed on a cost-conscious single-stack AWS CDK infrastructure with zero-downtime blue-green Docker deployments behind Caddy, monitored via CloudWatch + SNS.</p>
      <p>
        <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/AWS_CDK-F90?style=flat-square&logo=amazonwebservices&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_Live-8E75FF?style=flat-square&logo=googlegemini&logoColor=white" />
        <img src="https://img.shields.io/badge/LiveKit-1FD5C7?style=flat-square&logo=livekit&logoColor=white" />
        <img src="https://img.shields.io/badge/pgvector_RAG-31648C?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/BullMQ-FF4154?style=flat-square&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      </p>
      <a href="https://www.onecultureworld.com"><b>Live →</b></a>
    </td>
  </tr>
  <tr>
    <td>
      <h3>📦 Learning Kit — open-source SDK for interactive learning <sub>— npm · MIT</sub></h3>
      <p>A <b>TypeScript-first SDK for interactive educational content</b> — a lightweight, schema-driven alternative to H5P, published on npm as five packages and running in production in both platforms above. <b>lk-core</b>: schemas, a deterministic scoring engine, rubric grading and an xAPI 1.0.3 builder, with no runtime dependencies beyond Zod. <b>lk-react</b>: accessible React 19 components (WCAG 2.2 AA), interactive video included. <b>lk-practice</b>: spaced-practice planning over a skill graph — FSRS-7 memory, Elo ability and stage ladders as pure functions of a replayable log. Plus <b>lk-azure</b> (pronunciation assessment) and <b>lk-interactive-activities</b>.</p>
      <p>
        <a href="https://www.npmjs.com/package/@intellectif/lk-core"><img src="https://img.shields.io/npm/v/@intellectif/lk-core?style=flat-square&logo=npm&label=lk-core&color=CB3837" alt="lk-core on npm" /></a>
        <a href="https://www.npmjs.com/package/@intellectif/lk-react"><img src="https://img.shields.io/npm/v/@intellectif/lk-react?style=flat-square&logo=npm&label=lk-react&color=CB3837" alt="lk-react on npm" /></a>
        <a href="https://www.npmjs.com/package/@intellectif/lk-practice"><img src="https://img.shields.io/npm/v/@intellectif/lk-practice?style=flat-square&logo=npm&label=lk-practice&color=CB3837" alt="lk-practice on npm" /></a>
        <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Zod_4-3E67B1?style=flat-square&logo=zod&logoColor=white" />
        <img src="https://img.shields.io/badge/xAPI-0B1020?style=flat-square" />
      </p>
      <a href="https://github.com/intellectif/learning-kit"><b>Code →</b></a> &nbsp;·&nbsp; <a href="https://www.npmjs.com/package/@intellectif/lk-core"><b>npm →</b></a>
    </td>
  </tr>
</table>

### More I've built

<table>
  <tr>
    <td width="50%">
      <h4>🗣️ Polyglotas <sub>— production</sub></h4>
      <p>An AI language-learning platform: <b>dictation</b>, <b>pronunciation assessment with phoneme-level feedback</b>, and <b>spontaneous AI conversation</b>, orchestrating AWS, Google Cloud &amp; Azure.</p>
      <a href="https://polyglotas.com/"><b>Live →</b></a>
    </td>
    <td width="50%">
      <h4>🎬 Cinematic GenAI Video Pipeline <sub>— GPU</sub></h4>
      <p>A GPU-backed FastAPI service on GCP that turns a scene script into a ~5-minute video with consistent recurring characters, narrated with ElevenLabs and delivered through S3 and CloudFront.</p>
      <a href="https://github.com/diego28e/ai-video-generation-pipeline"><b>Code →</b></a>
    </td>
  </tr>
</table>

---

## 🛠️ Tech I build with

**AI & ML**

![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75FF?style=flat-square&logo=googlegemini&logoColor=white)
![Anthropic Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-1FD5C7?style=flat-square&logo=livekit&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=flat-square&logo=elevenlabs&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square&logoColor=black)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![RAG / pgvector](https://img.shields.io/badge/RAG_%2F_pgvector-31648C?style=flat-square&logo=postgresql&logoColor=white)

**Languages & Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-F90?style=flat-square&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1A1A1A?style=flat-square&logo=linux&logoColor=FCC624)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-nine-dusky-92.vercel.app/api?username=diego28e&show_icons=true&theme=tokyonight&bg_color=0A0E1A&title_color=2DD4BF&icon_color=A78BFA&text_color=CBD5E1&border_color=1e293b&rank_icon=github&include_all_commits=true&hide_border=false" alt="Diego's GitHub Stats" height="180" />
  <img src="https://github-readme-stats-nine-dusky-92.vercel.app/api/top-langs/?username=diego28e&layout=compact&theme=tokyonight&bg_color=0A0E1A&title_color=2DD4BF&text_color=CBD5E1&border_color=1e293b&hide_border=false" alt="Most Used Languages" height="180" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=diego28e&theme=transparent&background=0A0E1A&ring=2DD4BF&fire=A78BFA&currStreakLabel=2DD4BF&sideLabels=CBD5E1&currStreakNum=F1F5F9&sideNums=F1F5F9&dates=64748b&border=1e293b" alt="GitHub Streak" />
</div>

---

<div align="center">
  <i>Building AI features that change how a product works — let's talk.</i><br/>
  <b><a href="mailto:diego28e@gmail.com">diego28e@gmail.com</a></b>
</div>

<!---
diego28e/diego28e is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
