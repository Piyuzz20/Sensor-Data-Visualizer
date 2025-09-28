# Sensor-Data-Visualizer 

## Overview
This project simulates multiple sensor data streams (e.g., Temperature and Humidity) and visualizes them in real-time using Python. It also logs all sensor readings to a CSV file for future analysis.
<br>
The system demonstrates how engineers can monitor live sensor data for applications like environmental monitoring, IoT dashboards, or industrial sensors


## Feature 


Simulate real-life sensor data for any sensors (here Tempreture and Humidity sensor).

Real-time plotting of multiple sensor values using Matplotlib.

Data logging: all incoming sensor readings are stored in a CSV file for analysis.

Sliding window plotting: shows the most recent N readings for performance.
<br>


## Technologies & Libraries


Python 3.x

Matplotlib → real-time plotting (animation.FuncAnimation)

Pandas → logging data to CSV

Collections (deque) → efficient buffer for plotting

Datetime & Random → generate timestamps and simulated sensor data
