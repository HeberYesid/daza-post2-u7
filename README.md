# daza-post2-u7

API REST CRUD de productos con Spring Boot, @RestController y ResponseEntity.

## Endpoints

- GET /api/productos
- GET /api/productos/{id}
- POST /api/productos
- PUT /api/productos/{id}
- DELETE /api/productos/{id}

## CÃƒÂ³digos HTTP

- 200 OK en consultas y actualizaciÃƒÂ³n exitosa
- 201 Created al crear
- 204 No Content al eliminar
- 404 Not Found cuando el recurso no existe

## Prerrequisitos

- JDK 17+
- Maven 3.8+

## EjecuciÃƒÂ³n

1. mvn spring-boot:run
2. Probar en <http://localhost:8080/api/productos>

## Ejemplo de payload

{
  "nombre": "Tablet",
  "descripcion": "Tablet 10 pulgadas",
  "precio": 1200.0
}

## Capturas

Guardar respuestas de Postman/curl en capturas/.

