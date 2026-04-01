<div align="center">

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes pulse { 0%,100%{opacity:.25} 50%{opacity:.85} }
      @keyframes fade { from{opacity:0;transform:translateY(8px)} to{opacity:1;transform:translateY(0)} }
      .p1{animation:pulse 2.4s 0s infinite}
      .p2{animation:pulse 2.4s .3s infinite}
      .p3{animation:pulse 2.4s .6s infinite}
      .p4{animation:pulse 2.4s .9s infinite}
      .p5{animation:pulse 2.4s 1.2s infinite}
      .title{animation:fade .6s .1s both}
      .sub{animation:fade .6s .3s both}
      .badges{animation:fade .6s .5s both}
    </style>
  </defs>
  <rect width="800" height="200" fill="#0d1117" rx="12"/>
  <!-- grid -->
  <line x1="0" y1="50" x2="800" y2="50" stroke="#21262d" stroke-width=".5"/>
  <line x1="0" y1="100" x2="800" y2="100" stroke="#21262d" stroke-width=".5"/>
  <line x1="0" y1="150" x2="800" y2="150" stroke="#21262d" stroke-width=".5"/>
  <line x1="200" y1="0" x2="200" y2="200" stroke="#21262d" stroke-width=".5"/>
  <line x1="400" y1="0" x2="400" y2="200" stroke="#21262d" stroke-width=".5"/>
  <line x1="600" y1="0" x2="600" y2="200" stroke="#21262d" stroke-width=".5"/>
  <!-- glow -->
  <ellipse cx="390" cy="100" rx="260" ry="70" fill="#1f6feb" opacity=".1"/>
  <!-- calendar icon -->
  <rect x="40" y="65" width="70" height="70" rx="8" fill="none" stroke="#388bfd" stroke-width="1.5"/>
  <rect x="40" y="65" width="70" height="20" rx="8" fill="#1f6feb" opacity=".5"/>
  <line x1="62" y1="57" x2="62" y2="73" stroke="#58a6ff" stroke-width="2" stroke-linecap="round"/>
  <line x1="98" y1="57" x2="98" y2="73" stroke="#58a6ff" stroke-width="2" stroke-linecap="round"/>
  <rect x="52" y="97" width="12" height="12" rx="2" fill="#58a6ff" class="p1"/>
  <rect x="70" y="97" width="12" height="12" rx="2" fill="#58a6ff" class="p2"/>
  <rect x="88" y="97" width="12" height="12" rx="2" fill="#3fb950" class="p3"/>
  <rect x="52" y="115" width="12" height="12" rx="2" fill="#58a6ff" class="p4"/>
  <rect x="70" y="115" width="12" height="12" rx="2" fill="#58a6ff" class="p5"/>
  <!-- text -->
  <text class="title" x="132" y="108" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif" font-size="40" font-weight="700" letter-spacing="-1" fill="#e6edf3">ProjectLibre</text>
  <text class="sub" x="134" y="132" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif" font-size="15" fill="#8b949e">Interaktiivne projektijuhtimise õpetlik veebijuhend</text>
  <g class="badges">
    <rect x="134" y="148" width="68" height="22" rx="11" fill="#238636" opacity=".3"/>
    <text x="168" y="163" text-anchor="middle" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif" font-size="11" fill="#3fb950">● Kalender</text>
    <rect x="212" y="148" width="82" height="22" rx="11" fill="#1f6feb" opacity=".3"/>
    <text x="253" y="163" text-anchor="middle" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif" font-size="11" fill="#58a6ff">● Diagrammid</text>
    <rect x="305" y="148" width="68" height="22" rx="11" fill="#6e40c9" opacity=".3"/>
    <text x="339" y="163" text-anchor="middle" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif" font-size="11" fill="#bc8cff">● HTML/CSS</text>
  </g>
</svg>

# ProjectLibre — Õpetlik Veebijuhend

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](.)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](.)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](.)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](.)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)](.)

</div>

---

## 📖 Ülevaade

