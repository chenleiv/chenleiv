# Chen Leiv

Frontend Engineer with 4+ years of experience building web applications with Angular, React and TypeScript, moving toward application security.
Portfolio: https://chenleiv.vercel.app

Based in Tel Aviv. Dog mom to Bucky.

[![Interactive isometric room portfolio](https://raw.githubusercontent.com/chenleiv/my-portfolio/main/docs/screenshots/room-light.png)](https://chenleiv.vercel.app)

## Projects

- **Portfolio**: an isometric room you can walk around, plus a terminal you can type commands into. Next.js, React, TypeScript. [Code](https://github.com/chenleiv/my-portfolio) · [Live](https://chenleiv.vercel.app)
- **InsightDesk**: a document workspace with a chat that answers from your documents and cites its sources. React, Node.js, Express, MongoDB. [Code](https://github.com/chenleiv/insight-desk) · [Live demo](https://insight-desk-bwji.onrender.com)
- **SignalForge**: a SOC dashboard for real-time threat monitoring, alert triage and incident investigation, with role-based access control. Angular 21, FastAPI. [Code](https://github.com/chenleiv/signal-forge) · [Live demo](https://signalforge-api-ah1q.onrender.com) (the first load can take a moment while the server wakes up)

## Application security

Controls I built into InsightDesk and SignalForge:

- **CSP**: a CSP with no inline scripts, set with helmet (InsightDesk).
- **Secure sessions**: HttpOnly cookies, JWTs with HS256 pinned, and logout that ends the session on the server (InsightDesk, SignalForge).
- **Input validation**: uploads must match their file type and size limits (InsightDesk), and IP inputs must be public addresses, as an SSRF guard (SignalForge).
- **Rate limiting**: failed logins limited per address and per account (InsightDesk, SignalForge), plus daily usage limits (InsightDesk).

Knowledge and tools: OWASP Top 10, XSS, CSRF and SQL injection, Burp Suite, Linux (CLI), Python (scripting).

## Tech

- **Frontend**: Angular (Signals), React, Next.js, TypeScript, RxJS, MobX, SCSS
- **Backend and APIs**: Node.js, Express, FastAPI, REST, WebSockets, MongoDB
- **Architecture**: Nx, real-time systems, component libraries
- **AI tools**: Claude Code (agents, skills), Cursor, prompt engineering

## Links

[LinkedIn](https://www.linkedin.com/in/chen-leiv) · [Portfolio](https://chenleiv.vercel.app)
