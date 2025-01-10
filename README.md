
# Cybersecurity Threat Monitoring

A project to monitor network traffic, detect threats, and log incidents for analysis. Built with Python and Flask.

## Features
- Monitor live network traffic.
- Detect potential threats like port scanning.
- Log suspicious activities in a database.
- View threats on a web-based dashboard.

## Installation
1. Clone this repository:

git clone https://github.com/yourusername/cybersecurity-threat-monitoring.git

2. Set up the Python environment:

python3 -m venv venv source venv/bin/activate pip install -r requirements.txt


## Usage
1. Run the monitoring script:
sudo python3 scripts/monitor.py
2. Start the dashboard:
python3 dashboard/app.py
3. Visit `http://127.0.0.1:5000` to view the logs.

## License
This project is licensed under the MIT License.
