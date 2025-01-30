
# Application Uptime Checker

This is a simple Python-based GUI application to check the uptime status of a given web application URL. The application uses the `requests` library to send HTTP GET requests and provides real-time feedback on whether the given URL is **UP** or **DOWN**, using the `tkinter` library for the graphical interface.

## Features

- Easy-to-use interface:** Enter a URL and check its status with a single click.  
- Error Handling:** Handles invalid URLs, connection errors, and request timeouts.  
- Responsive UI:** The application remains responsive while checking the URL.  
- Status Indication:** Displays results in green (UP) or red (DOWN).  

## Prerequisites

Ensure you have the following installed:

- **Python 3.x**  
- Required Python libraries:

  Install them using:

  ```bash
  pip install requests validators
  ```

## Installation

1. Clone the repository or copy the script to your local machine.

   ```bash
   git clone https://github.com/your-repo/application-uptime-checker.git
   cd application-uptime-checker
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python uptime_checker.py
   ```

## Usage

1. Open the application.
2. Enter a valid URL in the input field (e.g., `https://www.google.com`).
3. Click **"Check Status"** to see whether the application is UP or DOWN.
4. The result will be displayed in the interface.

## Example

- **Input:** `https://www.google.com`  
  **Output:** `The application at https://www.google.com is UP.`  

- **Input:** `https://invalid-url.com`  
  **Output:** `The application at https://invalid-url.com is DOWN.`  

---

# Cpu-usage
# System Health Monitoring Script

## Overview
This Python script monitors system health by checking CPU usage, memory usage, disk space, and the number of running processes. It logs warnings when resource usage exceeds predefined thresholds.

## Features
- Monitors CPU, memory, and disk usage.
- Logs warnings when thresholds are exceeded.
- Displays the number of running processes.
- Saves logs in `system_health.log`.

## Prerequisites
Ensure you have Python installed (version 3.x recommended) and install the required package:

```bash
pip install psutil
```

## Installation
1. Download or clone the script.
2. Install dependencies using `pip install psutil`.
3. Run the script with:
   ```bash
   python system_health.py
   ```

## Configuration
Modify the threshold values in the script as needed:
```python
CPU_THRESHOLD = 80  # CPU usage percentage
MEMORY_THRESHOLD = 80  # Memory usage percentage
DISK_THRESHOLD = 90  # Disk usage percentage
```

## Logging
Logs are saved in `system_health.log`. Warnings are recorded when thresholds are exceeded.

## Enhancements
Future improvements could include:
- Continuous monitoring with scheduled intervals.
- Email or notification alerts for critical issues.
- More detailed process monitoring.

## License
This script is free to use and modify.

## Author
GEMBALI KEERTHIVARDHAN


