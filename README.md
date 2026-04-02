# db-mariadb

MariaDB 11 Docker container pré-configurado. Fork moderna do MySQL, pronta pra usar.

## Uso rápido

```bash
git clone https://github.com/Brazwed/db-mariadb.git
cd db-mariadb
docker compose up -d
```

## Conexão padrão

```
Host:     localhost
Porta:    3307
Usuário:  mariadb_user
Senha:    mariadb_dev_2026
Banco:    devdb

mysql -h localhost -P 3307 -u mariadb_user -pmariadb_dev_2026 devdb
```

## Configuração

Edite `.env` (criado automaticamente de `.env.example`):

```env
MA_USER=mariadb_user
MA_PASS=mariadb_dev_2026
MA_DB=devdb
MA_PORT=3307
```

## Parte do Database Toolkit

Este repositório pode ser usado standalone ou junto com outros bancos via [Database](https://github.com/Brazwed/Database).
