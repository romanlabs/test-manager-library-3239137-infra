# Manager Library - Infrastructure

Configuracion de contenedores Docker para Manager Library.

## Servicios

- **postgres**: Base de datos PostgreSQL 16
- **api**: Servidor PHP 8.2 para el backend

## Inicio

```bash
docker-compose up
```

Acceso:
- API: http://localhost:8000
- Database: localhost:5432

## Variables de entorno

- DB_HOST: postgres
- DB_PORT: 5432
- DB_NAME: library
- DB_USER: library
- DB_PASSWORD: library
