Traditional traffic signals operate on fixed timers, which do not adapt to real-time road conditions, causing unnecessary delays, pollution, and fuel consumption.
This project uses AI (Computer Vision + ML) and Cloud Computing to build a smart, automated traffic control system capable of:

<li>Detecting the number of vehicles using video feeds.
<li>Predicting congestion.
<li>Dynamically changing signal timings.
<li>Monitoring city-wide traffic using a cloud dashboard.
<li>Alerting authorities about accidents or unusual events.

Core Idea

Use AI models (like YOLOv8) to analyze live traffic camera feeds and send real-time vehicle counts to the cloud. A cloud-based backend calculates the optimal signal duration and sends it back to the traffic lights.
It’s a real-time, AI-powered, cloud-integrated traffic management system.

Key Objectives

<li>Detect and count vehicles from live CCTV/video streams.
<li>Identify congestion levels (low, medium, high).
<li>Adjust traffic light timings automatically.
<li>Provide a live traffic dashboard for monitoring.
<li>Store data in cloud for analytics and predictions.
<li>Reduce congestion, waiting time, and fuel consumption.

CCTV Camera/Live Feed  AI Engine (YOLOv8 / OpenCV) Vehicle Count + Congestion Level Cloud Backend (AWS / IBM Cloud / Azure) Decision Engine (Signal Timing Algorithm) Traffic Signal Controller (Simulated or Real) Dashboard for Monitoring (React/Streamlit)
