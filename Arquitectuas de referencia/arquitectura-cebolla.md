![Arquitectura de debolla](https://miro.medium.com/v2/resize:fit:400/1*uzpwtt85w4RCo1jA0Ok4Eg.png)

- **Modelo de dominio**
    - Estarán las entidades de la aplicación
    - Esas entidades no deberian estar amarradas con la persistencia
    - Este solo puede depender de si mismo
*Ejemplo*: Si vamos a hace una aplicacion para hoteles, aqui van a estar entidades como "hotel", "reserva"
- **Servicios de Dominio**
    -  Tendrá la lógica y reglas de negocio
    - Tendrá los "repositorios" (que son las que se conectan a la bd), y las interfaces
- **Servicios de aplicación**
    - Aunque tambien puede estar repartida entre los servicios de dominio y los modelos de dominio
    - Conocida también como la capa de servicios
    - También puede tener interfaces

  - **Capa externa**
    - Todo lo que rodea a nuestro sistema
    - Contiene las pruebas
    - Infraestructura
    - Interfas gráfica

 Es una arquitectura muy conocida en el ecosistema c# y .NET pero se puede implementar en cualquier lenguaje   