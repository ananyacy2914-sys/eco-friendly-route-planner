🌍 Eco-Friendly Route Planner

The Eco-Friendly Route Planner is a smart navigation tool designed to help users travel efficiently and sustainably. By considering traffic, weather, pollution levels, road types, and fuel efficiency, it suggests the most eco-friendly routes. This reduces fuel consumption, costs, and carbon emissions while ensuring smooth travel.

✨ Key Features

🚗 Eco-Friendly Routing → Suggests low-emission, fuel-efficient paths
🌦 Real-Time Data Integration → Uses live APIs for weather, traffic, and air quality
💰 Dynamic Cost Estimation → Estimates fuel cost & consumption for selected routes
🗺 User-Friendly Interface → Interactive map with visual indicators for traffic & weather
🤖 Machine Learning Optimization → Predicts and recommends the most sustainable route options

🛠 Technologies Used

Frontend:HTML, CSS, JavaScript
Backend:PHP
Database:MySQL
APIs:OpenWeatherMap,Traffic APIs,Air Quality & Pollution APIs

📂 Project Structure
eco-friendly-route-planner/
├── index.html          # Homepage
├── dashboard.html      # Dashboard view
├── traffic.html        # Traffic details
├── pollution.html      # Pollution details
├── weather.html        # Weather details
├── script.js           # Frontend logic
├── login1.php          # Login backend
├── register.php        # Registration backend
├── register1.php       # DB insert for user register
├── style.css           # Styles
├── traffic_volume_data.csv # Example dataset
└── README.md

⚙ Setup & Installation
1. Clone the Repository
git clone https://github.com/ananyacy2914-sys/eco-friendly-route-planner.git
cd eco-friendly-route-planner

2. Move Project to XAMPP (Windows Example)
Copy the folder into:
C:/xampp/htdocs/eco-friendly-route-planner

3. Start Server
Open XAMPP Control Panel
Start Apache and MySQL

4. Configure Database
Open phpMyAdmin
Create a database (e.g., eco_route_db)
Import tables as required (users, routes, etc.)
Update database connection details inside PHP files (login1.php, register.php, etc.)

5. Run the App
Open browser:
http://localhost/eco-friendly-route-planner/index.html

🚀 Future Enhancements

Mobile App version (React Native / Flutter)
More APIs for live fuel price & public transport integration
Advanced ML models for better traffic & pollution prediction
User profiles with travel history and CO₂ savings report

📜 License

This project is for educational purposes. Feel free to fork and improve!
