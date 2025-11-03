# Financial Insights Dashboard

A responsive Personal Finance Dashboard to track budgets, expenses, savings goals, and investments with interactive Chart.js visualizations. Add entries, view live-updating charts, and monitor progress toward financial goals in one clean interface.

## Features
- Budget tracking with progress visualization
- Expense logging by category with breakdown chart
- Savings goals with progress tracking
- Investment overview chart
- Clean, responsive UI

## Tech Stack
- HTML, CSS, JavaScript (ES Modules)
- Chart.js

## Project Structure
.
├─ index.html
├─ style.css
└─ js/
   ├─ app.js
   └─ chart.js

## Getting Started

Serve the site over HTTP (ES modules won’t load via file://).

- Python:
  ```powershell
  cd "D:\SDE\Financial Dashboard"
  python -m http.server 5500
  ```
  Open http://localhost:5500/

- Node:
  ```powershell
  cd "D:\SDE\Financial Dashboard"
  npx http-server -p 5500
  ```
  Open http://localhost:5500/

- VS Code:
  - Install “Live Server” extension
  - Right-click `index.html` → Open With Live Server

## Screens
- Budget progress chart
- Expense category chart
- Savings goals progress
- Investment overview

## Roadmap
- Persistent storage (localStorage / backend)
- Import/export data
- More chart types and filters
- Dark mode

## License
MIT

Open http://localhost:5500/

--> Node:
  cd "D:\SDE\Financial Dashboard"
  npx http-server -p 5500

--> Open http://localhost:5500/

--> VS Code:
  1. Install “Live Server” extension
  2. Right-click index.html → Open With Live Server

--> Screens
  1. Budget progress chart
  2. Expense category chart
  3. Savings goals progress
  4. Investment overview

--> Roadmap
  1. Persistent storage (localStorage / backend)
  2. Import/export data
  3. More chart types and filters
  4. Dark mode
