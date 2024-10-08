# BoostMyTab

## Overview

BoostMyTab is a web-based tool designed to optimize and enhance the performance of Android tablets. Utilizing Flask and ADB, this tool provides users with a simple and intuitive interface to run various optimization scripts, monitor resource usage, and even remotely control the tablet using scrcpy.

## Features

- **Manage Unnecessary Processes**:
  - Disable or enable Google, Samsung, and miscellaneous bloatware.
  - Disable or enable the virtual keyboard.
  
- **Performance Optimization**:
  - **Power & Battery**: Disable or enable power saving mode.
  - **Screen Brightness**: Set screen brightness to minimum or maximum levels.
  - **CPU Management**: Set the CPU governor to performance or balanced mode.
  - **Animations**: Turn animations on or off to improve responsiveness.
  - **Background Processes**: Limit or unlimit background processes.
  - **Network Optimization**: Boost or reset Wi-Fi and network settings.

- **System Management**:
  - **Recovery Mode**: Enter recovery mode for system troubleshooting.
  - **Device Management**: List all devices connected to the ADB server.
  - **Tablet Management**: Restart the tablet.
  - **Remote Access to Tablet**: Use scrcpy to remotely control the tablet from a PC.
  
## Getting Started

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/BoostMyTab.git
    cd BoostMyTab
    ```

2. **Set up the virtual environment**:
    ```sh
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Flask application**:
    ```sh
    flask run
    ```

5. **Open your browser and navigate to** `http://127.0.0.1:5000`.

## Usage

- **Manage Unnecessary Processes**:
  - Click the corresponding buttons under each section (Google Apps, Samsung Apps, Miscellaneous, Keyboard) to disable or enable specific services.

- **Performance Optimization**:
  - Adjust power, screen brightness, CPU, and animation settings to optimize tablet performance.
  - Manage background processes and network settings for better resource management.

- **System Management**:
  - Enter recovery mode, list connected devices, restart the tablet, or connect the tablet to your PC for remote control using scrcpy by clicking "Connect Tab to PC".

## Notes

- For maximum performance, it is recommended to disable all unnecessary processes and optimizations. You can always re-enable them if needed.
- Ensure that USB debugging is enabled and authorized to allow proper communication between the tablet and BoostMyTab.
