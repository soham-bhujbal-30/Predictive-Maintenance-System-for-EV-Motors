🔧 Predictive Maintenance System for EV Motors (IoT + ThingSpeak)
An IoT-based predictive maintenance solution for Electric Vehicle (EV) motors, designed to monitor key parameters, detect anomalies, and predict faults using ThingSpeak for cloud data storage, analysis, and visualization.

🚀 Features
Real-time Sensor Data Acquisition (temperature, vibration, current, RPM)

Wi-Fi Enabled Data Upload to ThingSpeak via ESP32

Live Graphs & Historical Trends on ThingSpeak Channels

Custom MATLAB Analysis scripts in ThingSpeak for anomaly detection

Automated Alerts using ThingSpeak’s ThingHTTP & React features

Low-Cost & Scalable solution for EV fleet monitoring

🛠️ Tech Stack
Hardware: ESP32, Vibration Sensor, Current Sensor, Temperature Sensor

Platform: ThingSpeak IoT Analytics Platform

Communication: MQTT / HTTP API over Wi-Fi

Data Processing: MATLAB scripts within ThingSpeak

Visualization: ThingSpeak charts & dashboards

📈 Use Cases
Detecting bearing wear, overheating, or vibration issues in EV motors

Preventive maintenance scheduling to reduce downtime

Monitoring motor health remotely in real-time

📂 Repository Structure
bash
Copy
Edit
/hardware      → Circuit diagrams & sensor connections  
/firmware      → ESP32 Arduino code for sensor reading & ThingSpeak upload  
/matlab        → ThingSpeak MATLAB analysis scripts  
/docs          → Setup guides, usage instructions, and documentation  
📜 How It Works
Sensors collect EV motor parameters in real time.

ESP32 sends data to ThingSpeak channel via Wi-Fi.

MATLAB scripts on ThingSpeak analyze trends and predict faults.

Alerts triggered via ThingSpeak React when anomalies are detected.
