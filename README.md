# Dragon Quest VII Reimagined — Fan Guide

คู่มือประกอบการเล่นส่วนตัวสำหรับ **Dragon Quest VII Reimagined** สร้างขึ้นเพื่อเป็นข้อมูลอ้างอิงในการเล่น ครอบคลุมตัวละคร ค่าพลัง กลยุทธ์ และ Walkthrough แต่ละบท

🌐 **Live:** https://g3ner8.github.io/dragon-quest-vii-guide/

---

## Features

- **Core Attributes** — ตารางแสดงค่าพลังหลักทั้งหมดพร้อมคำอธิบาย
- **Character Dashboard** — เลือกดูข้อมูลตัวละครแต่ละตัว: Radar Chart, ค่าสถิติ, เส้นทางอาชีพ, ไฮไลต์, และอุปกรณ์แนะนำ
- **Stat Ranking** — อันดับค่าพลังของทุกตัวละครในแต่ละสถิติ พร้อม Horizontal Bar Chart แบบเรียงลำดับ
- **Walkthrough** — ขั้นตอนการเล่นแบ่งตามบท พร้อม Timeline layout
- **Strategy & Tips** — กลยุทธ์และเคล็ดลับการเล่นจากประสบการณ์จริง

---

## Tech Stack

| Tool                                                              | Usage                              |
| ----------------------------------------------------------------- | ---------------------------------- |
| [Tailwind CSS](https://tailwindcss.com/) v3 (CDN)                 | Styling & responsive layout        |
| [Chart.js](https://www.chartjs.org/) (CDN)                        | Radar chart + Horizontal bar chart |
| [Google Fonts — Prompt](https://fonts.google.com/specimen/Prompt) | Thai + Latin typography            |
| Vanilla JavaScript                                                | All interactivity (no build step)  |

---

## Getting Started

ไม่มี build step — เปิดไฟล์ได้เลย:

```bash
git clone https://github.com/G3Ner8/dragon-quest-vii-guide.git
cd dragon-quest-vii-guide
open index.html
```

หรือจะใช้ Live Server extension ใน VS Code ก็ได้

---

## Project Structure

```
dragon-quest-vii-guide/
└── index.html    # Single-file app (HTML + CSS + JS)
└── README.md
```

---

## Accessibility

- WCAG 2.4.1 Skip link
- `aria-labelledby` on all sections
- `aria-current` on active nav items
- `aria-expanded` on mobile menu toggle
- Focus-visible indicators (WCAG 2.4.11)
- Touch targets ≥ 44px (WCAG 2.5.5)
- `prefers-reduced-motion` support

---

## Disclaimer

คู่มือนี้เป็นผลงานส่วนตัวของแฟนเกม **ไม่ใช่คู่มือทางการ** และไม่มีความเกี่ยวข้องกับ Square Enix แต่อย่างใด

Dragon Quest VII Reimagined เป็นเครื่องหมายการค้าของ Square Enix

---

## Author

**G3Ner8** — © 2026
