# HealthcareSecurityProject
 
# Healthcare Security System Project

## Project Overview
This project focuses on the development of a robust cybersecurity system tailored for a healthcare organization. The primary goal is to safeguard sensitive patient data, ensure uninterrupted operations, and proactively address cybersecurity threats. By integrating automation, data analytics, and machine learning, this system enhances threat detection, incident response, and overall organizational resilience. The system also includes a disaster recovery plan to mitigate risks and ensure rapid recovery from potential disruptions.

## Installation
Follow these steps to set up the project:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your_username>/HealthcareSecurityProject.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd HealthcareSecurityProject
   ```
3. **Install required dependencies**:
   Ensure Python is installed on your system, then run:
   ```bash
   pip install -r requirements.txt
   ```
4. **Setup environment variables**:
   Configure any required environment variables in a `.env` file.

## Usage
1. **Scripts**:
   - Navigate to the `/scripts` directory to access Python scripts for directory monitoring, network scanning, and email alerts.
   - Example command to run a script:
     ```bash
     python scripts/monitor_directory.py
     ```
2. **UML Diagrams**:
   - UML diagrams are available in the `/diagrams` directory to provide a visual representation of the system architecture and processes.
3. **Documentation**:
   - System requirements and planning documents are located in the `/documentation` directory.
4. **Results**:
   - Analysis results, including network scans and vulnerability assessments, are stored in the `/results` directory.

## Team Members
- **Tomi**: Project Manager
- **Benita, Jimmy**: Systems Modelers
- **Dahab,Trung **: Python Developers
- **Dahab,Saam**: Data Analysts

## Documentation
The `/documentation` folder includes:
- UML diagrams
- System requirements
- Planning documents detailing the design and implementation process.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Tutorial
### Directory Monitoring
- Run the monitoring script to track file changes in a specified directory:
  ```bash
  python scripts/monitor_directory.py
  ```
- Log files will be generated in `system_security.log`.

### Network Scanning
- Use the network scanning script to identify vulnerabilities:
  ```bash
  python scripts/scan_network.py
  ```
- Results will be saved in `network_scan_results.txt`.

### Email Alerts
- Configure the `send_alert` function to notify administrators of detected issues.
- Example usage:
  ```bash
  python scripts/send_alert.py
  ```

By following these instructions, team members and users can efficiently set up and utilize the Healthcare Security System.
