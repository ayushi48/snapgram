<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:EC4899,100:06B6D4&height=200&section=header&text=📸%20Snapgram&fontSize=58&fontColor=ffffff&fontAlignY=35&desc=Create%20%E2%80%A2%20Share%20%E2%80%A2%20Explore%20%E2%80%A2%20Connect&descAlignY=58&descSize=17&animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&size=22&duration=3000&pause=1000&color=EC4899&center=true&vCenter=true&width=650&lines=Modern+Social+Media+Experience;Create+%E2%80%A2+Share+%E2%80%A2+Discover;Built+with+React+%2B+TypeScript+%2B+Appwrite" alt="Typing SVG" />

<br/><br/>

<a href="https://github.com/ayushi48/snapgram">
  <img src="https://img.shields.io/badge/📦_GitHub_Repository-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://ayushikumari.me/">
  <img src="https://img.shields.io/badge/👩‍💻_Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<br/><br/>

<img src="https://skillicons.dev/icons?i=react,typescript,appwrite,tailwind,vite&theme=dark" />

</div>

---

## 📌 Overview

**Snapgram** is a modern social media web application built with **React, TypeScript, and Appwrite**.

It provides a responsive platform for users to create and explore posts, upload images, manage profiles, and interact with social content through a clean and modern interface.

---

## ✨ Features

| 🔐 Authentication | 📝 Content | 👤 Profiles |
|:---:|:---:|:---:|
| User registration & login | Create & publish posts | User profiles |
| Protected routes | Explore posts | View user content |
| Appwrite authentication | Image uploads | Profile-based content |

| ❤️ Social | 🔎 Discovery | 📱 Experience |
|:---:|:---:|:---:|
| Like & save content | Search & explore | Responsive UI |
| Interactive posts | Discover users | Mobile friendly |

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/REACT-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/APPWRITE-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" />
<img src="https://img.shields.io/badge/TAILWIND_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/VITE-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/TANSTACK_QUERY-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
<img src="https://img.shields.io/badge/REACT_ROUTER-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white" />
<img src="https://img.shields.io/badge/ZOD-3E67B1?style=for-the-badge&logo=zod&logoColor=white" />

</div>

| Layer | Technology |
|:--|:--|
| 🎨 **Frontend** | React.js · TypeScript · Vite |
| ☁️ **Backend / BaaS** | Appwrite |
| ⚡ **Data Fetching** | TanStack React Query |
| 📝 **Forms** | React Hook Form |
| ✅ **Validation** | Zod |
| 🎨 **Styling** | Tailwind CSS |
| 🧩 **UI** | Radix UI · Lucide React |
| 🧭 **Routing** | React Router |

---

## 🏗️ Architecture

```text
                         📸 SNAPGRAM
                              │
               ┌──────────────┴──────────────┐
               │                             │
        ⚛️ React + TypeScript             ☁️ Appwrite
               │                             │
        ┌──────┼──────┐             ┌────────┼────────┐
        │      │      │             │        │        │
       🎨     🔄     🧩            🔐       🗄️       🖼️
    Tailwind  Query  Router        Auth    Database  Storage
```

---

## 📂 Project Structure

```text
snapgram/
│
├── public/
│
├── src/
│   ├── _auth/
│   │   ├── forms/
│   │   └── AuthLayout.tsx
│   │
│   ├── _root/
│   │   ├── pages/
│   │   └── RootLayout.tsx
│   │
│   ├── components/
│   │   ├── forms/
│   │   ├── shared/
│   │   └── ui/
│   │
│   ├── constants/
│   ├── context/
│   ├── hooks/
│   │
│   ├── lib/
│   │   ├── appwrite/
│   │   ├── react-query/
│   │   ├── validation/
│   │   └── utils.ts
│   │
│   ├── types/
│   ├── App.tsx
│   ├── globals.css
│   ├── main.tsx
│   └── vite-env.d.ts
│
├── .eslintrc.json
├── .gitignore
├── .prettierrc
├── components.json
├── index.html
├── package.json
├── postcss.config.cjs
├── tailwind.config.cjs
├── tsconfig.json
├── tsconfig.node.json
├── vercel.json
└── vite.config.ts
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ayushi48/snapgram.git
cd snapgram
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure Appwrite

Create an Appwrite project and configure the required project credentials and environment variables used by the application.

### 4. Start the development server

```bash
npm run dev
```

### 5. Build for production

```bash
npm run build
```

---

## 🌟 Development Highlights

- 🎯 **Type-Safe** — TypeScript-based development
- ⚡ **Server State** — TanStack React Query
- 🔐 **Authentication** — Appwrite services
- 📝 **Form Handling** — React Hook Form
- ✅ **Schema Validation** — Zod
- 🧩 **Reusable UI** — Modular React components
- 🎨 **Modern Styling** — Tailwind CSS
- 📱 **Responsive Design** — Desktop and mobile friendly
- 🧭 **Client Routing** — React Router

---

## 🗺️ Roadmap

- [ ] 💬 Comments & Replies
- [ ] 🔔 Notifications
- [ ] 👥 Follow / Unfollow
- [ ] 📩 Direct Messaging
- [ ] 🌙 Dark Mode
- [ ] 📱 Progressive Web App

---

## 👩‍💻 Author

<div align="center">

### Ayushi Kumari

**Full-Stack Developer · React Developer · Open Source Contributor**

<br/>

<a href="https://github.com/ayushi48">
<img src="https://img.shields.io/badge/GitHub-ayushi48-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/ayushi-kumari48/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://ayushikumari.me/">
<img src="https://img.shields.io/badge/Portfolio-Visit-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<br/><br/>

⭐ **If you like Snapgram, consider giving the repository a star!**

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:EC4899,100:7C3AED&height=100&section=footer" width="100%"/>

</div>
