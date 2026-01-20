## App microservicios productos

Este es el repo de la app de productos, para poder ejecutar por favor haga los siguientes pasos:

## Products microservice

# Dev

1. Clonar el repositorio `products-ms` en https://github.com/Prueba-Productos-microservicios/products-ms
2. Instalar dependencias
```
npm i
```
4. Crear un archivo `.env` basado en el `.env.template`
5. Levantar la base de datos con
```
docker compose up -d
```
6. Ejecutar migracion de prisma
```
npx prisma migrate dev
```
7. Levantar el proyecto con
```
npm run start:dev
```

## Client gateway

# Dev
1. Clonar el repositorio `client-gateway` en https://github.com/Prueba-Productos-microservicios/client-gateway
2. Instalar dependencias
```
npm i
```
3. Crear un archivo `.env` basado en el `.env.template`
4. Tener levantados los microservicios que se van a consumir
5. Levantar el proyecto con
```
npm run start:dev
```

## Products web ui
1. Clonar el repositorio `products-web-ui` en https://github.com/Prueba-Productos-microservicios/products-web-ui.git
2. Instalar dependencias
```
npm i
```
3. Levantar el proyecto con
```
ng serve
```
