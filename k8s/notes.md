# Notes d'installation

## Loki & Promtail
```sh
helm repo add grafana https://grafana.github.io/helm-charts
helm install loki grafana/loki-stack
```

```sh
kubectl apply -f promtail.yaml
```

```sh
kubectl apply -f promtail-daemonset.yaml
```