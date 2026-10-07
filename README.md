# Noor Saqib

Final-year B.Tech CSE student (graduating 2027) | Backend and Full-Stack Developer | Bareilly, India

I build backend systems and AI-powered web applications with Node.js and MongoDB. I care most about correctness: consistent data, secure authentication, and validating what goes in and out of a system. I am looking for SDE roles in backend or full-stack development.

[LinkedIn](...) | [LeetCode](...) | [saqibsiddiqui380@gmail.com](mailto:saqibsiddiqui380@gmail.com)
---

## Projects

### PrepPilot: AI Interview Preparation Platform
[Repository](https://github.com/Noor-Saqib/PrepPilot--An-AI-Powered-Interview-Preparation-Platform) 

Takes a candidate's resume and a target job description, then generates a profile match score, skill gaps, technical and behavioral interview questions, and a preparation plan. It can also export an ATS-friendly resume as a PDF.

- Gemini API responses are validated with Zod before being stored or rendered, so malformed AI output never reaches the UI.
- PDF export is generated server-side with Puppeteer.

**Stack:** React, Node.js, Express, MongoDB, Gemini API, Zod, Puppeteer

### Advanced Banking Backend System
[Repository](https://github.com/Noor-Saqib/Advanced-Banking-Backend-System)

Backend for a banking application, built around transaction safety rather than basic CRUD.

- Ledger-based accounting: balances are calculated from ledger entries instead of being stored as a single editable number.
- Fund transfers run inside MongoDB transactions and roll back completely if any step fails.
- Idempotency keys prevent duplicate transfers when a request is retried.
- JWT authentication, bcrypt password hashing, protected routes, and transaction notifications.

**Stack:** Node.js, Express, MongoDB, Mongoose, JWT, bcrypt

### Spotify-inspired Backend
[Repository](https://github.com/Noor-Saqib/Spotify-inspired-backend-Project)

REST API for a music streaming platform with JWT authentication, MongoDB storage, and file uploads through ImageKit.

**Stack:** Node.js, Express, MongoDB, JWT, ImageKit

---

## Skills

| | |
|---|---|
| **Languages** | C++, JavaScript |
| **Backend** | Node.js, Express, REST APIs, JWT |
| **Databases** | MongoDB, Mongoose, SQL |
| **Frontend** | React, Next.js, HTML, CSS, SCSS |
| **AI** | Google Gemini API, Zod |
| **Tools** | Git, GitHub, Postman, Vercel, Render |

---

## Problem Solving

I practice data structures and algorithms in C++ and have solved 100+ problems on [LeetCode](https://leetcode.com/u/noorsaqib/).

---

## Education and Achievements

- B.Tech in Computer Science and Engineering, Shri Ram Murti Smarak College of Engineering and Technology, Bareilly (2023 to 2027). CGPA: 8.3
- Placement Representative, SRMSCET
- Semifinalist at a hackathon with LinguaLink
- IBM Virtual Internship
