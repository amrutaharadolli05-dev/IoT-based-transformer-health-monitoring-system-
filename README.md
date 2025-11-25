# IoT-based-transformer-health-monitoring-system-
IoT-based Transformer Health Monitoring System using Arduino with temperature, current, oil level, and oil quality sensors. It provides real-time monitoring of transformer conditions, detects faults like overheating or low oil level, and helps improve safety and predictive maintenance.

Overview  
This project is a real-world industrial monitoring system that uses IoT to track the health of electrical transformers. It monitors key parameters such as temperature,oil level, and current to detect faults and prevent transformer failures.

Problem Statement  
- Transformers are critical assets in power systems and can fail due to overheating or insulation degradation.  
- Manual inspection is costly, time-consuming, and can miss early fault signals.  
- There is a need for a *remote, real-time monitoring* solution to reduce downtime and maintenance costs.

 Objectives  
1. Continuously monitor transformer parameters (temperature, oil level, current).  
2. Detect anomalies or fault conditions early.  
3. Send real-time data to an IoT platform for monitoring.  
4. Enable predictive maintenance and alert generation.
   

Components Used  
Microcontroller (Arduino)  
Temperature sensor  
Oil-level sensor   
Current sensor
Power supply  
IoT communication: Wi-Fi  
Cloud platform or database (ThingSpeak)   
LED and Buzzer for alerts  

Working Principle  
1. Sensors (temperature, current, oil) continuously read transformer parameters.  
2. Microcontroller processes these sensor values in real time.  
3. If any parameter crosses defined thresholds → fault or warning condition buzzer starts to make sound.  
4. Upload sensor data periodically (or on threshold breach) to an IoT platform.  


