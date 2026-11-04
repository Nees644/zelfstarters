# Zelfstarters

Zelfstartregister voor zelfstandige professionals. Statische site, gehost op Vercel.

## Werkregel Vercel

`vercel.json` heeft `cleanUrls: true`. Een herschrijfregel (`rewrites`) naar
een `.html`-bestand geeft daarnaast een 404. Nieuwe adressen zijn daarom altijd
echte bestanden: `/check` is `check.html`, dat met het nummer doorstuurt naar
de voorpagina (`/?nummer=ZS-2026-00001#check`). Zelfde valkuil als in
happly-scan.
