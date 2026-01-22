India’s Vehicle Registration Trends (2020–2025): EV & Fuel Transition Analysis
📊 SQL, Python, and Power BI project analyzing:
- Post-COVID growth in registrations
- EV adoption vs Petrol/Diesel/CNG
- Manufacturer market share trends
- Policy impact of BS-VI norms

Indian Vehicle Registration Data (2020–2025)
This dataset contains Indian RTO-style vehicle registration records from FY 2020 onwards. It captures temporal, geographic, manufacturer, fuel, and regulatory attributes, enabling trend analysis, forecasting, and policy impact studies.

It includes:

500,000-row sampled transactional dataset for deep exploratory analysis

Aggregated state–month–fuel dataset for time-series analysis

Special handling is required for grossVehicleWeight = 0, which indicates non-applicable or unrecorded values (commonly for two-wheelers).

2️⃣ Key Business Questions You Can Answer 🔍
🚗 Market & Growth

How have vehicle registrations grown post-COVID (2020–2025)?

Which states show the fastest growth in registrations?

Monthly & seasonal registration patterns

⚡ EV & Fuel Transition

EV adoption trend vs Petrol/Diesel/CNG

State-wise EV penetration

Fuel mix shift after BS-VI norms

🏭 Manufacturer Insights

Top manufacturers by volume & growth

Fuel preference by manufacturer

Market share trends over time

🏛 Policy & Regulation Impact

Impact of BS-VI pollution norms

Pre vs post policy registration spikes

Used vs New vehicle trends

3️⃣ Recommended Data Cleaning Rules 🧹
1. Treat grossVehicleWeight = 0 as NULL
2. Convert registrationMonthMMYY → proper date
3. Validate vehicleCount > 0
4. Standardize fuel names (EV / Electric)
5. Remove duplicate state–month–fuel rows (if any)

4️⃣ High-Impact Visualizations 📊
Must-Have Charts

📈 Monthly registrations (2020–2025)

🗺️ State-wise heatmap of vehicle growth

⚡ EV vs Petrol/Diesel stacked area chart

🏭 Manufacturer market share trend

📉 COVID impact & recovery curve

5️⃣ SQL / Excel / Python Project Ideas (Portfolio-Strong)
SQL

Top 5 states by YoY growth

Fuel-wise CAGR

Manufacturer-wise market dominance

Rolling 3-month registration averages

Excel / Power BI

Interactive dashboard with:

State slicer

Fuel type filter

Year comparison

EV growth KPI cards

Python

Time-series forecasting (ARIMA / Prophet)

EV adoption prediction

COVID vs post-COVID comparison

6️⃣ Perfect Portfolio Project Titles 💼

“India’s Vehicle Registration Trends (2020–2025): EV & Fuel Transition Analysis”

“Post-COVID Recovery of India’s Automobile Market”

“State-wise EV Adoption and Policy Impact Analysis”
