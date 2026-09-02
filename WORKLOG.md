## 2026-08-26: Перенос Kubernetes-манифестов в отдельный репозиторий

- Создан отдельный репозиторий k8s-basics.
- Перенесены манифесты Deployment, Service, ConfigMap, Secret.
- Настроен Git и GitHub.

## 2026-09-02: StatefulSet и PersistentVolume

- Созданы манифесты PV, PVC, StatefulSet для Nginx.
- Изучено, как PV и PVC связываются по размеру и режиму доступа.
- StatefulSet автоматически создаёт PVC для каждого пода.
- Под не запустился из-за отсутствия PV для автоматического PVC (Pending).
- Сеть кластера всё ещё не работает (CNI Calico), но объекты создаются.
