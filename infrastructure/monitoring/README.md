# Kube-Prometheus-Stack

Diese Datei dokumentiert die Helm-Values des Monitoring-Stacks.

## Komponenten

- Prometheus
- Grafana
- Alertmanager
- Node Exporter
- kube-state-metrics

## Storage

- Grafana: 2 GiB Longhorn
- Alertmanager: 2 GiB Longhorn
- Prometheus: 3 GiB Longhorn
- Prometheus-Retention: 1 Tag

## Sicherheit

Echte Passwörter und Kubernetes-Secrets werden nicht in Git gespeichert.
