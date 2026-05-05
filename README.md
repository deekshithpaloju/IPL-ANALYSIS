# 🏏 IPL Analysis Dashboard (2008–2025)
**Power BI Report | File:** `project_2_completedpbix.pbix`

---

## 📌 Project Overview

This Power BI dashboard provides a comprehensive analysis of the **Indian Premier League (IPL)** seasons from **2008 to 2025**. It enables users to explore season-by-season statistics including winners, top performers, batting/bowling leaders, and team standings — all through an interactive, visually rich single-page report.

<img width="3200" height="1794" alt="Ipl dash board_page-0001" src="https://github.com/user-attachments/assets/780e5004-5dda-49f3-8492-17eb5386cd24" />

---

## 📊 Dashboard Sections

### 🔢 Season Selector (Slicer)
- Filter the entire dashboard by **IPL Season** (sorted in descending order)
- Drives all KPIs and stats dynamically for the selected year

---

### 🏆 Season Summary
| KPI Card | Description |
|---|---|
| **IPL Season** | The selected season year |
| **Season Winner** | Champion team name |
| **Season Winner Logo** | Visual logo of the winning team |
| **Season Runner Up** | Runner-up team name |
| **Season Runner Up Logo** | Visual logo of the runner-up team |

---

### 🟠 Orange Cap Stats *(Top Run Scorer of the Season)*
| KPI Card | Description |
|---|---|
| **Player Name** | Orange Cap holder's name |
| **Orange Cap Runs** | Total runs scored |
| **Orange Cap Holder Image** | Player photo |

---

### 🟣 Purple Cap Stats *(Top Wicket Taker of the Season)*
| KPI Card | Description |
|---|---|
| **PurpleCapHolder** | Purple Cap holder's name |
| **Purple Cap Wickets** | Total wickets taken |
| **PurpleCapImage** | Player photo |

---

### 🏏 Top Fours
| KPI Card | Description |
|---|---|
| **Top Fours Player Name** | Player hitting the most fours |
| **Top Fours Count** | Number of fours hit |
| **TopFoursPlayerImage** | Player photo |
| **Total 4's** | Season-wide total boundaries (fours) |

---

### 💥 Top Sixes
| KPI Card | Description |
|---|---|
| **TopSixesPlayerName** | Player hitting the most sixes |
| **Top Sixes Count** | Number of sixes hit |
| **TopSixesPlayerImage** | Player photo |
| **Total 6's** | Season-wide total sixes |

---

### 📋 Points Table
A tabular visual showing team standings for the selected season:

| Column | Description |
|---|---|
| **Logo** | Team logo (image URL) |
| **Team Name** | Name of the IPL franchise |
| **Pld** | Matches played |
| **Won** | Matches won |
| **Lost** | Matches lost |
| **NR** | No result matches |
| **Tie** | Tied matches |
| **Total Points** | Cumulative points |

---

## 🗃️ Data Sources / Tables

| Table | Description |
|---|---|
| `ipl_matches_data` | Core dataset — match results, cap holders, sixes, fours, season KPIs |
| `teams_data` | Team metadata — names, logos, and standings data |

---

## 🖼️ Assets & Branding

The report includes embedded images for branding and visual appeal:
- **IPL Logo**
- **Orange Cap** and **Purple Cap** award graphics
- **Player photos** (dynamic via card visuals)
- **Team logos** (used in the points table and winner/runner-up cards)
- Social media icons: **Instagram**, **X (Twitter)**, **YouTube**

---

## ⚙️ Report Settings

| Setting | Value |
|---|---|
| **Canvas Size** | 2000 × 1100 px |
| **Display Mode** | Fit to Page |
| **Theme** | CY24SU10 (Power BI base theme) |
| **Pages** | 1 (single-page dashboard) |
| **Drill Filter** | Enabled (cross-visual filtering) |
| **Export Mode** | Allow Summarized Data |
| **Enhanced Tooltips** | Enabled |

---

## 🚀 How to Use

1. Open the file `project_2_completedpbix.pbix` in **Microsoft Power BI Desktop**.
2. Use the **Season Slicer** (top-right area) to select an IPL season.
3. All KPI cards, cap stats, top boundary hitters, and the points table will update automatically.
4. Hover over visuals for enhanced tooltips with additional context.

---

## 📁 File Info

| Property | Detail |
|---|---|
| **File Name** | `project_2_completedpbix.pbix` |
| **File Size** | ~3.77 MB |
| **Last Modified** | May 5, 2026 |
| **Format** | Power BI Desktop Report (.pbix) |
| **Total Visuals** | 70+ (cards, shapes, images, table, slicer, buttons) |

---

*Built with Microsoft Power BI | IPL Data 2008–2025*
