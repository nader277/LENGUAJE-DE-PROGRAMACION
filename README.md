# Andes Fresh - Portal (Spring Boot + Thymeleaf + JPA)

Requisitos: Java 17 o superior y Maven.

## Ejecutar
    mvn spring-boot:run

Abrir http://localhost:8080/productos

## Rutas
- /productos (catálogo paginado)
- /productos/nuevo (registro único)
- /productos/lote (carga por lote)
- /pedidos/nuevo (maestro-detalle)

La base H2 es en memoria: al reiniciar vuelven los 7 productos iniciales.
