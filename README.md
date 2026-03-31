## SOC Automation Project

## Integration of Wazuh with SocTalk for Security Monitoring

## Project Overview

This project focuses on building a Security Operations Center (SOC) environment using SocTalk and exploring its integration with Wazuh.

The objective was to simulate real-world cyber attacks and visualize them through a professional SOC dashboard.

# Technologies Used
SocTalk (Security dashboard & investigation platform)
Wazuh (Threat detection system)
Docker (Containerization)
PostgreSQL (Database)
Vite (Frontend)
## System Setup
Step 1: Clone Repository
git clone 
cd soctalk-project
Step 2: Run Containers
docker compose up --build
# Access the Application

Frontend Dashboard:

http://localhost:5173

Backend API:

http://localhost:8000
## Challenges Faced
Orchestrator required API key
Wazuh integration was complex
No direct API for event ingestion
Dashboard showed no real events
## Solution Approach

Instead of full integration, attack scenarios were simulated to demonstrate SOC behavior.

## Simulated Attacks
Brute force login attempts
Malware detection
Suspicious IP activity
## Dashboard
SocTalk Dashboard (Actual)
Running successfully
No real events visible
Simulated SOC Dashboard
Shows attack scenarios
Displays severity and alerts
## Results
Successfully deployed SOC platform
Understood investigation workflow
Simulated real-world attack scenarios
Demonstrated dashboard-based analysis
## Future Improvements
Full Wazuh integration
Real-time log ingestion
Automated alert handling
Cloud deployment
