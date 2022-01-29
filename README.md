# :gear: SRE Tools

## :white_check_mark: About
This is an sample project to set up the basic needed tools for infrastructure monitoring. 

| <!-- --> | <!-- --> | 
--------------- |  ---------------
First Launch:   | **2022-01-29**    
Last Revision:  | **2022-01-29**    
Version:        | **1.0**


## :white_check_mark: Requirements

1. [Docker](https://docs.docker.com/get-docker/)


## :white_check_mark: Included tools

- [x] [Prometheus](https://prometheus.io)
- [x] [Grafana](https://grafana.com)
- [x] [AlertManager](https://prometheus.io/docs/alerting/latest/alertmanager/)
- [x] [Blackbox](https://github.com/prometheus/blackbox_exporter)
- [x] [cAdvisor](https://github.com/google/cadvisor)

## :white_check_mark: How it works

Everything can be done from Makefile. For example ``` make build ``` will pull all needed images to up the tools.