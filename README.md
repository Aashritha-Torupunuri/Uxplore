# UXplore

A high-fidelity web platform designed to make UX education accessible and engaging for first-year students. Built as a group project for UX103 at Wilfrid Laurier University.

🔗 **[Live Demo](#)** ← paste your Vercel/Netlify link here

---

## What it does

UXplore is a virtual classroom that lets students choose how they learn — on their own schedule or in real time with an educator.

| Section | Description |
|---|---|
| **Asynchronous** | Watch topic videos and complete interactive quizzes at your own pace |
| **Synchronous** | Join live Zoom sessions, view office hours, and review the class schedule |
| **Discussion Board** | Ask questions and connect with classmates |
| **Case Study** | Sign up for the Smart Campus UX Challenge — a team-based design competition |

### Key features
- Interactive quiz engine with true/false, multiple choice, and fill-in-the-blank questions
- Instant feedback and hints on wrong answers
- Personal best scores saved per quiz (requires login)
- User authentication with login and registration
- Educator review and rating system
- Fully responsive design

---

## Built with

- [Astro](https://astro.build) — web framework
- TypeScript
- MongoDB — user auth and quiz score persistence
- Netlify — deployment and serverless middleware
- CSS (custom design system)

---

## Getting started

```bash
# Install dependencies
npm install

# Start local dev server at localhost:4321
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```

> **Note:** You'll need a MongoDB connection string. Create a `.env` file at the root with:
> ```
> MONGODB_URI=your_connection_string_here
> ```

---

## Project structure

```
/
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable UI components (Quiz, SiteNav)
│   ├── layouts/     # Page layout wrapper
│   ├── lib/         # Database, session, and validation helpers
│   ├── pages/       # Routes (index, async, sync, discussion, case-study)
│   │   └── api/     # Auth and quiz API endpoints
│   └── styles/      # Global CSS
├── astro.config.mjs
└── package.json
```

---

## Team

Built by a group of UX103 students at Wilfrid Laurier University.

---

## License

This project was created for educational purposes as part of a university course.

