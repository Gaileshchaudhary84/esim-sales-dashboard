# eSIM Sales & Revenue Analytics Dashboard

A responsive, real-time analytics monitoring dashboard for telecom eSIM and travel SIM operations. The dashboard fetches aggregated business metrics, sales performance indicators, and destination breakdowns via a single optimized PostgreSQL RPC endpoint hosted on Supabase.

---

## 🚀 Live Demo & API

- **Live Application:** [https://gaileshchaudhary84.github.io/esim-sales-dashboard/](https://gaileshchaudhary84.github.io/esim-sales-dashboard/)
- **Backend Infrastructure:** Supabase (PostgreSQL 15+)
- **RPC Endpoint:** `POST /rest/v1/rpc/get_sales_dashboard`

---

## 📌 Core Features

- **Executive KPI Cards:** Real-time tracking of Today's Revenue/Orders, Month-to-Date (MTD) performance, and historical comparisons against previous billing cycles.
- **Interactive Daily & Monthly Charts:** Dual-axis visualization with metric toggles (Revenue vs. Orders) built with Chart.js.
- **Top eSIM Destinations:** Donut breakdown highlighting high-volume regions and destination distribution.
- **Sales Team Leaderboard:** Dynamic rep performance table tracking Target %, ARPU (Average Revenue Per User), MTD revenue, and volume rankings with built-in search and sort filters.
- **Dynamic Date Filtering:** Interactive date selector to evaluate performance across specific reporting windows.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Modern CSS (Glassmorphism & Slate/Indigo Palette), Vanilla JavaScript (ES6+)
- **Data Visualization:** Chart.js
- **Icons & Typography:** FontAwesome 6, Google Fonts (Inter)
- **Backend & Database:** Supabase, PostgreSQL (PL/pgSQL stored procedures, JSONB aggregation)
- **Deployment:** GitHub Pages

---

## 📂 Project Structure

```text
├── index.html        # Main dashboard structure and layout
├── styles.css        # Custom CSS styling and responsive grid rules
├── script.js         # API integration, Chart.js logic, and DOM mutations
└── README.md         # Project documentation