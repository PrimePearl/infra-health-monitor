# Infrastructure Health Monitor

A lightweight Python & Bash-based tool to monitor server health metrics like uptime and disk usage, and send alerts via Slack.

## 🔧 Tools & Technologies

- Python 3
- Bash
- Prometheus (optional integration)
- Slack Webhooks
- Cron (for scheduling)

## 📁 Files

- `monitor.py`: Python script to check disk space and log server status
- `disk_check.sh`: Simple Bash version for checking disk usage
- `README.md`: Project documentation

## 🚀 Usage

Schedule the script using `cron` or run it manually:
```bash
python monitor.py
