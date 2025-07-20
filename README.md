#🚀 **Nasa_Asteroids_Data**

**Overview: NASA Asteroid Data**
This project analyzes Near-Earth Object (NEO) asteroid data from NASA’s public API. It collects real-time asteroid approach information, stores it in a cloud SQL database, and presents interactive insights through a Streamlit-based web dashboard.

The dashboard allows users to explore asteroid approach patterns — such as velocity, distance, frequency, and orbital behavior — using predefined queries or custom filters (e.g., date range, speed, distance).

It's a complete ETL + SQL + Visualization pipeline, ideal for scientific exploration, learning, and presentations.

.

🧩**Steps Involved**
**1. Data Collection**
Retrieve asteroid data from NASA’s NEO Feed API for a selected date range.

**2. Data Transformation**
Extract relevant fields like name, magnitude, speed, distance, and approach dates.

Convert nested JSON into a clean, structured format.

**3. Data Storage**
Create two normalized tables:

asteroids (basic info)

close_approach (event details)

Insert the data into a TiDB Cloud (MySQL-compatible) database using Python.

**4. SQL Querying**
Write over 20 SQL queries to analyze asteroid behaviors:

Fastest/closest approaches

Monthly/yearly trends

Orbiting body stats

Asteroids with repeated approaches

**5. Dashboard Development**
Build an interactive UI using Streamlit.

Include:

Dropdown to run predefined queries

Sidebar filters for custom queries (date, AU, lunar distance, velocity)
