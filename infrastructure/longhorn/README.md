# Longhorn

Longhorn stellt persistenten Speicher für den K3s-Cluster bereit.

## Voraussetzungen

- open-iscsi auf allen Kubernetes-Nodes
- iscsid aktiv
- nfs-client für RWX-Volumes
- flannel-iface auf enp0s8

## Hinweise

Die Root-Dateisysteme sind knapp bemessen. Das Prometheus-Volume
wurde deshalb von 10 GiB auf 3 GiB reduziert.
