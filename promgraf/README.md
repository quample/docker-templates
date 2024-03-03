#Prometheus-Grafana docker-compose stack for Linux host monitoring & observability

This stack is used to setup a Prometheus and Grafana docker stack for monitoring a Linux node/host, using docker compose.
In order to achieve the linux host system monitoring, I've used the prom/node\_exporter docker container; run as a seperate service in the docker-compose stack.

Inspired by the tutorial from Grafana Labs -  https://grafana.com/docs/grafana-cloud/send-data/metrics/metrics-prometheus/prometheus-config-examples/docker-compose-linux/

