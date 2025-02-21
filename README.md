# Ansible Prometheus stack
This Ansible playbook automaticaly install Prometheus, Grafana, Alertmanager and Node Exporter  on your monitoring servers.

The script is executed in several stages:

1) Update apt package index
2) Install dependencies
3) Add Prometheus user
4) Download and install Prometheus
5) Create Prometheus directories
6) Create Prometheus configuration file
7) Create systemd service for Prometheus
8) Start and enable Prometheus service
9) Download and install Alertmanager
10) Create Alertmanager directories
11) Create Alertmanager configuration file
12) Create systemd service for Alertmanager
13) Start and enable Alertmanager service
14) Download and install Grafana
15) Create systemd service for Grafana
16) Start and enable Grafana service
17) Download and install Node Exporter
18) Create systemd service for Node Exporter
19) Start and enable Node Exporter service
