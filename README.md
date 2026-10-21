<p align="center">
  <img src="./assets/banner.webp" alt="" width="100%">
</p>

## Hey, I'm Karthik

Full-stack developer and final-year CS student at **Amrita Vishwa Vidyapeetham** (class of '27).

I like building complete products, from the database to the last animation. Most of my work is web (React, Next.js, Angular, Node, Spring Boot), but I spend a fair amount of time outside that too: native iOS and macOS apps in Swift, backend systems in Go, ML models, and firmware for an ESP32. Right now I'm working on [Knock](https://github.com/karthikvishal-s/Knock), an iOS expense logger, and [ClimateCopilot](https://github.com/karthikvishal-s/ClimateCopilot), a retrieval pipeline over climate-adaptation research.

[Portfolio](https://karthikvishal.vercel.app) · [LinkedIn](https://www.linkedin.com/in/karthik-vishal-s-851921287/) · [Medium](https://medium.com/@karthikvishal1506) · [Email](mailto:karthikvishal1506@gmail.com)

## Experience

**Fidelity Investments** — LEAP Intern · Chennai · Summer 2026<br>
Selected for Fidelity's LEAP internship program, working with cross-functional teams on financial-technology projects.

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Knock](https://github.com/karthikvishal-s/Knock)
*Swift · SwiftUI · SwiftData · App Intents · WidgetKit*

An iOS app for logging expenses in a few seconds: double-tap the back of the phone, type the amount, pick a category. Includes Siri shortcuts, Home and Lock Screen widgets, budgets, recurring bills and charts. All data stays on the device, and it's covered by 111 unit tests.

</td>
<td width="50%" valign="top">

### [Zenith](https://github.com/karthikvishal-s/Zenith)
*Go · Gin · GORM · PostgreSQL · Docker*

A configuration and feature-flag engine. The control plane is a layered Go API with hashed API-key auth, audit logs and a global version vector, built so nodes can later sync with each other through gossip. Ships as a small distroless Docker image.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Flash Sale Engine](https://github.com/karthikvishal-s/flash-sale-engine)
*Node.js · Redis · Lua · AWS SQS · Next.js*

A backend for flash sales that never oversells. Stock is checked and decremented atomically in Redis through a Lua script, AWS SQS absorbs traffic spikes, and an idempotent worker writes orders to the database. A Next.js dashboard simulates concurrent buyers.

</td>
<td width="50%" valign="top">

### [Vigilance](https://github.com/karthikvishal-s/Vigilance)
*Python · XGBoost · FastAPI · Streamlit*

Real-time fraud detection on a dataset where fewer than 0.05% of transactions are fraudulent. An XGBoost model is served through FastAPI with a real-time feature processor, and a Streamlit dashboard monitors it live. ROC-AUC of about 0.966.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Journal](https://github.com/karthikvishal-s/Journal)
*Swift · SwiftUI · CryptoKit · LocalAuthentication*

A private journal for macOS with no network access at all. Every entry is encrypted with AES-GCM using a key derived from your passcode, with optional Touch ID. A test scans every byte on disk to make sure no plaintext is ever written.

</td>
<td width="50%" valign="top">

### LithoFlow — [Firmware](https://github.com/karthikvishal-s/LithoFlow-Firmware) · [Model](https://github.com/karthikvishal-s/LithoFlow-EdgeML)
*C · ESP32 · TensorFlow Lite · Next.js*

A smart water bottle. A custom driver reads a load cell, and a small neural network running on the ESP32 itself tells real sips apart from bumps and sloshes. Readings are sent to a Next.js API.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [TealSlate](https://github.com/karthikvishal-s/TealSlate) · [Live](https://teal-slate.vercel.app)
*React · GSAP · Lenis · Motion · Tailwind*

A landing site for a creative studio, built around scroll-driven motion: a showreel that plays inside the headline's letters, photos that come into focus as you scroll, and full support for reduced-motion settings.

</td>
<td width="50%" valign="top">

### [Fabergé](https://github.com/karthikvishal-s/Faberge)
*Next.js · Flask · Gemini · Spotify API*

Turns a ten-question mood quiz into a Spotify playlist. Gemini picks the songs, concurrent Spotify lookups cut response time by about 80%, and it supports 7+ languages, including Hindi, Tamil and Telugu.

</td>
</tr>
</table>

### More projects

| Project | Description | Built with |
|:--|:--|:--|
| [ClauseAI](https://github.com/karthikvishal-s/ClauseAI) · [Live](https://clauseai.vercel.app) | Explains the important clauses in legal contracts using GenAI | Next.js, FastAPI, Gemini, Supabase |
| [SyncHRMS](https://github.com/karthikvishal-s/SyncHRMS) | Employee management system | Angular, Spring Boot, MySQL |
| [Le Marché](https://github.com/karthikvishal-s/Le-Marche-Frontend) | E-commerce app with customer and product management | Angular, Spring Boot, Oracle DB |
| [Vanguard](https://github.com/karthikvishal-s/Vanguard) | Messaging platform with role-based access, encryption and digital signatures | React, Node.js, JWT, node-forge |
| [PatternSlayer](https://github.com/karthikvishal-s/PatternSlayer) · [Live](https://shapesense.vercel.app) | Pattern-recognition game designed for autistic children | React, TypeScript, Framer Motion |
| [The Raven's Roost](https://github.com/karthikvishal-s/The-Ravens-Roost) · [Live](https://varys.vercel.app) | Social network for Game of Thrones fans | Next.js, NextAuth, MongoDB |
| [Movie Recommender](https://github.com/karthikvishal-s/Recommendation_System) · [Live](https://movie-recommendation-11.streamlit.app) | Collaborative-filtering recommendations on MovieLens | Python, scikit-learn, Streamlit |
| [Pensieve](https://github.com/karthikvishal-s/Pensieve) · [Live](https://thepensieve.vercel.app) | Community-curated book collection | MongoDB, Express, React, Node.js |
| [UnitEd](https://github.com/karthikvishal-s/UnitEd) | Mega Hackathon 2025 entry: a safe space for students dealing with anxiety | React, Firebase |

## Stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=ts,js,py,go,java,swift,cpp,c" alt="TypeScript, JavaScript, Python, Go, Java, Swift, C++, C">

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,angular,vue,tailwind,vite" alt="React, Next.js, Angular, Vue, Tailwind CSS, Vite">

**Backend**
<br>
<img src="https://skillicons.dev/icons?i=nodejs,express,spring,fastapi,flask,redis,rabbitmq" alt="Node.js, Express, Spring, FastAPI, Flask, Redis, RabbitMQ">

**Data, cloud and DevOps**
<br>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,supabase,firebase,aws,gcp,docker,kubernetes,githubactions" alt="PostgreSQL, MySQL, MongoDB, Supabase, Firebase, AWS, GCP, Docker, Kubernetes, GitHub Actions">

**Machine learning and embedded**
<br>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,arduino" alt="PyTorch, TensorFlow, scikit-learn, Arduino">

## GitHub

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile/stats-dark.svg">
  <img alt="GitHub stats" src="./profile/stats-light.svg">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile/langs-dark.svg">
  <img alt="Most used languages" src="./profile/langs-light.svg">
</picture>

---

Always happy to talk about interesting problems. The fastest way to reach me is [email](mailto:karthikvishal1506@gmail.com).
