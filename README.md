<div align="center">
<img width="555" alt="EDS Logo" src="https://github.com/SarahAlh/EDS/assets/78688276/115b44f7-0021-4453-83f5-e83fd3ec69c1">
</div>

## Description

The Ensemble Defense System (EDS) is a powerful cybersecurity framework designed to safeguard computer networks from cyber threats. EDS combines the capabilities of multiple security tools, creating a comprehensive defense strategy against cyber-attacks.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Screenshots](#screenshots)

## Installation

1. **Clone the Repository**: 

   First, clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/sarahalh/EDS.git
   ```

3. **Navigate to the Project Directory**:

   Change your working directory to the project folder:
   ```
   cd EDS
   ```

4. **Configure Environment Variables**:

   Edit the `enVariable.env` file in the project directory and set the appropriate parameters based on your environment.

5. **Build and Start the Containers**:

   Run the following command to start the Docker containers, passing the environment variables from the `enVariable.env` file:
   ```
   docker-compose --env-file enVariable.env up --build
   ```
   This will build and start the required Docker containers with the provided environment variables.

6. **Access the System**:
   Once the containers are up and running, you can access the system through Kibana. Open your web browser and navigate to:
   ```
   http://localhost:5601/
   ```
   This URL should allow you to access the Kibana web interface, where you can interact with the system.

## Features

Our system offers a wide range of features designed to enhance your network security and monitoring capabilities. Here are some key features:

- **Real-time Alerts:** Receive real-time alerts for security incidents, anomalies, and potential threats from both Slips, Suricata, and Zeek.

- **Anomaly Detection:** Explore different types of attacks, including Denial-of-Service (DoS), Port Scanning, and Privilege Escalation attacks, and gain insights into their patterns.

- **Zeek Logs:** View detailed Zeek logs, providing you with a deeper understanding of network activity and traffic.

- **Customizable Dashboards:** Tailor your experience with customizable dashboards and visualizations, allowing you to focus on the data that matters most to you.

- **Open-Source:** Our system is built on open-source technologies, giving you flexibility and the ability to contribute to its development.


## Screenshots
### Suricata and Slips Alerts Page
This page contains the alerts from both Slips and Suricata
<div align="left">
<img width="666" alt="Screenshot 2023-10-16 at 2 00 32 PM" src="https://github.com/SarahAlh/EDS/assets/78688276/a432fc3c-8424-49db-8e50-d3aef2211198">
</div>

### Anomaly Detection Page
On the Anomaly Detection page, there are three tabs:

1. **Denial-Of-Service Attack Page:**
   <div align="left">
<img width="666" alt="Screenshot 2023-10-16 at 2 14 42 PM" src="https://github.com/SarahAlh/EDS/assets/78688276/3bbbcd6b-f928-4af6-b97d-14fc39e75933">
</div>

2. **Port Scanning Attack Page:**
      <div align="left">
<img width="666" alt="Screenshot 2023-10-16 at 2 07 50 PM" src="https://github.com/SarahAlh/EDS/assets/78688276/f2ed9d54-84f4-4cb5-a322-60a5882d702b">
</div>

3. **Privilege Escalation Attack:**
         <div align="left">
<img width="666" alt="Screenshot 2023-10-16 at 2 09 07 PM" src="https://github.com/SarahAlh/EDS/assets/78688276/a88375f5-75f1-4373-b304-7bddc0066ccb">
</div>

### Zeek Logs Page
The Zeek Logs Page:
         <div align="left">
<img width="666" alt="Screenshot 2023-10-16 at 2 14 56 PM" src="https://github.com/SarahAlh/EDS/assets/78688276/496f81e0-7b4b-4650-b4c2-b6324be0fe8e"></div>

