README ke liye ek ready markdown de raha hoon, sirf `README.md` bana ke is content ko paste kar dena repo me.

***

```md
# Finance Tracker

Simple, fast, and mobile–friendly finance tracker made with **HTML, CSS, and JavaScript**.  
It runs completely in the browser using **localStorage**, so your data stays on your device only.

🔗 Live Demo: https://armanlive.github.io/Finance_Tracker/

---

## Features

- 📥 Track **Income**, **Expenses**, and **Investments** (Share Market, Mutual Funds, LIC)
- 📅 Manage **repayments / EMIs** with due dates
- 🔍 Filter by **month** and **type** (Income / Expense / Share / MF / LIC)
- 📊 Monthly snapshot cards:
  - Total Income  
  - Total Expense  
  - Total Investments  
  - Balance (Surplus / Deficit)
- ⚠️ “Upcoming Dues” section for future EMIs/loans
- ✏️ Edit and delete individual entries
- 💾 Data stored in **localStorage** (no backend required)
- 📑 Export filtered data to **CSV**

---

## Tech Stack

- **HTML5** – structure and layout  
- **CSS3** – responsive, modern blue & white UI  
- **Vanilla JavaScript** – all logic (no frameworks)  
- **localStorage** – browser-based data storage

---

## How to Use

1. Open the live link or `index.html` file in any modern browser.
2. In **Add Entry**:
   - Select date, type, amount, and optional description.
   - Click **Save Entry**.
3. Use **filters** on top to see specific month or type.
4. Check **Monthly Snapshot** cards for quick totals.
5. Add EMIs/loans in **Add Repayment** section and see them under **Upcoming Dues**.
6. In **All Entries**:
   - Use **Edit** to modify an entry.
   - Use **Delete** to remove it.
7. Click **Export CSV** to download the current filtered entries as a CSV file.

---

## LocalStorage Notes

- All entries and dues are saved in:
  - `financeEntries`
  - `financeDues`
- Clearing browser storage or using a different browser/device will reset the data.

---

## Project Structure

```
.
├── index.html   # Main single-page app (HTML + CSS + JS)
└── README.md    # Project documentation
```

---

## Future Ideas

- Add category-wise charts (bar/pie)  
- Add simple **budget limits** and alerts  
- Add option to **backup/restore** data via file download/upload
```

Yahi file repo me add karke commit/push karoge to GitHub pe achha professional README dikh jayega.[1][2]

