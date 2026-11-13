# Kareem Mohamed

Frontend developer, Menoufia (Egypt). I build web apps for Arabic-speaking users —
two of them are public, and both are used by real people, not just deployed.

📧 kemo8298@gmail.com · [LinkedIn](https://www.linkedin.com/in/kareem-mohamed-156176180)

---

## Clinic management system

[github.com/kareeem7/clinic](https://github.com/kareeem7/clinic) ·
[staging build](https://clinic-staging.kemo8298.workers.dev) (login required — demo account on request)

Doctors here work on bad internet. It drops in the middle of a patient visit, so the app had
to keep working anyway: writes are queued in the browser and sync when the connection comes
back. The data side is Supabase, and every table has row-level security, so one clinic can't
read another clinic's patients even by calling the API directly. The SQL schema is kept out
of the published bundle; only the public anon key ships to the browser.

Vanilla JavaScript, 30 modules, no framework. 41 test files covering the main flows.

## Menhag — teacher management platform

[github.com/kareeem7/teaching-wep](https://github.com/kareeem7/teaching-wep)

Teachers manage students, groups, attendance, grades and exams in one place. Static-first
front end with a Supabase layer. ESLint, Stylelint, HTMLHint, unit tests and Playwright are
wired into the repo so nothing lands without passing.

## What I'm learning

React and TypeScript. I'm rebuilding the clinic dashboard in both — not because the vanilla
version doesn't work, but because I want to know where a framework actually pays for itself
and where it just adds weight. I'll write down what I find.

---

**Tools I use:** JavaScript, Supabase, HTML/CSS, Tailwind, Git, Cloudflare Workers,
Playwright, Figma. Service workers, RLS policies, accessibility.
