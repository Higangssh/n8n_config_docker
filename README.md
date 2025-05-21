# n8n Docker Setup

This repository contains configuration files to easily set up and run n8n using Docker.

## Prerequisites

- Docker
- Docker Compose

## Installation and Running

1. Clone the repository:

```bash
git clone https://github.com/Higangssh/n8n_config_docker.git
cd n8n_config_docker
```

2. Run n8n using Docker Compose:

```bash
docker-compose up -d
```

## Default Configuration

- Port: 5678
- Basic Authentication:
  - Username: test
  - Password: 12341234
- Timezone: Asia/Seoul

## Access

You can access n8n through your web browser at:

```
http://localhost:5678
```

## Data Storage

- n8n data is stored in the `./n8n_data` directory
- Local files are stored in the `./local-files` directory

## Important Notes

- `.env` file and `n8n_data` directory are included in `.gitignore` and are not tracked by Git
- Make sure to change the default authentication password in production environments
