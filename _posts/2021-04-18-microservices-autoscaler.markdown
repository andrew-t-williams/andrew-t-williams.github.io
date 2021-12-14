---
layout: default
title:  "Microservices Autoscaler"
description: "A cloud-based microservises server that horizontally autoscales based on demand."
date:   2021-04-18 14:00:00 -0800
core-tools: >-
    Python
    JavaScript
    Docker
tools: >-
    Cybera
    Redis
    Flask
    WebSocket
    Plotly
---

# Microservices Autoscaler

Docker swarm is used as the manager for the cloud microservices. To enable auto scaling we deploy a service that runs in the swarm manager that automatically scales the amount of services run by the workers based on the response times of the services. The estimated number of required replicas is calculated and then the swarm is scaled appropriately. The data collected by the auto scaler is then displayed in real time to a webpage in order to show the effect of the auto scaling service.

### Architectural Diagram
<img src="{{ site.baseurl }}/assets/images/autoscaler/architecturalView-1.png" width="100%">
<hr style="margin-top: 20px;">

### State Diagram
<img src="{{ site.baseurl }}/assets/images/autoscaler/stateDiagram-1.png" width="100%">

