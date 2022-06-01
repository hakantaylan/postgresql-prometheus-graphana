# How to monitor PostgreSQL with Prometheus and Grafana | Docker
How to monitor PostgreSQL with Prometheus and Grafana | Docker

Run Docker Compose
```bash
docker-compose up
```
Check status of Prometheus and Postgre Exporter
```bash
http://localhost:9090/targets
```
![Alt text](images/prometheus.png?raw=true "Prometheus")

Visit Grafana Dashboard

Default
```bash
User: admin
Password: admin
```
```bash
http://localhost:3000
```
![Alt text](images/graphana.png?raw=true "Graphana")

Add data source

![Alt text](images/graphana-add-datasource.png?raw=true "Graphana Add Datasource")

Save And Test

![Alt text](images/graphana-save-test.png?raw=true "Graphana Save And Test")

Import PostgreSQL Dashboard for Prometheus

For this we will use a Dashboard created by the community

![Alt text](images/graphana-import-dashboard.png?raw=true "Graphana Import DashBoard")

https://grafana.com/grafana/dashboards/9628

Import JSON of code

![Alt text](images/graphana-import-dashboard2.png?raw=true "Graphana Import DashBoard2")

![Alt text](images/graphana-import-dashboard3.png?raw=true "Graphana Import DashBoard3")

Code: 9628

Dashboard

![Alt text](images/graphana-final.png?raw=true "Graphana Dashboard Final")
