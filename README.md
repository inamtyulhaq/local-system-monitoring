# Local System Monitoring

This is a very simple project built with Prometheus Grafana and Windows Exporter.
It visualizes key system metrics (like CPU usage) from your own computer in real time.

I have used Prometheus, Grafana and Windows Exporter.

I used Windows Exporter as I was working on Windows 11. You can use Node Exporter if you are on Linux or Mac.

# How to make this project

It's very simple. Download Grafana, Prometheus and Windows/Node Exporter.
Make a simple configuration change in prometheus.yml file.
Run windows/node exporter, prometheus.
Now run Grafana. In data source, add Promtheus and then the local host link.
You are done. Now, you can create your customized dashboards.

# Screenshots:

<img width="1919" height="841" alt="image-1" src="https://github.com/user-attachments/assets/83b45bcb-c68f-4c8b-9a8a-8f3e6128601b" />
<p align="center"><em>Metrices - Grafana</em></p>

<img width="1448" height="705" alt="image" src="https://github.com/user-attachments/assets/93e083e3-b88e-4998-810b-f2e7c82c11ff" />
<p align="center"><em>Real-time Graph showing CPU usage</em></p>

<img width="1448" height="705" alt="image" src="https://github.com/user-attachments/assets/dba087e0-5d41-44ba-9162-1ee674afbae2" />
<p align="center"><em>Network Upload Speed (MB/s)</em></p>
