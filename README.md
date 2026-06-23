# 🐾 Prayas — Animal Shelter Supply Tracker

A lightweight, browser-based supply management tool built for **Prayas Animal Shelter** to log, track, and manage food, medicine, and other supplies across shelter cages.

> **Live Demo →** _[Add your Vercel link here]_

---

## ✨ Features

| Feature | Description |
|---|---|
| **📊 Dashboard** | At-a-glance metrics — active cages, entries this month, total food & quantity logged, with per-cage usage cards |
| **📝 Log Supply** | Quick form to record food, medicine, water, or other supplies against any cage |
| **📋 History** | Filterable table of all entries for the selected month, with one-click delete |
| **🏠 Manage Cages** | Add, edit (inline), or remove cages — animal type and cage name are fully editable |
| **⬇ CSV Export** | Download filtered supply history as a `.csv` file for reporting |
| **📅 Month Selector** | Browse data across the last 12 months with a single dropdown |

---

## 🖼️ Preview

| Dashboard | Log Supply | Manage Cages |
|---|---|---|
| Metric cards + cage overview grid | Clean form with auto-date | Inline editing with save/cancel |

---

## 🚀 Getting Started

### Run Locally

No build tools, no dependencies — just open the file:

```
git clone https://github.com/JaydeepBhandari/Prayas_Supply_Tracker.git
cd Prayas_Supply_Tracker
```

Then open `index.html` in your browser. That's it.



## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **Vanilla CSS** — custom design system with CSS variables, no frameworks
- **Vanilla JavaScript** — zero dependencies, all logic in a single file
- **LocalStorage-ready architecture** — data layer is modular and easy to persist

---

## 📁 Project Structure

```
Prayas_Supply_Tracker/
└── index.html      # Entire app — markup, styles, and logic
```

Single-file architecture keeps deployment dead simple while maintaining clean separation of concerns internally (CSS → HTML → JS data layer → render layer).

---

## 🎯 Roadmap

- [ ] Persist data with `localStorage` or a backend
- [ ] Add user authentication for volunteers
- [ ] Photo uploads for cage inspections
- [ ] Monthly PDF report generation
- [ ] Dark mode toggle

---

## 🤝 Contributing

This is an internal tool for Prayas Animal Shelter. If you'd like to contribute or adapt it for your own shelter:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---


