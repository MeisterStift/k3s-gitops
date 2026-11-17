# K3s-Lab-Architektur

## Control Plane

- k3s-s1
- k3s-s2
- k3s-s3
- Embedded etcd mit 2-von-3-Quorum

## Worker

- k3s-a1
- k3s-a2

## Loadbalancing

- HAProxy auf lb1 und lb2
- Keepalived-VIP 192.168.56.107
- Traefik als Kubernetes-Ingress-Controller

## Storage

- Longhorn
- Drei Replikate pro Volume, sofern genug Kapazität vorhanden ist

## Monitoring

- Kube-Prometheus-Stack
- Grafana
- Prometheus
- Alertmanager

## GitOps

- GitHub als Source of Truth
- Argo CD für Kubernetes-Ressourcen