[1](https://github.com/mdazfar2/Budget-Tracker/blob/main/README.md)
[2](https://docs.github.com/en/pages/quickstart)
[3](https://github.com/topics/finance-tracker?l=typescript)
[4](https://github.com/topics/finance-tracker?l=java)
[5](https://github.com/EneoKajo/finance-tracker/blob/main/README.txt)
[6](https://github.com/topics/finance-tracker)
[7](https://www.codewithfaraz.com/content/516/create-expense-tracker-app-with-html-css-javascript)
[8](https://github.com/orgs/community/discussions/128670)
[9](https://github.com/topics/financial-tracking)
[10](https://github.com/Ratna-Babu/Expense-Tracker-Web-Application)
[11](https://richjenks.com/github-pages-from-readme/)
[12](https://github.com/neeraj542/Personal-Finance-Tracker)
[13](https://www.geeksforgeeks.org/javascript/build-an-expense-tracker-with-html-css-and-javascript/)
[14](https://dev.to/github/how-to-create-a-github-profile-readme-jha)
[15](https://www.freecodecamp.org/news/how-to-build-an-expense-tracker-with-html-css-and-javascript/)
[16](https://stackoverflow.com/questions/48919200/github-pages-only-showing-readme-file)
[17](https://www.youtube.com/watch?v=E6NO0rgFub4)
[18](https://www.youtube.com/watch?v=gstzPdGYrgI)
[19](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
[20](https://projectai.in/projects/9ab4a587-1d84-45a1-873d-76487e3fb349/tasks/9b12b89b-f207-4d31-9255-5e88ef31ac71)


  <style>
    :root {
      --primary: #2563eb;
      --primary-soft: #dbeafe;
      --accent: #f97316;
      --bg: #e5f0ff;
      --card: #ffffff;
      --text: #0f172a;
      --muted: #6b7280;
      --border: #d1d5db;
      --success: #16a34a;
      --danger: #dc2626;
    }
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: radial-gradient(circle at top, #eff6ff 0, #e5f0ff 60%);
      color: var(--text);
      padding: 10px;
      display:flex;
      justify-content:center;
    }
    .app {
      width:100%;
      max-width:1100px;
    }

    .header {
      background: linear-gradient(135deg, #3b82f6, #60a5fa);
      color:#f9fafb;
      padding:14px 16px;
      border-radius:14px;
      margin-bottom:14px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:8px;
      box-shadow:0 10px 25px rgba(37,99,235,0.35);
    }
    .header-left h1 {
      font-size:1.2rem;
      font-weight:700;
      letter-spacing:0.03em;
    }
    .header-left p {
      font-size:0.75rem;
      opacity:0.9;
      margin-top:2px;
    }
    .header-right {
      text-align:right;
      font-size:0.7rem;
    }
    .pill {
      display:inline-flex;
      align-items:center;
      gap:4px;
      padding:2px 8px;
      border-radius:999px;
      background:rgba(15,23,42,0.1);
      font-size:0.7rem;
      font-weight:600;
    }

    .section {
      background: var(--card);
      border-radius:14px;
      padding:14px;
      margin-bottom:12px;
      box-shadow:0 8px 18px rgba(148,163,184,0.35);
      border:1px solid var(--border);
    }
    .section h2 {
      font-size:0.95rem;
      margin-bottom:10px;
      display:flex;
      align-items:center;
      gap:6px;
    }
    .section h2 span.icon {
      font-size:1rem;
    }

    .form-grid {
      display:grid;
      grid-template-columns:repeat(2,minmax(0,1fr));
      gap:10px;
      margin-bottom:10px;
    }
    @media (max-width:700px){
      .form-grid { grid-template-columns:1fr; }
    }
    input, select, button {
      font-size:0.8rem;
    }
    input, select {
      padding:7px 9px;
      border-radius:8px;
      border:1px solid var(--border);
      background:#f9fafb;
      color:var(--text);
      outline:none;
      transition:all 0.15s ease;
    }
    input::placeholder { color:var(--muted); }
    input:focus, select:focus {
      border-color:var(--primary);
      box-shadow:0 0 0 1px rgba(37,99,235,0.25);
      background:#ffffff;
    }

    button {
      border:none;
      border-radius:999px;
      padding:7px 13px;
      cursor:pointer;
      font-weight:600;
      letter-spacing:0.02em;
      display:inline-flex;
      align-items:center;
      gap:6px;
      transition:all 0.15s ease;
    }
    .btn-primary {
      background:linear-gradient(135deg,#3b82f6,#2563eb);
      color:#f9fafb;
    }
    .btn-primary:hover { transform:translateY(-1px); box-shadow:0 8px 18px rgba(37,99,235,0.4); }
    .btn-soft {
      background:var(--primary-soft);
      color:var(--primary);
      border:1px solid #bfdbfe;
    }
    .btn-soft:hover { background:#bfdbfe; }
    .btn-danger {
      background:#fee2e2;
      color:var(--danger);
      border:1px solid #fecaca;
      padding:4px 9px;
      font-size:0.7rem;
      border-radius:999px;
    }
    .btn-danger:hover { background:#fecaca; }
    .btn-xs {
      padding:3px 7px;
      font-size:0.7rem;
    }

    .filters {
      display:flex;
      gap:8px;
      flex-wrap:wrap;
      margin-bottom:10px;
      align-items:center;
    }
    .filters select { min-width:135px; }

    .summary {
      display:grid;
      grid-template-columns:repeat(4,minmax(0,1fr));
      gap:8px;
    }
    @media (max-width:700px){
      .summary { grid-template-columns:repeat(2,minmax(0,1fr)); }
    }
    .stat {
      padding:10px 10px;
      border-radius:10px;
      background:linear-gradient(145deg,#eff6ff,#ffffff);
      border:1px solid #dbeafe;
      display:flex;
      flex-direction:column;
      gap:2px;
    }
    .stat-label {
      font-size:0.7rem;
      color:var(--muted);
      text-transform:uppercase;
      letter-spacing:0.06em;
    }
    .stat-value {
      font-size:0.9rem;
      font-weight:700;
      color:#111827;
    }
    .stat-tag {
      font-size:0.7rem;
      color:var(--success);
    }
    .stat-tag.negative { color:var(--danger); }

    .due-card {
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:7px 9px;
      border-radius:9px;
      background:#eff6ff;
      border:1px solid #dbeafe;
      margin-bottom:6px;
      font-size:0.75rem;
    }
    .due-main span { display:block; }
    .due-desc { font-weight:600; color:#111827; }
    .due-meta { color:var(--muted); font-size:0.7rem; }

    .table-wrapper {
      width:100%;
      overflow-x:auto;
      border-radius:10px;
      border:1px solid #dbeafe;
      background:#f9fafb;
    }
    table {
      width:100%;
      border-collapse:collapse;
      font-size:0.75rem;
    }
    th, td {
      padding:7px 8px;
      text-align:left;
      border-bottom:1px solid #e5e7eb;
      white-space:nowrap;
    }
    th {
      background:#eef2ff;
      color:#4b5563;
      font-weight:600;
      text-transform:uppercase;
      letter-spacing:0.06em;
      font-size:0.68rem;
      position:sticky;
      top:0;
      z-index:1;
    }
    tr:nth-child(even) { background:#f9fafb; }
    tr:hover td { background:#e0f2fe; }

    .chip-type {
      padding:2px 7px;
      border-radius:999px;
      font-size:0.65rem;
      font-weight:600;
    }
    .chip-income { background:#dcfce7; color:#166534; }
    .chip-expense { background:#fee2e2; color:#b91c1c; }
    .chip-invest { background:#dbeafe; color:#1d4ed8; }

    p { font-size:0.78rem; }
    .muted { color:var(--muted); }

    .empty-state {
      font-size:0.78rem;
      color:var(--muted);
      padding:6px 2px;
    }
  </style>
