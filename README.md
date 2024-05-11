<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar repositorio
2. Ejecutar comando:

```bash
yarn install
```

3. Tener Nest Cli instalado

```bash
npm i -g @nestjs/cli
```

4. Levantar la BBDD

```bash
docker-compose up -d
```

5. Copiar el archivo ```.env.template``` y renombrar la copia a ```.env```

6. Completar las variables de entorno con los valores correctos

7. Ejecutar la aplicación

```
yarn start:dev
```

8. Reconstruir BBDD con los datos semilla

```bash
http://localhost:3000/api/v2/seed
```

# Stack Usuado

* MongoDB
* Nest
