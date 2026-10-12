# Costa Coffee — Bilingual Landing Page

A responsive, bilingual (English / Arabic) landing page for a coffee brand, inspired by the structure of major coffee-chain home pages. Built with plain HTML, CSS and JavaScript in a single file: no frameworks, no build step.

**Live demo:** https://USERNAME.github.io/costa-coffee-landing/

> **Concept project.** This is a design exercise and is not affiliated with, or endorsed by, any coffee company. *(Remove this note if the page was made for an approved client.)*

---

## Screenshots

| Desktop | Mobile | Arabic (RTL) |
|---|---|---|
| ![Desktop](screenshots/desktop.png) | ![Mobile](screenshots/mobile.png) | ![Arabic](screenshots/arabic.png) |

*Add your own screenshots to a `screenshots/` folder with these names. See "Taking screenshots" below.*

---

## Features

- **Language switch in the header.** One button flips the whole page between English and Arabic. Arabic switches the layout to right-to-left, and the choice is remembered on the next visit.
- **Full landing-page structure:**
  - announcement bar and sticky header (menu, rewards, app, stores, find a store, sign in, join now)
  - hero section with an animated steam cup
  - alternating feature blocks
  - menu categories
  - "most loved" product cards
  - rewards section
  - mobile app section
  - store finder by city
  - newsletter signup
  - full footer
- **Custom logo.** A round badge with a coffee bean whose center crease curves like a wisp of steam. The brand name runs around the rim in English and Arabic. It is drawn as inline SVG and reused across the page.
- **Responsive.** Layouts adapt from desktop to tablet to phone.
- **Accessible basics.** Visible keyboard focus, labelled controls, live regions for form feedback, and reduced-motion support.

## Design system

| Token | Hex | Used for |
|---|---|---|
| Espresso | `#2a1810` | Hero, footer, primary buttons |
| Roast | `#4a2c1d` | Cards, feature panels |
| Mocha | `#7a5038` | Accents, secondary text |
| Beige | `#e9d9c0` | Highlights, logo, panels |
| Sand | `#f3eadb` | Soft section backgrounds |
| White | `#ffffff` | Page background, text on dark |

**Typography:** [Reem Kufi](https://fonts.google.com/specimen/Reem+Kufi) for headings and [Cairo](https://fonts.google.com/specimen/Cairo) for body text. Both support Arabic and Latin, so the two languages share one visual voice.

## Tech

- HTML5, CSS3 (custom properties, grid, flexbox, logical properties for RTL)
- Vanilla JavaScript for the language switch and small interactions
- Google Fonts
- No dependencies

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any browser.

## Deploy on GitHub Pages

1. Push `index.html` (and this README) to a public repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then **main** and **/ (root)**, and save.
4. After a minute or two the site is live at `https://USERNAME.github.io/REPO-NAME/`.

## Customize

- **Text:** every translatable element carries a `data-ar` attribute holding its Arabic text, and the English text sits in the element itself. Edit both together.
- **Colors:** change the variables at the top of the `<style>` block (`--espresso`, `--roast`, `--mocha`, `--beige`, `--sand`).
- **Logo:** edit the `#logo` symbol at the top of the `<body>`.
- **Cities in the store finder:** edit the buttons inside the `#stores` section.

## Placeholders to replace

- The store finder shows a short note and has no real branch data yet.
- The newsletter form shows a confirmation message but does not send the email anywhere.
- App Store and Google Play buttons are not linked to real listings.
- Menu items, descriptions and promo text are sample copy, and no prices are shown.

## Taking screenshots

In Chrome: press `F12`, then `Ctrl+Shift+P` (`Cmd+Shift+P` on Mac), type **Capture full size screenshot** and press Enter. Use the device toolbar (`Ctrl+Shift+M`) for the mobile view, and switch the page to Arabic for the third image.

## Project structure

```
costa-coffee-landing/
├── index.html
├── README.md
└── screenshots/
    ├── desktop.png
    ├── mobile.png
    └── arabic.png
```

---

# نظرة عامة بالعربي

صفحة هبوط متجاوبة وثنائية اللغة (عربي / English) لبراند قهوة، مبنية بـ HTML وCSS وJavaScript في ملف واحد بدون أي مكتبات.

- **زر تغيير اللغة** في الهيدر يحوّل الصفحة بالكامل بين الإنجليزية والعربية، وتتحول الصفحة لاتجاه اليمين لليسار تلقائياً، والاختيار بيتحفظ للزيارة الجاية.
- **أقسام الصفحة:** شريط الإعلان، الهيدر، الواجهة الرئيسية، أقسام المميزات، تصنيفات القائمة، المشروبات الأكثر طلباً، المكافآت، التطبيق، البحث عن فرع، النشرة البريدية، والفوتر.
- **الألوان:** بني غامق وبيج وأبيض.
- **الشعار:** شارة دائرية فيها حبة بن يتحول شقّها لخيط بخار، واسم البراند حوالين الشعار بالعربي والإنجليزي.

**ملحوظة:** المشروع تصميم تجريبي وغير تابع لأي شركة قهوة.
