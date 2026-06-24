# FPL-2025-2026-Season-Dashboard
An interactive, data-driven analytics application designed to unpack, visualize, and benchmark player and club performance data across the Fantasy Premier League (FPL) season. This dashboard transforms complex sports metrics into actionable strategic intelligence, enabling users to evaluate roster efficiency, track underlying creative metrics, and optimize budget allocations.

## 📊 Dashboard Architecture & Views

The project features a centralized user interface with an elegant navigation matrix allowing seamless transitions between three main analytical engines.

### 1. Landing Page
* **Description:** Provides a streamlined, user-friendly entry point using intuitive visual blocks to route users directly into specific micro or macro-analytical modules.

### 2. FPL Overview
* **Key Metrics Tracked:** 
  * High-level KPIs: Total FPL Points (34K), Goals Scored (1K), Total Players (841), and League-Wide Average Points (40.88).
  * Financial Efficiency: Point-Per-Million (PPM) optimization curve tracking.
  * Distributions: Total point aggregations sorted across all competing Premier League clubs alongside a localized "Goal Share Among Top 4 Scorers" breakdown.

### 3. Player Performance Analysis
* **Key Metrics Tracked:**
  * Elite Outliers: Direct tracking of league leaders in Points, Goals, Assists, and Clean Sheets.
  * Disciplinary Risk Assessment: Pie-chart breakdown isolating the highest yellow card receivers.
  * Asset Benchmarking: Multi-bar point tracking displaying the step-down distribution among top-tier assets to identify reliable point generators.

### 4. Club Analysis
* **Key Metrics Tracked:**
  * Offensive Volatility: Side-by-side comparative bar charts analyzing total goals against total assists per club.
  * ICT Breakdown: Multi-dimensional visualization assessing team-wide Influence, Creativity, and Threat (ICT) metrics.
  * Fixture Variance Engine: Scatter-plot matrix mapping the correlation between total points accumulated against Home Stadium Strength Ratings.

## 🛠️ Built With

* **BI Visualization Tool:** Power BI
* **Data Source:** Official Fantasy Premier League API

## 🚀 Key Features

* **Bi-directional Cross-Filtering:** Selecting any specific club via the "Filter by Club" slicer instantly recalculates all player profiles, goal shares, and underlying metrics across the respective view.
* **Granular Drill-Downs:** Dive from macroscopic club performance directly down into individual player metrics.
* **Risk vs. Reward Modeling:** Built-in disciplinary and home/away strength indicators enable managers to weigh high-risk creative differentials against reliable, high-floor options.