**ProjectLibre** on tasuta avatud lähtekoodiga alternatiiv Microsoft Projectile. See interaktiivne veebijuhend katab kahte põhiteemat:

- 📅 **Kalendrid** — tööaja, pühade ja vabade päevade haldamine
- 📊 **Diagrammid** — Gantti diagramm ja ressursigraafik

> Juhend töötab puhta HTML/CSS/JS-ga, ühtegi raamistikku pole vaja.

---

## 🗂 Projekti struktuur

```
📦 projectlibre-juhend
 ┣ 📄 kalender.html         ← Kalendri loomise juhend (6 sammu)
 ┣ 📄 diagrammid.html       ← Diagrammide juhend (4 sammu)
 ┗ 📂 images
    ┣ 📂 kalender
    ┃  ┣ 🖼️  step1.png       Resource → Calendar avamine
    ┃  ┣ 🖼️  step2.png       Kalendri menüü ja seaded
    ┃  ┣ 🖼️  step3.png       TestKalendri loomine
    ┃  ┣ 🖼️  step4.png       Päevade ja tööaja seadistamine
    ┃  ┣ 🖼️  step5.png       Advanced → Task Calendar
    ┃  ┗ 🖼️  step6.png       Kalendriikoon projekti peal
    ┗ 📂 diagrammid
       ┣ 🖼️  step1.png       Task → Gantt avamine
       ┣ 🖼️  step2.png       Gantti diagramm ülesannetega
       ┣ 🖼️  step3.png       Views → Resource Usage avamine
       ┗ 🖼️  step4.png       Resource Usage diagramm
```

---

## 🚀 Alustamine

```bash
# 1. Klooni repositoorium
git clone https://github.com/melon3000/projectlibre-juhend.git

# 2. Mine kausta
cd projectlibre-juhend

# 3. Ava brauseris
open kalender.html         # macOS
start kalender.html        # Windows
xdg-open kalender.html     # Linux
```

> **Nõuded:** Kaasaegne brauser (Chrome, Firefox, Safari, Edge). Serverit pole vaja.

---

## 📄 Lehed

<table>
<tr>
<td width="50%">

### 📅 `kalender.html`

| # | Samm |
|---|------|
| 1 | Resource → Calendar avamine |
| 2 | Kalendri menüü ja seaded |
| 3 | Uue TestKalendri loomine |
| 4 | Tööpäevade seadistamine |
| 5 | Task Calendar rakendamine |
| 6 | Tulemuse kontrollimine |

</td>
<td width="50%">

### 📊 `diagrammid.html`

| # | Samm |
|---|------|
| 1 | Task → Gantt avamine |
| 2 | Gantti diagramm ja ajakava |
| 3 | Views → Resource Usage |
| 4 | Ressursid ja tööaeg |

</td>
</tr>
</table>

---

## ✨ Funktsionaalsus

| Funktsioon | Kirjeldus |
|---|---|
| 📌 Kleepuv navigatsioon | Jääb lehe ülaossa kerimise ajal |
| 🔍 Piltide modal | Klõpsa pildil suurendamiseks |
| ⌨️ `Esc` klahv | Sulgeb modali |
| 🎬 Hero animatsioon | Sissefade + liikuv ruudustik |
| 📱 Reageeriv kujundus | Töötab mobiilis ja lauaarvutis |
| 🗂 Vahelehtede nav | Lihtne liikumine lehtede vahel |

---

## 🛠 Tehnoloogiad

| Tehnoloogia | Kasutus |
|---|---|
| `HTML5` | Lehe struktuur ja semantika |
| `CSS3` | Kujundus, animatsioonid, grid |
| `Vanilla JS` | Modal, sündmuste haldus |
| `Google Fonts` | Syne + DM Sans |

---

## 👤 Autor

<div align="center">

**melon3000**

[![GitHub](https://img.shields.io/badge/GitHub-melon3000-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/melon3000)

*Koostatud ProjectLibre õppeülesande jaoks*

</div>
