# 🐾 Prayas — Animal Shelter Supply Tracker

A lightweight, browser-based supply management tool built for **Prayas Animal Shelter** to log, track, and manage food, medicine, and other supplies across shelter cages.

> **Live Demo →** _[Add your Vercel link here]_

---

## ✨ Features

| Feature | Description |
|---|---|
| **📊 Dashboard** | At-a-glance metrics, supply quantity breakdown bars (showing percentage totals by type), and ranked lists of top items supplied. Features per-cage cards showing daily averages and a minimal low-stock warning system. |
| **📦 Available Stock** | Easily log current inventory (Food, Medicine, etc.) on hand. Displays directly on the dashboard with a clean visual breakdown of quantities and stock levels. |
| **📝 Log Supply** | Fast, error-free logging using cascading dropdowns (Item Type → Category → Sub-category → Item) instead of text inputs. Features 1-click quick-log buttons for rapid data entry. |
| **📋 History** | Filterable table of all entries for the selected month, with one-click delete. |
| **🏠 Manage Cages** | Add, edit (inline), or remove cages. Track animal type, cage name, and expected monthly food (kg). |
| **📈 Report** | A dedicated monthly summary tab showing overall item totals and a detailed per-cage breakdown of items supplied. |
| **⬇ Excel Export** | Download filtered supply history as a native `.xls` file for easy spreadsheet reporting. |
| **💾 Local Storage** | All cage and log data is automatically persisted in your browser's local storage between sessions. |
| **📅 Month Selector** | Browse data across the last 12 months with a single dropdown. |

---

## 🖼️ Preview

| Dashboard | Log Supply | Report |
|---|---|---|
| Metric cards + minimal cage overviews | Quick-log buttons + auto-date | Monthly summary cards + cage breakdown |

---

## 🚀 Getting Started

### Run Locally

No build tools, no dependencies — just open the file:

```
git clone https://github.com/JaydeepBhandari/Prayas_Supply_Tracker.git
cd Prayas_Supply_Tracker
```

Then open `index.html` in your browser. That's it. Your data will be saved locally.

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **Vanilla CSS** — custom design system with CSS variables, no frameworks
- **Vanilla JavaScript** — zero dependencies, all logic in a single file
- **LocalStorage API** — for automatic, persistent client-side data storage

---

## 📁 Project Structure

```
Prayas_Supply_Tracker/
├── index.html      # Entire app — markup, styles, and logic
└── logo.png        # Custom brand logo for the header
```

Single-file architecture keeps deployment dead simple while maintaining clean separation of concerns internally (CSS → HTML → JS data layer → render layer).

---

## 🎯 Roadmap

- [x] Persist data with `localStorage`
- [x] Add monthly reporting metrics
- [x] Excel data exports
- [ ] Add user authentication for volunteers
- [ ] Photo uploads for cage inspections
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
