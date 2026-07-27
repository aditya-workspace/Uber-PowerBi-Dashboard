# 🚖 Uber Ride Analytics Dashboard — Power BI

An end-to-end business intelligence dashboard analyzing Uber ride-hailing operations — covering bookings, revenue, cancellations, and customer behavior — built to support data-driven decision-making.

![Dashboard Preview](images/00_home.png)

---

## 📌 Overview

Uber connects riders with drivers through a digital marketplace, generating rich operational data across every trip. This project transforms raw ride-booking data into a **4-page interactive Power BI dashboard** that surfaces where revenue is being lost, why bookings get cancelled, and which customer segments matter most.

**Live goal:** Go beyond visualization — turn data into a prioritized business recommendation.

---

## 🗂️ Dashboard Pages

| Page | What it covers |
|---|---|
| **Home** | Landing page and navigation |
| **Customer Overview** | First-time vs. returning riders, customer count trends, revenue-at-risk by segment, demand heatmap by day/time slot |
| **Bookings & Cancellations** | Completed vs. lost bookings, cancellation reasons (customer vs. driver side), ride distance and booking volume by vehicle type |
| **Revenue** | Total revenue, revenue by vehicle type, revenue by payment method, top customers by revenue, MoM revenue change |
| **Booking Status** | Booking funnel breakdown, completion rate, revenue leakage, monthly booking/revenue trend |

---

## 📊 Key Insights

- **139K total bookings**, generating **₹48.23M in total revenue** (+9.1% MoM)
- **Completion rate of 62%** — with **₹7.93M in revenue leakage** from incomplete/cancelled rides
- **Revenue-at-risk is concentrated in first-time riders** (~₹20M+) vs. almost none in returning riders — pointing to **retention as the higher-leverage lever over acquisition**
- Top cancellation reasons differ by side: **"Change of plans"** (customers) vs. **"Customer related issue"** (drivers) — implying two distinct fixes are needed
- **6 PM–9 PM is peak demand across every day of the week**, useful for driver supply planning
- **Auto** is the leading vehicle type by both bookings and revenue; **UPI** is the dominant payment method (₹21.69M)

---

## 🛠️ Tools & Tech Stack

- **Power BI Desktop** — data modeling, DAX, visualization
- **Power Query (M)** — data cleaning and transformation
- **DAX** — calculated measures (completion rate, revenue leakage, MoM change, revenue-at-risk)

---

## 📁 Repository Structure

```
├── uber-dashboard.pbix        # Power BI source file
├── data/                      # Source dataset (raw booking data)
├── images/                    # Dashboard screenshots
├── measures.md                # DAX measures reference
└── README.md
```

---

## 🚀 How to Use

1. Clone this repo
2. Open `uber-dashboard.pbix` in **Power BI Desktop**
3. Refresh the data source if needed (Home → Refresh)
4. Explore each page via the left navigation panel

---

## 🎯 Why This Project

Built as part of a product-analytics portfolio — practicing the same skill product managers rely on: turning raw data into a clear, prioritized recommendation rather than just a chart.

---

## 📬 Connect

If you're working in product, analytics, or fintech and want to discuss this project — feel free to reach out or open an issue.
