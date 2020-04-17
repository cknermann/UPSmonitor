# UPSmonitor
This repo provides the code to set up the monitoring and alerting for an APC UPS with Node-RED, InfluxDB and Grafana. It's just some example code, which comes "as-it-is" without any warranties or support. Please feel free to adapt it to suit your needs.

![UPSmonitor Grafana dashboard](media/grafana_dashboard.png)

I have configured and tested the Node-RED flow and the Grafana dashboard with two APC UPS models,  one "Back-UPS RS 900G" and an older "Back-UPS CS 650", both connected via USB to a Raspberry Pi 3 with Rasbian Buster Lite and Node-RED, InfluxDB and Grafana all locally installed.