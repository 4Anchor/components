# Манифесты и компоненты применяемые в процессе выполнения спринтов.
### Описание
#### Компоненты БД
values.yaml - требуется для деплоя helm chart PostgreSQL DB  

storageclass.yaml - требуется для успешного старта пода helm chart PostgreSQL DB  

pv.yaml - требуется для успешного старта пода helm chart PostgreSQL DB

#### Компоненты логирования
promtail.yaml - Kubernetes манифест для деплоя агента логирования promtail  

promtail-cluster-role.yaml - манифест кластр роли promtail  

promtail-cluster-rolebinding.yaml - манифест дляпривязки кластр роли promtail  

