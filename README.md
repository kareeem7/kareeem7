# Kareem Mohamed

Frontend developer, Menoufia (Egypt). I build web apps for Arabic-speaking users — React,
JavaScript and Supabase, mostly without a build step.

Four public projects. Two you can open in the browser right now.

📧 kemo8298@gmail.com · [LinkedIn](https://www.linkedin.com/in/kareem-mohamed-156176180)

---

## RŪH — a working storefront (React)

[**kareeem7.github.io/ruh-**](https://kareeem7.github.io/ruh-/) · [source](https://github.com/kareeem7/ruh-)

A clothing store for a made-up Cairo brand: 24 products, filters, cart, wishlist, compare,
3-step checkout with six payment methods, accounts, Arabic/English with an RTL flip, dark mode,
currency switcher.

React 18 and `htm` loaded from a CDN, so there's no bundler — the whole store is a folder you
can open with a double click. Being able to see the code that renders a page without a build
tool was worth more to me than the usual setup.

## MADAR — open it and start typing

[**kareeem7.github.io/madar**](https://kareeem7.github.io/madar/) · [source](https://github.com/kareeem7/madar)

Tasks, a focus timer and habit tracking. Arabic and English, installable as a PWA, keeps
working with the connection off.

No backend and no build step, so the state lives on the device. That makes the boring parts
matter more than the features: a migration step so an update never eats someone's data, weekly
local backups, and cross-tab sync so two open tabs don't overwrite each other.

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

## What I'm working on

TypeScript, and moving from React-by-CDN to a real toolchain — Vite, proper modules, component
tests. I've built enough with React to know the state model; what I haven't done is the part
every job listing assumes: a typed codebase that builds.

---

**Tools I use:** JavaScript, React, Supabase, HTML/CSS, Tailwind, Git, Cloudflare Workers,
Playwright, Figma. Service workers, RLS policies, accessibility.
