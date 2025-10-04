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

![Metrices - Grafana](images\image-1.png)

![Real-time Graph showing CPU usage](images\image-2.png)

![Network Upload Speed (MB/s)](images\image.png)