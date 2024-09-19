1. Clonar repositorio
2. Instala dependencias
3. Crear archivo `.env` basado en el `env.template`
4. Levantar la BBDD con `docker compose up -d`
5. Levantar servidor de NATS
```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats

```
6. Levantar el proyecto con `npm run start:dev`