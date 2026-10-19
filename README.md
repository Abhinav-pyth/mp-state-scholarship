# एमपी छात्रवृत्ति हेल्पर (MP Scholarship Helper)

A single-page, bilingual (Hindi / English) static website that helps students and families in Madhya Pradesh understand and apply for **scholarships** and **government certificates** — with step-by-step guides, direct links to official portals, and an interactive eligibility checker.

## ✨ Features

- 🌐 **Bilingual UI** — toggle between Hindi and English; every text element carries `data-hi` / `data-en` attributes (no page reload needed).
- 📜 **Certificate Guides (चरण-दर-चरण)** — step-by-step instructions for:
  - Income Certificate (आय प्रमाण पत्र)
  - Caste Certificate (जाति प्रमाण पत्र)
  - Domicile / Resident Certificate (मूल निवासी प्रमाण पत्र)
  - Samagra ID (समग्र आईडी) creation & download
- 🎓 **Scholarship Schemes (नर्सरी से 12वीं)** — details on Pre-Matric, MMVY, Ladli Laxmi Yojana, MPTAAS, and more.
- 🎯 **Eligibility Checker** — client-side form that helps users quickly assess which schemes they may qualify for.
- 🔗 **Official Portal Links** — curated links to verified government websites:

  | Portal | URL |
  |---|---|
  | MP Scholarship Portal | https://scholarshipportal.mp.gov.in/ |
  | MP e-District | https://edistrict.mp.gov.in/ |
  | MP Online | https://www.mponline.gov.in/ |
  | Samagra Gateway | https://samagra.gov.in/ |
  | Ladli Laxmi Yojana | https://ladlilaxmi.mp.gov.in/ |
  | MPTAAS (Tribal Welfare) | https://tribal.mp.gov.in/mptaas |
  | DBT Bharat | https://dbtbharat.gov.in/ |
  | National Scholarship Portal | https://scholarships.gov.in/ |

- 🔍 **SEO-ready** — complete meta tags, Open Graph / Facebook previews, canonical URL, and structured data.

## 🛠 Tech Stack

- **HTML5** — semantic markup
- **Tailwind CSS** — via CDN (`https://cdn.tailwindcss.com`), no build step required
- **Vanilla JavaScript** — language toggle, eligibility checker, and UI logic embedded directly in the page

No frameworks, no bundlers, no backend — everything lives in a single file.

## 📁 Project Structure

```
.
├── index.html   # Complete application (markup + styles + scripts)
└── README.md    # This file
```

## 🚀 Getting Started

Since the site is fully static, you can run it locally with any web server:

```bash
# Option 1: Python
python3 -m http.server 8000
# then open http://localhost:8000

# Option 2: Node.js
npx serve .

# Option 3: Just open the file directly
# double-click index.html or: xdg-open index.html
```

## 🌍 Deployment

Deploy to any static host, for example:

- **GitHub Pages** — push to a repo and enable Pages from the root branch.
- **Netlify / Vercel** — drag-and-drop deploy, zero configuration needed.
- **Cloudflare Pages** — connect the Git repository for automatic deployments.

Update the `<link rel="canonical">` and `og:url` tags in `index.html` to match your production domain.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/amazing-feature`).
3. Commit your changes (`git commit -m 'Add amazing feature'`).
4. Push to the branch (`git push origin feature/amazing-feature`).
5. Open a Pull Request.

## ⚠️ Disclaimer

This is an unofficial informational project. Always verify scheme details, deadlines, and application procedures on the official government portals listed above.

## 📄 License

This project is provided as-is for educational and public-information purposes.
