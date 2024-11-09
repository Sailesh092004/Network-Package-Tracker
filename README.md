# Network-Package-Tracker
A Python-based network monitoring tool that tracks latency, packet loss, and bandwidth usage with real-time alerts and logging.


Sure! Here’s a detailed description and the steps to install the prerequisites for your project, formatted for GitHub.

Network Performance Monitor
Overview
The Network Performance Monitor is a Python-based application designed to monitor various aspects of a network’s performance in real-time. This tool tracks network parameters such as:

Latency: The time it takes for a packet to travel from your computer to a specified IP address and back.
Packet Loss: The percentage of lost packets during the ping tests.
Bandwidth Usage: The amount of data sent and received over the network.
Packet Loss Rate: A calculated percentage representing the ratio of lost packets to total packets sent.
The application provides real-time monitoring with the help of a graphical user interface (GUI) built using Tkinter. The data is continuously updated every few seconds, logged to text files for later analysis, and alerts the user if any of the monitored metrics exceed predefined thresholds.

The program is useful for network administrators, developers, or anyone interested in tracking the performance and reliability of their network over time.

Features
Real-time Network Monitoring: Monitors latency, packet loss, and bandwidth usage continuously.
Threshold-based Alerts: Alerts when latency exceeds a certain threshold, when packet loss is high, or when bandwidth usage surpasses a limit.
Logging: Saves network statistics to local text files for historical analysis.
Graphical User Interface (GUI): Provides a user-friendly interface to display real-time monitoring data.
Customizable Settings: You can modify thresholds for latency, packet loss, and bandwidth within the code.

 Install the Required Packages
Once the virtual environment is activated (or globally if you chose to skip this step), run the following command to install the necessary dependencies:

bash
Copy code
pip install psutil ping3 schedule
Note: tkinter is included by default in most Python installations. If it’s not already installed, you can install it separately.

Windows:
bash
pip install tk

macOS (if necessary):
bash
brew install python-tk

Linux (Ubuntu/Debian-based systems):
bash
sudo apt-get install python3-tk
