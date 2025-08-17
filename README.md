# Fruit-Quality-And-Inventory-Management-using-IoT-and-ML
📌 Overview

This project presents an IoT-enabled Smart Warehouse System for monitoring fruit freshness and managing inventory. By integrating embedded sensors, cloud services, and machine learning models, the system ensures real-time tracking of environmental conditions (temperature, humidity, ethylene gas, weight, and light exposure), predicts spoilage, and optimizes stock rotation.

The solution is designed to be scalable, affordable, and user-friendly, benefiting farmers, distributors, and retailers by reducing food waste, improving shelf life, and enhancing supply chain efficiency.

🚀 Features

✅ Real-Time Monitoring – Track temperature, humidity, gas levels, weight, and light.

🤖 Spoilage Prediction – ML models (Random Forest, AdaBoost, XGBoost) estimate ripeness & shelf life.

📦 Smart Inventory Management – Alerts & optimized stock dispatch.

☁️ Cloud Integration – Firebase for live monitoring, history, and device control.

📊 Interactive Dashboard – React.js + Flask/Django interface with real-time visualization.

🧠 Edge Intelligence – TinyML models running directly on NodeMCU for offline capability.

🛠️ Tools & Technologies

Hardware: NodeMCU (ESP8266/ESP32), DHT22, MQ-135, HX711 + Load Cell, LDR Sensor, Relay Modules
Software: Python, Flask/Django, React.js, Firebase, TensorFlow Lite, scikit-learn, XGBoost
Protocols: MQTT / HTTP
Cloud: Firebase, AWS (optional)

⚙️ System Architecture

Sensor Nodes → Collect environmental data per basket.

NodeMCU Controller → Processes & transmits data.

Cloud (Firebase) → Stores data, manages devices, provides real-time sync.

ML Models → Predict spoilage & shelf life.

Dashboard → User-friendly visualization & control.

📊 Results

🔹 User Interface Dashboard
<img width="1919" height="960" alt="image" src="https://github.com/user-attachments/assets/b8635fa0-c78c-4e36-9c31-1eeca32233ea" />

🔹 Sensor Reliability and Data Consistency
<img width="1309" height="900" alt="image" src="https://github.com/user-attachments/assets/b07d3e2a-e339-4aa9-b589-44c62c6476c5" />

🔹 Real time firebase Dashboard
<img width="442" height="297" alt="image" src="https://github.com/user-attachments/assets/b0989333-22ae-40c2-a762-08fe2342c4a9" />

🔹 Sales and Price Prediction Interface.
<img width="772" height="475" alt="image" src="https://github.com/user-attachments/assets/785cbeb3-7b96-4114-84b5-4dd7d14803ba" />

🔹 Circuit Connections
<img width="539" height="391" alt="image" src="https://github.com/user-attachments/assets/a5ef48f1-9eb5-42f6-94e3-663d6d7f16de" />


📈 Future Scope

🧠 TinyML integration for offline spoilage prediction.

🔗 Blockchain for secure, immutable data logging.

📱 Android/iOS app for real-time mobile monitoring.

🏭 Multi-warehouse AI optimization for logistics.


Credentials

Username: admin@gmail.com 
Password: Admin@123

👨‍💻 Contributors

Pratik Lakkundi (CSE)

B Tanuj (CSE)

Paramesh N T (CSE)

Yashika P (CSE)

Kiran Kumar M (ME)

Guide: Dr. P. R. Venkatesh (Associate Professor, RVCE)

📜 License

📘 This project was developed as part of the Interdisciplinary Project (XX367P) at RV College of Engineering.
All rights reserved © 2025.
