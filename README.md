# kubelet-exporter

[![Build Status](https://travis-ci.org/cofyc/kubelet-exporter.svg?branch=master)](https://travis-ci.org/cofyc/kubelet-exporter)
[![Docker Repository on Quay](https://quay.io/repository/cofyc/kubelet-exporter/status "Docker Repository on Quay")](https://quay.io/repository/cofyc/kubelet-exporter)

A exporter which translates information of kubelet summary API into prometheus
metrics. See [docs/metrics.md](docs/metrics.md).

## How to deploy it

```
kubelet apply -f deployment/daemonset.yaml
```
