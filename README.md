# **AirLens – Air Quality Monitoring & Comparison Web App**

A simple, interactive, single-page web application built using **HTML, CSS, and JavaScript** to visualize and compare air quality data across different cities.
It includes charts, comparisons, search features, mock APIs, leaderboards, and recommendations.

---

##  **1. Project Overview**

**41** helps users monitor, compare, and analyze air quality metrics such as **PM2.5, PM10, CO, and NO₂** for multiple cities.
The application visualizes pollution levels using **interactive charts** and **dynamic UI components**, and provides helpful recommendations to raise awareness about environmental health.

---

##  **2. Features / Functional Requirements**

###  Display Air Quality Metrics

Shows PM2.5, PM10, CO, and NO₂ levels for selected cities.

###  Compare Multiple Cities

Users can select 2–3 cities and view side-by-side comparisons.

###  Interactive Charts

Includes bar charts, line charts, and pollution-intensity visuals.

###  Search & Filter

Search for cities based on pollution levels or name.

###  Responsive Design

Fully optimized for **mobile, tablet, and desktop**.

---

##  **3. Optional Enhancements (Included)**

###  Mock Real-Time API Simulation

Automatically refreshes air quality data every few seconds.

###  Historical & Seasonal Trends

Line charts show pollution history for each city.

###  Health Recommendations

Generates tips based on current air quality levels.

###  City Leaderboard

Ranks cities from cleanest to most polluted.

---

## **4. File Structure**

Since this is a **single-file** project:

```
41.html
```

Everything (HTML + CSS + JavaScript + charts) is inside this file.

---

## **5. Setup Instructions**

### **Step 1: Download or copy the HTML file**

Save it as:

```
41.html
```

### **Step 2: Open in Browser**

Double-click or open it inside any browser:

* Chrome
* Firefox
* Edge

### **Step 3: No Installation Required**

All code runs locally — no backend required.

---

## **6. How It Works**

### **Mock Data Generation**

A JavaScript function randomly updates:

* PM2.5
* PM10
* CO
* NO₂

for each city every few seconds.

### **Charts**

Charts are built using HTML Canvas + native JS drawing functions.

### **Comparisons**

Values from two or more cities are displayed side by side.

### **Leaderboard**

Cities are sorted by overall pollution score.

### **Recommendations**

Rules determine health warnings & safety actions.

---

##  **7. Deliverables (All Included)**

###  Source Code

Single-file HTML with full CSS + JS.

###  Visuals

Dynamic charts appear when the webpage runs.


---

## **8. Challenges & How They Were Solved**

### **1️ Designing clear visualizations**

Used simple, high-contrast bars and lines
Organized metrics to avoid clutter

### **2️ Managing multiple data sets**

 Created modular functions to handle city objects
 Updated charts dynamically without page reload

### **3️ Ensuring responsive layout**

 Used flexbox + percentage-based widths
 Lightweight design for fast mobile performance

---

## **9. Future Enhancements (Extendable)**

* Live API integration (OpenAQ, IQAir)
* User accounts & saved city lists
* Predictive analytics with ML
* City heatmaps

---

