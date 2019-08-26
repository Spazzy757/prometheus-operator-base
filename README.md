# Prometheus Operator Kustomize base

## Usage
```bash
kubectl apply -k prometheus-operator-base
```

You can then get the grafana pod using:

```bash
kubectl get pods -n monitoring
```


Port forward grafana:

```bash
kubectl port-forward <grafana-podf-id> 3000:3000 -n monitoring
```
