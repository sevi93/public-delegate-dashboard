# public-delegate-dashboard

This repository contains the deployment tools of public dashboard version, of [tbw_node_monitoring](https://github.com/sevi93/tbw_node_monitoring)

This tool has a dependency with [tbw_exporter_api](https://github.com/sevi93/tbw_exporter_api) in order to display all the TBW and Network metrics on the dashboard

# Configuration

Change `TBW_EXPORTER_API` with the tbw_exporter_api IP endpoint in :

```
public-delegate-dashboard/prometheus/prometheus.yml
````

# Setup

```
./install.sh
```
Go to `http://node_ip:3100` to access grafana dashboard

# Reverse proxy

It is advised to setup a reverse proxy in front of the grafana, in order to do that, follow : [grafana documentation](https://grafana.com/tutorials/run-grafana-behind-a-proxy/) 
