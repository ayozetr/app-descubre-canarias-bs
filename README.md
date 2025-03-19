# Descubre Canarias App

## Descripción

Aplicación con Bootstrap que muestra información de los sitios más atractivos para visitar en Canarias.

## Ejecución con Docker

### Construcción de la imagen

```bash
docker build -t app-descubre-canarias-bs .
```

### Ejecución del contenedor

```bash
docker run -d -p 8080:80 --name app-descubre-canarias-bs app-descubre-canarias-bs
```

```bash
curl http://localhost:8080
```
