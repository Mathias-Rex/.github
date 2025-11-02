# Picsi Mátyás Király Utcai Általános Iskola – Informatikai Versenycsapatok

A pécsi **Mátyás Király Utcai Általános Iskola** informatikai versenycsapatainak közös GitHub-szervezete.
Ide kerülnek **évről évre** a versenyprojektek (Hack&Code, iskolai/megyei/országos fordulók), a hozzájuk tartozó **forráskódok**, **megoldások** és **oktató anyagok**.
Az iskola hagyományaira építve támogatjuk a **modern, kreatív digitális alkotást**.

---

## 🎯 Küldetés

* **Közösségi tudásbázis:** minden tanév verseny- és gyakorló projektje egy helyen, visszakereshetően.
* **Tanulás kóddal:** példák, sablonok, leírások – hogy a csapatok önállóan is tudjanak építkezni.
* **Tiszta források:** egységes szerkezet, licenc és kódstílus, hogy más évfolyamok is bátran újrahasznosítsák.

> A névadó **Mátyás király** példája (igazságosság, műveltségpártolás) iránytűnk: korrekt, dokumentált és minőségi munka.

---

## 📦 Mit találsz itt?

* **Versenyprojektek:** tanévenként csoportosítva (pl. `2025-hackandcode-space-runner`).
* **Oktató anyagok:** beállítási útmutatók (IDE, Git, Node), „mini-kurzusok”, feladatlapok.
* **Eszközkészlet:** újrahasznosítható sablonok (Vite + React/TS, Phaser játék-alap, Node/WebSocket backend, CI-workflowk).

---

## 🗂 Ajánlott repo-struktúra

```
/2025/
  hackandcode-space-runner/
  phaser-starter-kit/
  worksheets-algorithms/
/2026/
  ...
/shared/
  templates/
  eslint-prettier-config/
  ci-workflows/
```

---

## 🛠 Tech stack (iránymutató)

* **Frontend:** Vite • React • TypeScript • Ant Design • Phaser
* **Backend:** Node.js • egyszerű WebSocket vagy HTTP API
* **Tooling:** ESLint + Prettier • Conventional Commits • GitHub Actions (CI)

---

## 🚀 Kezdő lépések csapattagoknak

1. Kérj meghívót a szervezethez (tanár/mentor).
2. Hozz létre **privát** repo-t a csapatodnak (tanév + projekt neve).
3. Töltsd ki a `README.md`-t: cél, feladat, csapatszerepek, futtatás.
4. Adj licencet (iskolai példákhoz **MIT** ajánlott).
5. Nyiss **issue**-kat feladatokra; dolgozz **branch**-eken; küldj **PR**-t.

**Gyors indítás (példa)**

```bash
git clone https://github.com/<org>/<repo>
cd <repo>
pnpm i
pnpm dev
```

> Környezeti változókhoz használj `.env.example` fájlt; build/release lépések a repo-k `CONTRIBUTING.md` fájljában.

---

## 🤝 Hozzájárulás & szabályok

* Tartsuk be a **CODE_OF_CONDUCT**-ot és a szerkesztési irányelveket.
* Források, képek: csak **jogtiszta** anyagok; hivatkozz, ha kell.
* **Személyes adatok** (névsor, fotók) ne kerüljenek publikus repo-kba; ha muszáj, használj privát tárhelyet és hozzáférés-kezelést.

---

## 🔒 Biztonság

Hibát vagy sebezhetőséget találtál?
Jelezd a mentorodnak **vagy** nyiss privát jelentést a szervezet *Security advisories* felületén.

---

## 🌐 Linkek

* **Iskola weboldala:** [https://www.matyas-pecs.edu.hu/](https://www.matyas-pecs.edu.hu/)
* **Wikipédia (iskola):** [https://hu.wikipedia.org/wiki/M%C3%A1ty%C3%A1s_Kir%C3%A1ly_Utcai_%C3%81ltal%C3%A1nos_Iskola](https://hu.wikipedia.org/wiki/M%C3%A1ty%C3%A1s_Kir%C3%A1ly_Utcai_%C3%81ltal%C3%A1nos_Iskola)

---

### Extra (ajánlott a `.github` repo-ba)

* `.github/ISSUE_TEMPLATE/bug_report.yml`, `feature_request.yml`
* `.github/PULL_REQUEST_TEMPLATE.md`
* `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`
* `CODEOWNERS` (review-felelősök)
