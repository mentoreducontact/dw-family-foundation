# DW Family Foundation — Psychological Sub-Health (心理亚健康)

**Live:** `https://mentoreducontact.github.io/dw-family-foundation/` after enabling GitHub Pages (main branch / root). Fully static, no server, GitHub history = audit trail.

## Mission — No longer TBD

**DW Family Foundation helps modern people improve psychological sub-health (心理亚健康)** — the gray zone before diagnosis: poor sleep, 3pm crash, doomscrolling, irritability, rumination, Sunday scaries.

We work with three groups:
- **Workers / 打工人** (25-45 tech) — burnout prevention
- **Students / 学生** — exam anxiety, transition stress
- **Little kids 3-8 / 小朋友** — emotional literacy via storytelling

**How:** not therapy. Education + practice.

## Three Pillars (concrete)

1. **Move & Mood Lab (运动与激素)** — weekly runs, strength, breathwork. Teaches hormone science: cortisol ↓ 15-25% after 30min Zone 2, endorphin + anandamide runner's high, serotonin from rhythmic movement, BDNF for memory.

2. **Trail Together (户外联结)** — monthly hikes, nature therapy. Stanford 90-min walk reduces rumination (Bratman 2015). Attention Restoration Theory. No-work-talk hour, family-friendly.

3. **Little & Big Minds** — 
   - Little Wonderers 3-8: feelings wheel (中英双语), Daily Wonder podcast tie-in
   - Classroom Calm: exam toolkit (box breathing, 5-4-3-2-1, Pomodoro+move)
   - Work Well: tech burnout vs depression, manager training

Inspired by: Active Minds (peer), The Jed Foundation (transitions), Mind.org.uk (science translation), Bring Change 2 Mind (anti-stigma), Child Mind Institute (kids).

## Site Map

- `index.html` — hero "From burnout to belonging / 心理亚健康不是病，是信号", pillars, stats, journal preview
- `about.html` — Alan & Jacqueline story, why sub-health, principles small/science/community
- `programs.html` — 6 programs grid
- `programs/move-mood.html`, `trail-together.html`, `little-wonderers.html`, `classroom-calm.html`, `work-well.html`, `science-stories.html`
- `articles.html` — journal index
- `articles/2026-07-21-launch.html` — updated manifesto
- `articles/mental-subhealth-101.html` — 什么是心理亚健康自查
- `articles/exercise-is-medicine.html` — 运动是天然抗抑郁药
- `articles/hiking-stops-rumination.html` — 为什么爬山关掉脑内小剧场
- `articles/kids-emotions-not-tantrum.html` — 小朋友情绪不是闹脾气
- `articles/student-exam-toolkit.html` — 考试焦虑工具包
- `articles/burnout-vs-depression.html` — 职业倦怠 vs 抑郁
- `contact.html`, `donate.html`, `financials.html` — updated to mental health mission
- Legal: `privacy.html`, `donor-privacy.html`, `terms.html`, `cookie.html`, `do-not-sell.html`, `state-disclosures.html`, `accessibility.html`
- `assets/style.css` — quiet luxury design system, no framework

## Design System (keep)

- Colors: paper #FFFCF8, ink #101010, gold #C8A96A, forest #0F1912
- Fonts: Cormorant Garamond (serif), Instrument Sans
- Classes: container, eyebrow, serif, card, grid, grid-3, grid-2, pill, btn, btn-primary, hero, news, news-item, prose
- Footer must include legal links on every page — done

## Nonprofit Checklist

- EIN placeholder + 501(c)(3) pending notice
- Donor privacy: no sell/share/trade commitment
- Do Not Sell page (nonprofits exempt from CCPA but best practice)
- State disclosures (FL, NY etc)
- Financials: 990 placeholder, use of funds, open books
- Educational disclaimer: not medical advice, crisis numbers (988, 400-161-9995)

## Page Manager Workflow

```bash
# edit article
vim articles/exercise-is-medicine.html
git add .
git commit -m "update journal: exercise"
git push # Pages auto deploy
```

## Local Preview

Just open index.html or use `python -m http.server 8000` in root.

## Next

- Enable GitHub Pages in repo settings
- Add Stripe donation link in donate.html
- Pilot 3 schools for Classroom Calm, 1 park for Move & Mood
- Translate key cards to Chinese

© 2026 DW Family Foundation. Seattle, family-run. Educational only.
