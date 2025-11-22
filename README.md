# IPL_data_visualization
IPL always confused me, so I built this project to understand it better in a visual and easy way.
🏏 IPL Stats Place

A Python-based interactive data visualisation tool that showcases IPL history using Pandas and Matplotlib.

📌 Overview

This project provides a menu-driven interface for exploring IPL statistics from 2008 to 2025. It includes multiple datasets and graphs for Orange Cap, Purple Cap, winners, runner-ups, centuries, hat-tricks and team-specific breakdowns.

Users can visualise performance trends across teams and seasons using clean, colorful graphs.

✨ Features
🔶 Orange Cap Analysis

Bar chart of total runs by the Orange Cap winners for each year

Color-coded by team

Dedicated CSK/RCB/PBKS/MI histograms

🟣 Purple Cap Analysis

Bar chart of wickets taken by Purple Cap winners per year

Color-coded by team

Team-specific histograms

🔥 Orange vs Purple Comparison

Line plot comparing how many times each team has won Orange and Purple Caps

Shows trends and dominance over the years

🏆 Winners (Cumulative Analysis)

Bar chart of total titles per team

Line chart showing cumulative wins across seasons

🥈 Runner-Ups (Cumulative Analysis)

Bar chart of runner-up appearances

Line chart showing cumulative runner-up counts

💯 Centuries

Bar chart of number of seasons each team produced a century

Player-wise century count colored by team

🎯 Hat-Tricks

Number of hat-tricks per team

Player-wise hat-trick distribution

🟡 Team-Specific Panels

CSK, RCB, PBKS, and MI histograms for Orange & Purple Cap years

🖥️ Running the Program

Make sure you have Python installed. Then install required libraries:

pip install pandas matplotlib


Run the main program:

python your_script_name.py


You’ll get an interactive menu to choose different IPL stats and visualisations.

📂 Project Structure
IPL-Stats/
│
├── main_script.py     # Contains all functions and main menu
├── README.md          # Project documentation
└── (Optional future additions...)

📊 Graphs Used

Bar charts

Line charts

Histograms
All built with Matplotlib and styled with team color dictionaries.

🏗️ Data Handling

All data is created through Pandas DataFrames inside the functions.
No external CSV files are required.

🚀 Future Improvements

Add GUI with Tkinter or Streamlit

Export charts as images

Add CSV import/export support

Add team logo integration

Add playoff, points table and MVP datasets

🧡 Credits

Created with Python, Pandas, Matplotlib...
