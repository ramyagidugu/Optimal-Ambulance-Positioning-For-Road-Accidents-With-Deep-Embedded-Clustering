# Optimal-Ambulance-Positioning-For-Road-Accidents-With-Deep-Embedded-Clustering
Road accidents are a major global issue, leading to millions of deaths and injuries each year. Urban areas, with growing vehicle density, are particularly vulnerable. This project presents a smart ambulance deployment system to reduce emergency response times and improve road safety using data-driven methods.

🔍 Objective
To minimize ambulance response time and enhance road safety by:

Identifying accident-prone zones using clustering techniques.

Strategically positioning ambulances based on risk patterns.

🧠 Solution Overview
This system utilizes Deep Embedded Clustering (DEC) to determine optimal ambulance placement. Unlike traditional clustering methods, DEC learns meaningful data patterns and groups accident-prone locations into compact, well-separated clusters. This approach ensures accurate and efficient ambulance coverage in critical zones.

🏗️ Tech Stack
Frontend: HTML, CSS, JavaScript

Backend: Django

Database: MySQL

Machine Learning: Deep Embedded Clustering (DEC), Cat2Vec for data embedding

Tools: WAMPServer, Python, Jupyter Notebook

📊 Dataset
Real-world data from Nairobi, Kenya

Includes traffic accident records, road segment details, and weather data

🔧 Key Features
95% model accuracy using DEC

Distance Score of 7.581 – outperforms traditional clustering methods

Cat2Vec embeddings used to convert categorical data while preserving relationships

Distance Scoring Algorithm to validate predicted ambulance positions

Exploratory Data Analysis (EDA) to identify accident patterns

📌 Contributions
Pinpoints high-risk zones using advanced clustering

Provides data-backed ambulance deployment strategies

Scalable for large and complex datasets

Incorporates diverse factors (traffic, roads, weather) for better precision


