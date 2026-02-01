# 🎬 FILMILYTICS: Data-Driven Insights for RSVP Movies

![Project Banner](https://img.shields.io/badge/Data%20Analysis-RSVP%20Movies-blue?style=for-the-badge&logo=analytics)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange?style=for-the-badge&logo=mysql)
![Excel](https://img.shields.io/badge/Excel-Data%20Visualization-green?style=for-the-badge&logo=microsoftexcel)

## 📌 Project Overview

**RSVP Movies** is a prominent Indian film production and distribution house, founded by Ronnie Screwvala. With a legacy of producing critically acclaimed hits like *Kedarnath*, *Pipa*, and *Uri: The Surgical Strike*, the company is now looking to leverage data to strategize its future releases.

**FILMILYTICS** is a comprehensive data analysis project designed to provide actionable business insights for RSVP Movies. By analyzing a vast dataset of global movie releases from the past three years, we help the production house make informed decisions about genres, actors, directors, and market strategies.

---

## 💼 Business Problem Statement

In an increasingly competitive global film market, RSVP Movies needs a data-driven roadmap to minimize risks and maximize audience engagement. This project solves this by:
- Identifying high-performing movie genres.
- Recommending top-tier talent (directors and actors) based on historical performance.
- Analyzing global vs. regional trends to optimize outreach.

---

## 📂 Dataset & Architecture

The analysis is built upon a robust relational database with the following core entities:

- **Movie**: Detailed metadata including title, year, duration, and country.
- **Genre**: Classification of movies across 13 unique categories.
- **Ratings**: Performance metrics like average ratings and total votes.
- **Talent Mapping**: Relationships between movies, directors (`Director_Mapping`), and actors (`Role_Mapping`).
- **Names**: Biographical data for industry professionals.

### 🛠️ Technical Stack
- **Database Management**: MySQL
- **Analysis Logic**: Advanced SQL (CTEs, Window Functions, Complex Joins, Views)
- **Data Exploration**: Microsoft Excel
- **Strategic Documentation**: Executive Summary Reports

---

## 🔍 Analytical Methodology

Our structured approach was divided into four strategic segments:

1.  **Segment 1: Data Exploration & Sizing**
    - Initial data audit, null value analysis, and trend identification (yearly/monthly).
2.  **Segment 2: Genre & Performance Analysis**
    - Identifying the most "bankable" genres and understanding movie duration trends.
3.  **Segment 3: Talent & Production Insights**
    - Ranking directors and actors based on weighted ratings and audience reception.
4.  **Segment 4: Strategic Deep-Dives**
    - Calculating running totals, moving averages, and refined performance classifications.

---

## 🏆 Key Recommendations

Based on our data-driven findings, RSVP Movies should adopt the following strategies:

*   **🎭 Double Down on Drama**: The Drama genre consistently produces the highest number of super-hits and maintains strong global appeal.
*   **🤝 Strategic Collaborations**: Partner with high-rated production houses like *Dream Warrior Pictures* and *National Theatre Live*.
*   **🌟 Talent Selection**: Prioritize highly-rated actors such as **Mammootty** and **Vijay Sethupathi**, and actresses like **Taapsee Pannu** for upcoming projects.
*   **🌍 Global Scaling**: Utilize the universal appeal of Drama and Thriller genres to expand into international markets while maintaining a strong foothold in the Indian region.

---

## 🚀 Getting Started

To explore the analysis:
1.  Navigate to the `RSVP_MOVIES_SQL_QUERIES.sql` file.
2.  Run the scripts in your MySQL environment on the `imdb` database.
3.  Check the `Executive Summary RSVP Movies.pdf` for a high-level business presentation.

---

*Generated with ❤️ by the Filmilytics Team. Transforming cinema through data.*
