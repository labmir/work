Python-Hello_World_web_server-with-Prometheus-Grafana
========

A docker-compose example with docker of python webserver together with monitoring solution for Docker hosts and containers with [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), [cAdvisor](https://github.com/google/cadvisor),
[NodeExporter](https://github.com/prometheus/node_exporter)



![Host](https://raw.githubusercontent.com/labmir/fincana/master/pics/scrn0.png)
![Host](https://raw.githubusercontent.com/labmir/fincana/master/pics/scrn1.png)

## Install

### Edit .env (optional):
```
ADMIN_USER=admin  
ADMIN_PASSWORD=admin
```

### Clone this repository on your Docker host, cd into cloned directory and run compose up:

```
git clone https://github.com/labmir/fincana.git 
docker-compose up -d
```


## Usage:

* Hello World web-page `http://localhost:8001`
* Grafana (visualize metrics) `http://localhost:3000`
* Prometheus (metrics database) `http://localhost:9090`
* 
* NodeExporter (host metrics collector)
* cAdvisor (containers metrics collector)
* Caddy (reverse proxy and basic auth for prometheus)


