# TUFA Apps — apps.tufa.al

Faqja e aplikacioneve të TUFA Consult (katalogu, shkarkimet, privatësia dhe kushtet).

- `index.html` — katalogu i aplikacioneve
- `flota/` — faqja e Flotës (`index.html`), `privatesia.html`, `kushtet.html`, `latest.json` (versioni aktual, për përditësime automatike)
- `downloads/` — instaluesit (`Flota-Setup-x.y.z.exe`, `Flota-x.y.z.apk`)
- `assets/` — stili, ikona, pamjet

Publikohet vetë në GitHub Pages me çdo push në `main` (`.github/workflows/pages.yml`). Domaini: `CNAME` = `apps.tufa.al`
(rekord DNS: `CNAME apps → klajditufa.github.io`).

Version i ri: ndërto instaluesit, kopjoji te `downloads/`, përditëso linket dhe madhësitë te `flota/index.html` dhe `flota/latest.json`, push.
