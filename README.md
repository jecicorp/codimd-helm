# CodiMD Helm chart

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/codimd)](https://artifacthub.io/packages/search?repo=codimd)

This repository contains helm chart for CodiMD.

## Requirements

- Kubernetes: >= 1.14
- Helm 2 / 3

## Install

```bash
helm repo add jeci https://nexus.jeci.tech/repository/jeci-charts/
helm install my-release jeci/codimd
```

## Documentation
[charts/codimd/README.md](./charts/codimd/README.md)

## Build

```shell
./build.sh
helm cm-push charts/codimd jeci -u xxx -p xxx --context-path=/repository/jeci-charts/
```
