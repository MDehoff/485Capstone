⚾ Trackman Pitching Analysis Dashboard
📊 Overview
The Trackman Pitching Analysis Dashboard is a web-based analytics tool designed to help baseball players, coaches, and analysts evaluate pitching performance using Trackman CSV data.
By simply uploading a CSV file, users can visualize pitch metrics, analyze strengths and weaknesses, and receive data-driven coaching recommendations—all in an interactive dashboard.
🚀 Features
📈 Dashboard Visualizations
Pitch Usage Pie Chart – Shows pitch mix distribution
Velocity Bar Chart – Displays average velocity per pitch type
Spray Chart – Visualizes batted ball locations
Pitch Location Heatmap – Shows pitch placement within the strike zone
📉 Performance Metrics
Total pitches thrown
Average velocity (MPH)
Average spin rate (RPM)
Strike percentage
Whiff percentage
⚖️ Pitch Comparison
Compares each pitch type to optimal benchmarks
Calculates:
Velocity vs optimal
Spin rate vs optimal
Strike & whiff rates
Assigns a letter grade (A–D) for each pitch
🧠 Coaching Recommendations
Identifies:
Best pitch
Weakest pitch
Generates personalized recommendations based on:
Command (strike %)
Swing-and-miss ability (whiff %)
Velocity and spin efficiency
🤖 Machine Learning Module
Compares actual vs predicted pitch locations
Displays:
Average X error
Average Z error
Total distance error
Interactive scatter plot with:
Actual vs predicted points
Connection lines between them
Adjustable sample size (10–100 pitches)
📂 How It Works
Upload a Trackman CSV file
The app uses:
PapaParse → to read CSV data
Chart.js → to generate visualizations
Data is processed in real-time using JavaScript
Results are displayed across multiple tabs:
Dashboard
Performance
Pitch Comparison
Recommendations
ML Model
📄 Required CSV Fields
To fully utilize all features, your CSV should include:
Core Pitch Data
pitch_type
release_speed
release_spin_rate
description
Batted Ball Data (for spray chart)
hc_x
hc_y
events
Pitch Location Data
plate_x
plate_z
Machine Learning Predictions (optional)
pred_x
pred_z
🛠️ Technologies Used
HTML5 – Structure of the app
CSS3 – Styling and layout
JavaScript (Vanilla) – Data processing and logic
Chart.js – Data visualization
PapaParse – CSV parsing
📦 Installation & Usage
Option 1: Run Locally
Download or clone the repository
Ensure all files are in the same directory:
index.html
styles.css
Open index.html in your browser
Option 2: Deploy Online
Upload files to any web hosting service (GitHub Pages, Netlify, etc.)
🎯 Use Cases
Player development analysis
Coaching insights and feedback
Pitch design evaluation
Baseball analytics projects
Research and academic presentations
⚠️ Notes
The ML model tab requires prediction columns (pred_x, pred_z)
Missing data fields will limit certain visualizations
Works entirely client-side (no backend required)
🔮 Future Improvements
Real machine learning model integration
Player comparison tools
Export reports (PDF/CSV)
Advanced pitch movement analytics
Team-wide dashboards
👨‍💻 Author
Developed as a baseball analytics project focused on combining data science and sports performance.
