<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```bash
pnpm install
```

3. Tener Nest CLI instaldo

```bash
npm i -g @nestjs/cli
```

4. Levantar la Base de Datos

```bash
docker-compose up -d
```

5. Clonar el archivo `.env.template` y renombrar la copia a `.env`

6. Llenar las variables de entorno definidas en el `.env`

7. Ejecutar la aplicacion en dev:

```bash
pnpm run start:dev
```

8. Reconstruir la Base de Datos con la semilla

```bash
http://localhost:3000/api/v2/seed
```

## Stack usado

- MongoDB
- Nest