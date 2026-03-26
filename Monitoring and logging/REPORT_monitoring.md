# Отчёт: Логирование и мониторинг
- Логин: red01
---

## Prometheus

### 1. Содержимое рабочей папки

![Содержимое папки prometheus01](screenshots/ls_la.jpg)

### 2. Содержимое файла prometheus.yml

![Файл prometheus.yml](screenshots/prometheus_file.jpg)

### 3. Содержимое файла alerts.yml

![Файл alerts.yml](screenshots/alerts_file.jpg)

### 4. Статус node_exporter

![node_exporter status](screenshots/node_exporter.jpg)

### 5. Запуск контейнера Prometheus


![Запуск Prometheus (docker ps)](screenshots/docker_prometheus.jpg)


![Запуск Prometheus](screenshots/docker_prometheus2.jpg)

Использовала для себя порт 8101, так как порт 3001 был уже занят
![Prometheus app](screenshots/app_prometheus.jpg)

### 7. Веб-интерфейс Prometheus

![Prometheus UI](screenshots/launched_prometheus.jpg)

---

## Grafana

### 9. Содержимое папки grafana

![Содержимое папки grafana](screenshots/ls_la_grafana.jpg)

### 10. Содержимое файла docker-compose.yml
Использовала для себя порт 3101, так как порт 3001 был уже занят

![docker-compose.yml](screenshots/docker-compose_file.jpg)

### 11. Содержимое файла loki-config.yaml

![loki-config.yaml](screenshots/loki_config_file.jpg)

### 12. Содержимое файла promtail-config.yaml

![promtail-config.yaml](screenshots/promtail_config_file.jpg)

### 13. Запуск контейнера Grafana

![Запуск Grafana (docker ps)](screenshots/docker_grafana.jpg)

### 14. Веб-интерфейс Grafana

![Grafana UI](screenshots/launched_grafana.jpg)
