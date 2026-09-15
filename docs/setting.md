# Setting

1. Укажите IP-адрес роутера в `prometheus/etc/targets/openwrt.yml`:

```yaml
- targets:
    - '192.168.1.1:9100'
```

2. Укажите учётные данные и retention в `.env`:

```bash
cp .env.example .env
```

Измените `GF_SECURITY_ADMIN_PASSWORD` на уникальный пароль.

3. Запустите мониторинг:

```bash
docker compose up -d
```

Сервисы по умолчанию доступны только на этой машине:

- Grafana — [localhost:3000](http://localhost:3000),
- Prometheus — [localhost:9090](http://localhost:9090).
