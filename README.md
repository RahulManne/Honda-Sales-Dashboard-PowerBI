# Honda-Sales-Sashboard-PowerBI

## 1. Project Overview

I built this Power BI dashboard to track and compare dealership sales across Honda's two-wheeler lineup in India—including models like the **CB350**, **Activa 6G**, **Hornet 2.0**, **Shine**, and **Unicorn**. Instead of a standard white report, I designed a custom dark-red theme that matches Honda's branding and lets you switch between bikes at the top to see how each model performs.

## 2. Dataset & Data Modeling

I got the dataset from **Kaggle**, which covers vehicle orders across different Indian states, along with order amounts, cost prices, customer ratings, payment modes, and add-ons like insurance and financing. I cleaned and shaped the raw tables in Power Query and wrote custom DAX measures to handle the dynamic totals and monthly trends when switching between models.

## 3. Key Metrics & KPIs

* **Orders & Ratings:** Total units sold and average customer rating (for example, `245` orders and a `4.31` rating for the CB350).

* **Insurance & Finance:** Revenue coming from vehicle financing (`32M`) and insurance policies (`1M`).

* **Sales, Cost & Profit:** Core numbers showing **Net Sales Amount** (`53M`), **Cost Price** (`41M`), and **Gross Profit** (`12M`), paired with monthly trendlines from Jan to Dec.

## 4. Key Insights & Visualizations

* **Model Selector:** Clicking any bike or scooter at the top updates every number and chart on the screen for that specific model.

* **Monthly Trends:** Three line charts at the bottom make it easy to spot seasonal spikes and dips in sales, costs, and profit across the year.

* **Payments & States:** Donut charts on the right break down how customers pay (**UPI**, **Credit Card**, **Finance**, **Cash**) and which states drive the most orders (**Uttar Pradesh**, **Gujarat**, **Karnataka**, etc.).

## 5. Tools Used

* **Power BI Desktop** (Dashboard layout, visuals, and slicers)

* **Power Query** (Data cleaning and transformations)

* **DAX** (Calculated measures for KPIs)

* **Figma** (Custom background layout and icons)

## 6. Screenshots

 **CB350 Model Overview** 
![Honda CB350 Dashboard Preview](Screenshots/Snapshot%202%20of%20Honda-Sales%20Dashboard.png)

