🎬 Netflix Viewer Engagement & Content Analytics
📌 Project Overview
This project is an end-to-end Exploratory Data Analysis (EDA) and data visualization dashboard built to analyze user streaming habits, content preferences, and engagement patterns on Netflix.

Using a dataset of 1,000+ granular viewing logs, this project transforms raw, unstructured event timestamps and content metadata into actionable business insights. The analytical pipeline answers critical platform questions: When are users most active? Which devices dominate specific content types? What genres drive the highest total watch time?

🛠️ Tech Stack & Core Concepts
Language: Python

Environment: Google Colab / Jupyter Notebook

Data Manipulation: pandas, NumPy

Data Visualization: seaborn, matplotlib

Analytical Techniques: Feature Engineering, Data Aggregation, Time-Series Breakdown, Segment Analysis

🏗️ Data Architecture & Pipeline
The project follows a standard data engineering and analytics lifecycle:

Data Ingestion & Structuring: Consolidated tabular tracking data containing unique User_IDs, Device types, Genres, and Playback Durations.

Feature Engineering: Extracted high-value operational metrics from raw Timestamp strings to create new behavioral dimensions: Hour of Day, Day of Week, and Month.

Statistical Aggregation: Grouped and segmented observations to isolate core platform Key Performance Indicators (KPIs).

📊 Dashboard Visualizations & Insights
The analytical dashboard generates a multi-panel visual matrix detailing user trends:

Genre Popularity: A distribution analysis identifying which storytelling categories capture the highest raw viewer volume.

Device Utilization Matrix: A segmented cross-tabulation comparing how screen choice (Smart TV vs. Mobile vs. Laptop) changes based on Content Type (Movies vs. TV Shows).

Hourly Traffic & Peak Demand: A time-series trend line plotting platform activity across a 24-hour cycle to pinpoint prime-time viewing windows.

Monthly Consumption Volume: A seasonal breakdown measuring variations in total minutes streamed month-by-month.

🚀 Key Business Takeaways
Prime-Time Window: The line chart reveals a sharp surge in viewer traffic during late-evening hours, indicating the optimal window for deploying localized content updates or targeted marketing notifications.

Form-Factor Pairing: The data demonstrates strong device affinity—e.g., users heavily favor Smart TVs for feature-length Movies, while Mobile and Tablet devices see higher proportional engagement for episodic TV Shows.

Resource Optimization: Identifying the lowest-performing genres and months provides concrete data for platform stakeholders to optimize content acquisition budgets and licensing strategies.

💻 How to Run the Project
Click the Open in Colab badge at the top of this page.

Run the cells sequentially (Shift + Enter).

(Optional) To analyze your own data, download your official NetflixViewingHistory.csv from your account settings, upload it to the Colab sidebar, and update the file path in the ingestion script.
