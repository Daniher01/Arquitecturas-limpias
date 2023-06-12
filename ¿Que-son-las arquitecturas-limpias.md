#### Formas de estructurar una aplicación
- Forma 1:
    - Presentación
    - Dominio
    - Accesso a datos
        - Bases de datos
- Forma 2:
Patro MVC
    - Vista
    - Controlador
    - Modelo

#### Limitaciones
- Desarrollo centrado en la base de datos  
- Lógica de negocio depende de la persistencia
- Si hay otras integraciones, no es claro donde van
- La lógica de negocio a veces se filtra (hay que aplicarla en la presentacion, ejemplo, en el click de un boton)

> Ante estas dificultados surgen las arquitecturas limpias

### Caracteiristicas comunes de arquitecturas limpias
- Dominio como elemento central
- **El dominio no depende de elementos externos**
- Las dependencias se inviernten
- Facilitan las pruebas

### ¿Cuando aplicar estas arquitecturas?
- Sistemas sostenibles en el tiempo
- Sistemas donde la testeabilidad es importante. ejemplo: aplicaciones que tienen que ver con dinero y salud
- Sistemas con multiples integraciones (aislar el dominio de las integraciones
- Flexibilidad para cambiar una implementacion)

### ¿Cuando NO aplicar estas arquitecturas?
- Sistemas sencillos (como un CRUD)
- Sistemas con un tiempo de vida muy corto(como pruebas de conecptos o MVP)
- Pocas integraciones (solo la bd)

## Consideraciones
- Tomarlas como punto de partida y adaptarla a cada caso
- El numero de capas depende de ti
    - Una, dos o más capa de dominio
    - Una o más capas externas
- La regla de la dependencia debe respetarse si o si
- El nombre de las arquitecturas y capas suelen usarse de forma arbitraria    

> "La arquitectura es acerca de las coasas importantes. Sean las que sean."    