# 📊 Website Analytics & Social Listening Project Report

**Author:** Ojo Adewale Samuel  
**Program:** Nexlevr Weekly Internship Track  
**Tools Used:** Google Analytics 4 (GA4), Google Alerts  

---

## 📌 Project Overview
This repository documents the completion of my weekly Nexlevr track focused on web analytics implementation, traffic behavior analysis, and brand monitoring fundamentals.

* **Task 1:** Set up Google Analytics 4 (GA4) and document core performance metrics.
* **Task 2:** Analyze 7-day and 28-day traffic data to identify user acquisition and engagement patterns.
* **Task 3:** Establish a social listening workflow to monitor brand mentions and sentiment.

---

## 1️⃣ Task 1: Website Analytics Setup & Key Metrics Guide

### **Analytics Setup**
Connected to **Google Analytics 4 (GA4)** using the live **Google Merchandise Store** web property (`a54516992p213025502`) to explore real-time and historical e-commerce reporting (`Oct 18 – Nov 14, 2026`).

### **Core GA4 Metrics Explained**
| Metric | 28-Day Value | Definition & Business Meaning |
| :--- | :--- | :--- |
| **Active Users** | `107K` | Total number of distinct, unique visitors who engaged with the website. |
| **New Users** | `96K` | Visitors interacting with the site for the very first time (~90% of active users). |
| **Avg. Engagement Time** | `55s` | Average duration the website remained actively in focus in a user's browser. |
| **Event Count** | `1.7M` | Total tracked user interactions (page views, scrolls, clicks, and purchases). |
| **Sessions (7-Day)** | `26K` | Total individual browsing visits initiated by users (`21K` active users in 7 days). |
| **Key Events (7-Day)** | `25K` | High-value conversion actions such as add-to-cart, sign-ups, or purchases. |
| **Bounce Rate** | `8.9% – 61.7%` | Percentage of sessions that were not engaged (left without interacting or staying >10s). |

---

## 2️⃣ Task 2: Patterns Found in Traffic Data (28-Day Analysis)

### **A. Top-Performing Pages & User Retention**
* **Homepage Traffic vs. Bounce Rate:** The **Home** page drove the highest volume (**103K views**, **74K active users**) with a **61.7% bounce rate**.
* **High-Intent Category Pages:** Visitors who navigated deeper showed significantly stronger engagement:
  * **Google Merch Shop:** `47K views` | `47.2% bounce rate`
  * **New Arrivals:** `22K views` | `16.6% bounce rate`
  * **Men's / Unisex:** `17K views` | `13.2% bounce rate`
  * **Sale Page:** `13K views` | `8.9% bounce rate`

### **B. Traffic Acquisition Channels**
| Channel / Source | Active Users | Total Sessions | Key Insight |
| :--- | :--- | :--- | :--- |
| **Direct (`(direct) / (none)`)** | `64K` | `71K` | #1 driver of both new users and total return visits. |
| **Paid Search (`google / cpc`)** | `20K` | `26K` | Outperforms Organic Search in acquiring *first-time* visitors. |
| **Organic Search (`google / organic`)** | `17K` | `30K` | Generates higher repeat session volume than Paid Search. |
| **Referrals** | `~1.7K` | `3.8K` | Led by `art-analytics.appspot.com` (`2.6K`) and `support.google.com` (`1.2K`). |

### **C. Geographic & Audience Trends**
* **Platform Dominance:** **100.0%** of key events occurred on the **Web** platform.
* **Campaign Anomaly Detection:** Automated GA4 insights detected a major **Paid Search spike on October 25, 2026**, bringing in **3,485 users** and **3,846 sessions** (well above forecasted norms).
* **Top Geographic Hubs:** Led by **New York (`1.9K`)**, **Mountain View (`1.7K`)**, **San Francisco (`1.3K`)**, **Sunnyvale (`1.3K`)**, and **San Jose (`1K`)**, alongside international hubs **Karachi (`982`)** and **Lahore (`960`)**.
* **Audience Segmentation:** Out of `107K` total users, `43K` scrolled 75%+ down a page, `18K` were classified as **Engaged Users**, and `10K` were flagged as **Likely 7-day purchasers**.

---

## 3️⃣ Task 3: Social Listening Basics

* **Definition:** Social listening is the continuous monitoring of digital platforms, news sites, blogs, and forums for mentions of a brand, product, or industry keyword to evaluate customer sentiment and spot emerging trends.
* **Implementation:** Configured real-time keyword monitoring via **Google Alerts** (`google.com/alerts`) set to *"As-it-happens"* delivery to track brand mentions and industry discussions immediately.

---

## 📂 Repository Files
* `README.md` — Full formatted project report and analysis.
* `weekly_track_project_report.pdf` — Downloadable PDF version of the project report.
