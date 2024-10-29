# pt_int_monitoring

# Мониторинг доступности ptsecurity.com с помощью Prometheus и Blackbox Exporter

Этот проект настраивает мониторинг доступности сайта `https://ptsecurity.com` с использованием [Prometheus](https://prometheus.io/) и [Blackbox Exporter](https://github.com/prometheus/blackbox_exporter). Он включает конфигурационные файлы для сбора метрик доступности.

## Начало работы

Эти инструкции помогут вам установить систему мониторинга на локальной машине с использованием Docker.

### Предварительные требования

- Docker
- Docker Compose

### Установка

1. **Клонируйте репозиторий:**

   ```bash
   git clone https://github.com/SL1MP/pt_int_monitoring
   cd pt_int_monitoring
   ```
2. **Запустите Docker Compose:**

Эта команда запустит как Prometheus, так и Blackbox Exporter в фоновом режиме.
  ```bash
  docker-compose up -d
  ```
