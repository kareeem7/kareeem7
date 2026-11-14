# Kareem Mohamed

Frontend developer, Menoufia (Egypt). I build web apps for Arabic-speaking users.

Three of them are public. One runs a clinic's daily work; one you can open in the browser right now.

📧 kemo8298@gmail.com · [LinkedIn](https://www.linkedin.com/in/kareem-mohamed-156176180)

---

## MADAR — open it and start typing

[**kareeem7.github.io/madar**](https://kareeem7.github.io/madar/) · [source](https://github.com/kareeem7/madar)

Tasks, a focus timer and habit tracking in one place. Arabic and English, installable as a
PWA, and it keeps working with the connection off.

No backend and no build step, so the whole state lives on the device. That makes the boring
parts matter more than the features: a migration step so an update never eats someone's data,
weekly local backups, and cross-tab sync so two open tabs don't overwrite each other.

## Clinic management system

[source](https://github.com/kareeem7/clinic) · [staging](https://clinic-staging.kemo8298.workers.dev)
(login required — demo account on request)

Arabic-first clinic app: patients, appointments, measurements, lab results, nutrition plans,
and a portal where a patient follows their own readings.

The hard part was underneath. Doctors here lose connection in the middle of a visit, so writes
queue in the browser and sync when it comes back. Supabase row-level security means one clinic
can't read another's patients even by calling the API with the public key, and the schema stays
out of the published bundle. 29 policies, 34 security-definer functions, 41 test files.

## Menhag — teacher management platform

[source](https://github.com/kareeem7/teaching-wep)

Teachers run groups, attendance, grades and exams in one place. Static front end with a
Supabase layer, and nothing lands without passing ESLint, Stylelint, HTMLHint, unit tests and
Playwright.

---

## What I'm learning

React and TypeScript.

I've argued that a build step gets in the way of small apps. That was a fair argument for
something that has to open from `file://`, and it has run out. MADAR is small and has no
backend, so it's the first thing I'm porting — and I'm writing down where the framework
actually pays for itself and where it just adds weight.

---

**Tools I use:** JavaScript, Supabase, HTML/CSS, Tailwind, Git, Cloudflare Workers, Playwright,
Figma. Service workers, RLS policies, accessibility.
