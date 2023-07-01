![arquitectura hexagonal](https://miro.medium.com/v2/resize:fit:1400/1*yR4C1B-YfMh5zqpbHzTyag.png)

- **Aplicación - Dominio**
Estará toda la lógica de negocio, servicios, entidades
- **Puerto**
Tendrá lo relacionado a la api de clientes, api de la BD
-**Adaptadores**
Se van a encargar de convertir algo externo a nuestra aplicación, como la *interfaz gráfica*, *api rest*, *adatador a Mysql*

>Las capas externas tiene conocimientos de lo que hay hacia adentro, pero la aplicacion nunca deberia tener conocimiento de que hay en la capa de puerto o de adaptadores

#### Otros conceptos

**Actores Primarios**
Son esos adaptadores capaces de iniciar interacciones con el sistema, ejemplo *API REST*

**Actores secundarios**
Son esos adaptadores que son notificados de algo que pasa en la aplicación, ejemplo *Adaptador de de la BD*