<h1 align="center">Hey, I'm Aayam Sinha 👋</h1>

<p align="center">
  <b>Full Stack & Backend Engineer</b> · New Delhi, India<br/>
  Full Stack Developer · Building production-grade web apps · Open to SDE / Full Stack / Backend roles
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aayam-sinha/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat-square&logo=linkedin" alt="LinkedIn"/></a>
  <a href="mailto:sinhaaayam12@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hi-ea4335?style=flat-square&logo=gmail" alt="Email"/></a>
  <a href="https://github.com/Thryyve"><img src="https://img.shields.io/badge/GitHub-Thryyve-181717?style=flat-square&logo=github" alt="GitHub"/></a>
  <img src="https://komarev.com/ghpvc/?username=Thryyve&style=flat-square&color=6e40c9" alt="Profile views"/>
</p>

---

## About me

I'm a final year Computer Science student who builds full-stack and backend systems end-to-end — from database schema to deployed product. I care about clean architecture, real authentication flows, and shipping things that actually work in production.

- 🔭 Currently building: AI-powered SaaS tools and real-time collaboration apps
- 🌱 Exploring: system design, distributed systems, and backend scalability
- 💬 Ask me about: Next.js, Node.js, PostgreSQL, REST API design, real-time systems with Socket.io
- 📫 Reach me: **sinhaaayam12@gmail.com**
- ⚡ Fun fact: I am a code archaeologist: I dig through old code and regret it.

---

## 🛠️ Tech stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599c?style=flat-square&logo=cplusplus&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-ff6f00?style=flat-square)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Databases & ORM**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47a248?style=flat-square&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ecf8e?style=flat-square&logo=supabase&logoColor=white)

**DevOps & Tools**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46e3b7?style=flat-square&logo=render&logoColor=black)
![Git](https://img.shields.io/badge/Git-f05032?style=flat-square&logo=git&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3e67b1?style=flat-square)

---

## 🚀 Featured projects

### 🧠 [ResumeIQ](https://github.com/Thryyve/resumeiq) — AI Resume Analyzer SaaS
> Paste your resume + job description → get an instant match score, skill gap report, and ATS keywords

Built a full SaaS with a **credit system** (free: 3 analyses, Pro: unlimited via ₹499 Razorpay payment), **JWT auth** with role separation (user/admin), and an **admin panel** tracking platform-wide revenue and usage. AI analysis is powered by OpenRouter and returns structured JSON — score, strengths, gaps, and keyword suggestions. Dashboard includes a Recharts trend chart for match score history.

`Next.js 14` · `TypeScript` · `PostgreSQL` · `Prisma` · `Supabase` · `NextAuth.js` · `OpenRouter API` · `Razorpay` · `Tailwind CSS`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-resumeiq--phi.vercel.app-000?style=flat-square&logo=vercel)](https://resumeiq-phi.vercel.app)
[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Thryyve/resumeiq)

---

### 📋 [Hudo](https://github.com/Thryyve/hudo) — Real-time Collaborative Kanban
> Team task manager with live drag-and-drop boards, workspace roles, and cross-client sync

Architected a **two-server deployment** — Next.js on Vercel and a standalone Socket.io server on Render — with board-scoped rooms for targeted real-time events. Implemented `@dnd-kit` for drag-and-drop with cross-list card moves, **OAuth via Auth.js v5** (GitHub + Google) with Prisma-backed sessions, and a full RBAC system (Owner / Admin / Member) with invite-by-email. All socket payloads validated with Zod 4.

`Next.js 16` · `React 19` · `TypeScript` · `Socket.io` · `PostgreSQL` · `Prisma` · `Auth.js v5` · `dnd-kit` · `Zod` · `shadcn/ui`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-hudo.vercel.app-000?style=flat-square&logo=vercel)](https://hudo.vercel.app)
[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Thryyve/hudo)

---

### 💼 [HireFlow](https://github.com/Thryyve/hireflow) — Full-Stack Job Portal with ATS
> Job board where companies post roles and candidates apply — with a full ATS status pipeline

Built a **role-based system** separating company and candidate flows end-to-end — companies post jobs, review applicants, and move them through a pipeline (`applied → reviewed → shortlisted → rejected`); candidates browse, apply, and track status live. Custom JWT middleware enforces role checks on every protected route. Separated frontend (Vercel) and backend (Render) with a clean Express REST API and Mongoose models.

`React 19` · `Node.js` · `Express` · `MongoDB Atlas` · `Mongoose` · `JWT` · `bcryptjs` · `Tailwind CSS`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-job--portal--six--opal.vercel.app-000?style=flat-square&logo=vercel)](https://job-portal-six-opal.vercel.app)
[![Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/Thryyve/hireflow)

---

## 📊 GitHub stats

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Thryyve&no-frame=true&no-bg=true&margin-w=6&column=6" alt="GitHub trophies"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Thryyve&layout=compact&hide_border=true&langs_count=6&theme=default" alt="Top languages"/>
</p>

---

## 🟢 Open to work

I'm actively looking for full-time roles — SDE, Full Stack Engineer, or Backend Engineer. I'm comfortable with the full product lifecycle: schema design, API development, auth, payments, real-time systems, and deployment.

> 💬 If you're hiring or just want to talk tech — let's connect.

<p>
  <a href="https://www.linkedin.com/in/aayam-sinha/"><img src="https://img.shields.io/badge/LinkedIn-Aayam%20Sinha-0a66c2?style=flat-square&logo=linkedin" alt="LinkedIn"/></a>
  <a href="mailto:sinhaaayam12@gmail.com"><img src="https://img.shields.io/badge/Email-sinhaaayam12@gmail.com-ea4335?style=flat-square&logo=gmail" alt="Email"/></a>
</p>
