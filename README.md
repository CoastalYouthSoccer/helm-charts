# Coastal Youth Soccer Helm Chart Repo

## Introduction
This repo holds the Helm Chart for the Coastal Youth Soccer organization.

## Prerequisites

- Kubernetes 1.22+
- Helm 3.x.+

## Installing via Helm Repo

1. Add Repo

```console
helm repo add coastalyouthsoccer https://coastalyouthsoccer.github.io/helm-charts/
helm repo update
```

2. Install the chart via Chart Repo

```console
helm install <release name>
```

## Uninstalling via Helm Repo

```console
helm delete <release name>
```

## Configuration

The table below lists available parameters and their default values.

| Parameter | Description | Default |
| --------- | ----------- | ------- |
