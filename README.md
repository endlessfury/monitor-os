# monitor-os
docker compose with stack to monitor your os resources and processes
## How to use
1. Clone git repo
2. Install docker and docker-compose
3. Run `docker-compose up` if you want to see the logs, add `-d` if you want to dettach it
4. Check the prometheus targets if exporters are up
5. Login to grafana (admin:admin) and add datasource prometheus (no encryption or authentication), use dns names (local dns within docker-compose network)
6. Import dashboards from jsons
---
#### Sources:
https://github.com/prometheus/node_exporter

https://github.com/ncabatoff/process-exporter
