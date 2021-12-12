# Kube Continous Monitor with Falco

## TLDR

* Setting up kubectl, doctl, and helm
* Create DigitalOcean Managed Kubernetes cluster
* Connect kubectl with the created cluster
* Install/deploy Falco using helm to the created cluster
* Create a nginx deployment
* Monitor Falco logs and try to enter the pod sh and do something malicious.

## Blog

You can see my blog [here](https://dev.to/berviantoleo/monitor-digitalocean-managed-kubernetes-cluster-with-falco-2cbn)

## Resource

* Nginx [deployment.yml](resources/nginx/deployment.yml)

## LICENSE

* Code - ![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)
* Article/Content - [![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/