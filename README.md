# Practica-Docker - Aplicación de Notas
primer trabajo de desplige en docker para nube

Aplicación contenerizada con Docker que permite guardar y consultar notas usando FastAPI y PostgreSQL.

## Funcionalidades
- Guardar notas en archivo y base de datos
- Consultar notas desde archivo (`/`)
- Contar notas (`/conteo`)
- Mostrar autor desde variables de entorno (`/autor`)
- Consultar notas desde PostgreSQL (`/notas-db`)

## Ejecución
docker-compose up --build
