<p align="center">
  <h1 align="center">📊 csvlens</h1>
  <p align="center"><i>CSV/TSV explorer — load, filter, sort, chart, and export tabular data right in your browser</i></p>
  <p align="center">
    <img alt="GitHub Pages" src="https://img.shields.io/badge/live-GitHub%20Pages-blue?style=flat">
    <img alt="size" src="https://img.shields.io/badge/size-419%20lines%20pure%20HTML/CSS/JS-purple?style=flat">
    <img alt="license" src="https://img.shields.io/badge/license-MIT-green?style=flat">
  </p>
</p>

**csvlens** is a zero-dependency, single-file HTML application for exploring CSV and TSV data. Paste data, open a file, and instantly get a sortable, filterable table with statistics and charts. No server, no install, no build step.

**[→ Open csvlens](https://neocrev.github.io/csvlens/)**

---

## Features

| Feature | Description |
|---|---|
| **Auto-detect delimiter** | Switches between comma and tab automatically based on content |
| **Sort by column** | Click any column header to sort ascending/descending |
| **Global search** | Filter rows across all columns with instant results |
| **Per-column filters** | Individual text filters in each column header |
| **Statistics panel** | Sum, mean, median, min, max, std dev, range for numeric columns |
| **Histogram chart** | Visual distribution of any numeric column (auto-binned) |
| **Row numbers** | Toggle `#` button to show original row indices |
| **Export** | Download filtered data as CSV |
| **Sample data** | Click "Sample data" to see a demo with 20 rows |
| **Keyboard friendly** | All controls are standard HTML inputs |

## Usage

1. **Open** `index.html` in any browser (or visit the [GitHub Pages link](https://neocrev.github.io/csvlens/))
2. **Paste** CSV/TSV data into the textarea, or click "Choose file" to upload
3. **Explore** — sort columns, search values, apply filters
4. **Analyze** — see stats and histograms for numeric columns
5. **Export** — download the filtered view as CSV

### Example

```csv
Name,Age,City,Salary
Alice,32,New York,85000
Bob,45,San Francisco,92000
Charlie,28,Chicago,67000
```

Paste this → click "Load" → click "Salary" column → see stats. That's it.

## How it works

A single `index.html` with Vanilla JS. Data lives in memory — nothing is sent to any server. Charts use [Chart.js](https://www.chartjs.org/) loaded from CDN. The app is stateless: refresh the page and you start fresh.

## Why csvlens?

- **No install.** Works in any browser, including mobile.
- **No upload.** Data never leaves your machine.
- **No config.** It just works.
- **Pure HTML/CSS/JS.** One file, 419 lines. Easy to fork, modify, embed.

## Tech

- Vanilla JavaScript (ES6+)
- [Chart.js](https://www.chartjs.org/) via CDN for histograms
- Tokyo Night color theme

---

<p align="center"><sub>Made by an AI agent, designed for humans.</sub></p>
