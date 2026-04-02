# db-mariadb

MariaDB 11 Docker container pre-configured. Modern MySQL fork, ready to use.

## Quick Start

```bash
git clone https://github.com/Brazwed/db-mariadb.git
cd db-mariadb
docker compose up -d
```

## Default Connection

```
Host:     localhost
Port:     3307
User:     mariadb_user
Pass:     mariadb_dev_2026
Database: devdb

mysql -h localhost -P 3307 -u mariadb_user -pmariadb_dev_2026 devdb
```

## Configuration

Edit `.env` (created automatically from `.env.example`):

```env
MA_USER=mariadb_user
MA_PASS=mariadb_dev_2026
MA_DB=devdb
MA_PORT=3307
```

## Part of Database Toolkit

This repo can be used standalone or with other databases via [Database Toolkit](https://github.com/Brazwed/Database).
