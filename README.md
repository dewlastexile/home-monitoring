# 🐳 Docker Monitoring Stack — cAdvisor + Prometheus + Grafana
Проект для мониторинга Docker-контейнеров в домашней или тестовой среде. Позволяет отслеживать загрузку CPU, RAM, дисков, сети и состояние каждого контейнера.
---
## 🚀 Компоненты проекта
| Компонент | Назначение |
|----------|------------|
|**cAdvisor**| Сбор метрик Docker-контейнеров |
|**Prometheus**| Хранение и сбор метрик |
|**Grafana**| Визуализация метрик |
|**Node-exporter**| Сбор метрик хостовой ВМ |
|**Alertmanager**| Отправка алертов в Telegram bot |
---
## 📦 Запуск
```bash
docker compose up -d
```
---
После запуска:
| Сервис | URL |
|----------|------------|
|**Prometheus**| http://localhost:9090|
|**Grafana**| http://localhost:3000|
|**cAdvisor**| http://localhost:8080|
|**Alertmanager**| http://localhost:9093|
---
## 🧰 Используемые порты
| Сервис | Порт |
|----------|------------|
|**Prometheus**| 9090|
|**Grafana**| 3000|
|**cAdvisor**| 8080|
|**Alertmanager**| 9093|
---
## 📜 Лицензия
Свободно используйте и модифицируйте проект.
