# 🏏 Cricket Analytics Dashboard

A powerful and interactive **Power BI Dashboard** designed to review, compare, and analyze the performances of all players in a cricket tournament. This dashboard enables users to select the **Best XI** of the tournament based on dynamic selection criteria and player performance metrics.

---

## 🚀 Key Features

- Compare player statistics across the tournament
- Filter and analyze based on teams, roles, performance metrics, etc.
- Select a custom **Best XI** using performance-based parameters
- Interactive visuals and intuitive layout

---

## 🔍 Project Workflow

### 📥 1. Data Collection
- Scraped comprehensive tournament data from **[ESPNcricinfo](https://www.espncricinfo.com)** and player career stats from **[Cricbuzz](https://www.cricbuzz.com)** using the **BeautifulSoup** library in Python.

### 🧹 2. Data Transformation
- Cleaned raw data using **Pandas**:
  - Normalized player names
  - Linked matches with correct IDs
  - Removed inconsistencies
- Used **Power Query (M)** in Power BI for final data shaping.

### 🔗 3. Data Modeling
- Established relationships between datasets via keys like match IDs and team names.
- Created **DAX measures**, **calculated columns**, and **parameters** for in-depth insights and filtering logic.

### 📊 4. Dashboarding
- Built an engaging dashboard using Power BI’s visualization tools and best design practices.

---

## 🖼️ Dashboard Previews

| ![Screenshot 1](https://github.com/nickel-28/cricket-analytics/assets/84437844/a6fcf141-3c6a-43df-8d66-cec2ef15b4f6) | ![Screenshot 2](https://github.com/nickel-28/cricket-analytics/assets/84437844/133df831-f6f0-47d8-bdef-8f2a7fb9b323) |
|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| ![Screenshot 3](https://github.com/nickel-28/cricket-analytics/assets/84437844/3a49afeb-1fdb-48eb-a120-c3078f615a28) | ![Screenshot 4](https://github.com/nickel-28/cricket-analytics/assets/84437844/033e4d1b-a963-426b-9e54-06cf124af85f) |
| ![Screenshot 5](https://github.com/nickel-28/cricket-analytics/assets/84437844/01b73b9a-8393-473b-9829-fe6c04da5348) | ![Screenshot 6](https://github.com/nickel-28/cricket-analytics/assets/84437844/d29f6b52-0556-4f45-9e35-1177c096746e) |
| ![Screenshot 7](https://github.com/nickel-28/cricket-analytics/assets/84437844/6b72427b-f2de-4668-92cf-faca270c6530) | ![Screenshot 8](https://github.com/nickel-28/cricket-analytics/assets/84437844/1cca0efe-16b8-4a34-8475-9d5d1ba02232) |

---

## 🛠️ Tech Stack

- **Python**:
  - `BeautifulSoup` – for web scraping
  - `Pandas` – for initial data cleaning and wrangling

- **Power BI**:
  - **Power Query (M Language)** – for data transformation
  - **DAX** – for custom calculations and measures
  - **Interactive Visuals** – charts, filters, slicers

---

## 📌 Future Enhancements

- Add team-wise performance comparison
- Introduce clustering-based suggestions for Best XI
- Add year-wise and venue-wise drill-downs
- Integrate live APIs for real-time stats

---

> Built with passion for cricket and data 🌟
