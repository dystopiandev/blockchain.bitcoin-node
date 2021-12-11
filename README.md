# Bitcoin Node

- [Bitcoin Node](#bitcoin-node)
  - [bitcoin-core](#bitcoin-core)
    - [Configure](#configure)
    - [Build](#build)
    - [Start](#start)
    - [Stop](#stop)
    - [View logs](#view-logs)

## bitcoin-core
### Configure
Alter data directory, ports, extra arguments and other options in `.env`. Sample is provided as `.env.example`.

### Build
```bash
docker-compose build bitcoin-core
```

### Start
```bash
docker-compose up -d bitcoin-core
```

### Stop
```bash
docker-compose stop bitcoin-core # stop
docker-compose kill bitcoin-core # kill
docker-compose rm bitcoin-core # remove container
```

### View logs
```bash
docker-compose logs bitcoin-core
```