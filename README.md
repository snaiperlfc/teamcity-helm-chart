# TeamCity Helm Chart

Этот Helm-чарт разворачивает TeamCity Server и Agent в Kubernetes с:

- Поддержкой PostgreSQL
- Agent auto-registration
- Собственным PersistentVolume

## Установка

```bash
kubectl apply -f pv-teamcity.yaml
helm install teamcity ./teamcity-helm-chart
```

## Настройки

Все параметры доступны в `values.yaml`.
