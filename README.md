# Profile README — نسخة بصوت بشري

> بديل للنسخة اللي نزلت. نفس الحقائق، بس مكتوبة زي ما مهندس بيتكلم في مقابلة — مش زي ما نموذج لغوي بيكتب.
> **الطريقة:** افتح `github.com/kareeem7/kareeem7` → القلم ✏️ → امسح الكل → الصق → Commit.

---

```md
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
```

---

## الفرق بين النسختين — وليه دي أهم

| النسخة الحالية (اللي نزلت) | النسخة دي |
|---|---|
| ٥ بوليتس بنفس الشكل بالظبط: **عنوان عريض** — شرطة — شرح | فقرات عادية بأطوال مختلفة |
| `—` (em dash) ١٢ مرة | مرة واحدة |
| emoji في كل عنوان (🩺 📚) | مفيش |
| شارات shields.io (٦ صور) | مفيش — شكلك مش محتاجها |
| «so a doctor isn't blocked when the connection drops mid-visit» | «It drops in the middle of a patient visit, so the app had to keep working anyway» |
| «if a project can't explain itself in 30 seconds, it isn't finished» | اتمسحت — حكمة مصطنعة |
| «Currently deepening:» | «What I'm learning» |

**ليه ده مهم:** الـ recruiter شاف ٥٠ بروفايل في يومه كلهم بنفس الإيقاع (بوليت، شرطة، شرح، بوليت، شرطة، شرح). لما يشوف السادس بنفس الشكل، دماغه بتقول «AI» وبيقلب. مش لأن الـ AI حرام — لأن ده معناه إنه مش هيعرف يقيس إيه اللي إنت فاهمه فعلاً، فهو بيسيبك ويروح لواحد شكله أوضح.

**النسخة الجديدة فيها تفصيل واحد مميز محدش هيكتبه بالنيابة عنك:** «It drops in the middle of a patient visit». دي جملة حد عاش المشكلة. متغيّرهاش لجملة أعمّ.
