Connection String
```
kubectl create secret generic grafana-database-secret --from-literal=connectionString='postgres://postgres:grafana@postgres@10.33.208.3:5432/postgres' -n monitoring
```
