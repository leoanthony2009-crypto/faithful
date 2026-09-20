# BLOOM Learning Lab 03 — Faithful Stewardship in Catholic Education

**BPLF-MC-STEW-01 v1.6 · digital edition** · Archdiocese of Port of Spain · Academic Year 2026–2027

A 45-minute self-paced micro-course for all who serve in Catholic schools. Ten interactive lessons across five movements (Receive → Discern → Serve → Witness → Account & Hand On), a six-question knowledge check, a personal when–then commitment, printable Stewardship Action Card and Certificate of Completion, and a downloadable digital badge.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The complete course — fully self-contained (fonts, badge and hero image embedded). Works offline once loaded. |
| `Letter-on-Faithful-Stewardship-in-Catholic-Education.pdf` | Source letter (Fr David S. Khan, 18 August 2026), linked from the front page. |
| `Blueprint-for-Faithful-Stewardship-2026-2027.jpg` | Blueprint poster, linked from the front page. |
| `netlify.toml` | Netlify publish directory and headers. |

## Deploy to Netlify

**Option A — from GitHub (recommended)**
1. Push this folder to a GitHub repository (see below).
2. In Netlify: *Add new site → Import an existing project → GitHub* → choose the repo.
3. Build command: leave empty. Publish directory: `.` (already set in `netlify.toml`).
4. Deploy. Every push to the default branch redeploys automatically.

**Option B — drag and drop**
1. *Add new site → Deploy manually*.
2. Drag this whole folder onto the drop zone.

## Push to GitHub

```bash
cd netlify
git init
git add .
git commit -m "Bloom Learning Lab 03 – Faithful Stewardship v1.6"
git branch -M main
git remote add origin https://github.com/<your-org>/bloom-learning-lab-03.git
git push -u origin main
```

## Updating the course

Replace `index.html` with a new export, commit and push (or redeploy manually). The PDF and poster are static and only need replacing if the documents change.

## Privacy

All learner data (name, notes, answers, quiz results) is stored only in the learner's browser (`localStorage`). Nothing is sent to any server. Learners on shared devices can clear their data from the front page.

## Browser support

Tested in Chrome (desktop and 390 px mobile). Certificate and Action Card printing use the browser's print dialog.

---
© The BLOOM Foundation · Bloom Learning Lab. Letter and Blueprint © Archdiocese of Port of Spain, reproduced with permission for formation use.
