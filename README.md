<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

#Ejecutar en desarollo

1. Clonar el repositorio
2. Ejecutar
```
yarn install
```
3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```

5. Clonar el archivo ```.env.template``` y renombrar la copia a ```.env```

6. Llenar las variables de entorno definidas en el ```.env```

7. Ejecutar la aplicación en dev:
```
yarn start:dev
```

8. Reconstruir la base de datos con la semilla
```
http://localhost:3000/api/v2/seed
```

#Stack usado
* MongoDB
* Nest JS


#Deploy
* nest-js-pokedex-production.up.railway.app


railway for mongo database
nest-js-pokedex-production.up.railway.app