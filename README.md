# ✈️ AeroTrack Live: Global Flight Telemetry Dashboard ✈️

![output-onlinegiftools](https://github.com/user-attachments/assets/dbbea6da-3edd-446c-b778-a912afa4f4f8)

# 📌 Project Overview
AeroTrack Live is an advanced, interactive Power BI dashboard designed to act as a real-time Air Traffic Control (ATC) monitoring system. By ingesting live global aviation data, this project transforms raw flight coordinates and physics metrics into actionable operational intelligence. It focuses heavily on anomaly detection, airspace congestion, and emergency telemetry tracking.


<img width="1919" height="1004" alt="Screenshot 2026-04-08 203059" src="https://github.com/user-attachments/assets/17540214-bba7-43d6-9f48-5f1ceb107421" />


# 🚀 Key Features & Analytical Insights
🔴 Active Emergency Monitoring: Utilized advanced DAX to create real-time tracking for critical Squawk codes (7700 - Emergency, 7600 - Comm Failure, 7500 - Hijack).

📈 Flight Envelope Analysis (Scatter Plot): Visualizes the correlation between Aircraft Altitude and Ground Velocity. This aids in identifying outliers (e.g., planes overspeeding at low altitudes).

📉 Vertical Rate Extremes (Combo Chart): Analyzes the top 10 aircraft with extreme climb or descent rates mapped against their current cruising altitude, acting as an early warning system for potential freefalls.

🌍 Geographical Drill-Throughs: Engineered hidden drill-through pages. Users can right-click any geographical region on the global radar to isolate and analyze localized airspace traffic.

🎨 Premium UI/UX: Features a "Dark Radar" theme, custom DAX-extracted airline identifiers, app-like page navigation, and advanced Z-order layering for transparent watermark effects.

<img width="1340" height="753" alt="image" src="https://github.com/user-attachments/assets/19c4ae8e-c68a-4194-8f3d-f591d59ddd65" />

# 🛠️ Tools & Technologies Used
Data Visualization: Power BI (Desktop)

Calculations & Logic: Advanced DAX (Data Analysis Expressions)

Data Processing: Power Query

Concepts: Telemetry Analysis, Outlier Detection, UI/UX Layering, Drill-Through Navigation.

# 📖 Data Dictionary
To make the dashboard accessible to non-aviation experts, a comprehensive Aero-Telemetry Dictionary is included within the dashboard to explain core parameters like ICAO24, Callsigns, Squawk Codes, and Vertical Rates.

# 💡 How to Interact
Download the .pbix file from this repository.

Open with Microsoft Power BI Desktop.

Use the top navigation buttons to switch between the Global Map, Telemetry Analysis, and the Data Dictionary.

On the Global Map, right-click any country's data point and select "Drill through" to see specific regional data.
