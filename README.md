#🚀 **Nasa_Asteroids_Data**

A project that gathers, processes, and displays Near-Earth Object (NEO) asteroid data from NASA’s public API. It turns raw space data into meaningful insights using Python, SQL, and Streamlit, offering a live dashboard for easy exploration and filtering.



📌 **Project Overview**

This project focuses on:

📡 Tracking asteroid close approaches to Earth

⚠️ Analyzing impact threats based on size, velocity, and distance

📊 Providing researchers and learners with a user-friendly dashboard to explore asteroid patterns and behaviors



🧠 **Skills Gained**

🔗 Working with online data using APIs (like NASA's)

📄 Reading and organizing JSON data

🧹 Cleaning and preparing data using Python

📊 Creating and using databases with SQL

🖥️ Building interactive dashboards with Streamlit

⏱️ Filtering and viewing data instantly in real-time



🧩 **Steps Involved**

✅ Step 1: Register for NASA API Access
Started by registering on NASA’s official API portal to receive a personal API key for accessing the Near-Earth Object Web Service.

✅ Step 2: Extract Raw Asteroid Data
Fetched asteroid data using the NASA API in 7-day intervals. Handled pagination to collect over 10,000 records related to close approaches, speeds, sizes, and orbital details.

✅ Step 3: Clean and Structure the Data
Parsed the JSON responses to extract essential attributes. Cleaned and converted the data into proper formats such as dates, floats, and booleans, and split the data into asteroid properties and close approach events.

✅ Step 4: Store Data in a SQL Database
Designed two structured SQL tables to store the cleaned data—one for general asteroid attributes and another for their approach details. Used parameterized insertions to load the dataset into the database.

✅ Step 5: Perform Analytical SQL Queries
Wrote multiple SQL queries to gain insights such as the fastest asteroids, closest approaches, most frequent visitors, and trends across different timeframes. Focused on scientific and safety-related insights.

✅ Step 6: Build an Interactive Dashboard
Developed a Streamlit-based dashboard with filters for distance, velocity, date, and hazard status. Connected the dashboard to the SQL database to allow users to run live queries and instantly visualize results.



📊 **Sample Query Outputs**

Top 10 Fastest Asteroids ➡️ Displays asteroids with the highest velocity.

Miss Distance < 1 Lunar Distance ➡️ Lists asteroids that passed closer to Earth than the Moon.

Hazardous Asteroids ➡️ Filters asteroids marked as potentially hazardous.

Closest Approach Dates ➡️ Shows asteroids sorted by how close their paths were to Earth.



🛠 **Tech Stack Used**

✅ Google Colab – Used for writing Python code, handling API requests, and cleaning data.

✅ MySQL – Used to store structured asteroid data and run SQL queries.

✅ Streamlit – Used to build the interactive web dashboard.

✅ Pandas & Requests – Used for data handling and making API calls.

✅ NASA Open API – The official source of Near-Earth Object data.



🎯 **Business Use Cases**

🛰️ Asteroid Threat Monitoring – Filter by size, speed, and approach frequency

📚 Education – Learn APIs, JSON parsing, SQL, and dashboards

🔍 Real-Time Analysis – Enable researchers to track and query up-to-date NEO events



🧩 **Key Learnings**

Handling real-world API pagination

Transforming JSON into normalized SQL schemas

Writing complex SQL queries for scientific data

Designing an intuitive dashboard for non-coders



📎 **References**

🔗 https://api.nasa.gov/

📘 https://docs.streamlit.io/

🛢️ https://dev.mysql.com/doc/
