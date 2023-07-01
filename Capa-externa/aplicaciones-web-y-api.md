Esto aplica a cualquier tipo de interfaz, sea móvil, desktop o cualquier otra

**Ejemplo de estructura:**
- Domain
- External
    - rest
    - console
    - persistence

#### Cosas que hay que evitar en la capa externa
- Colocar lógica de negocios en la vista
- Poner lógica de negocio en los controladores
    - **Contrladores:** recibir datos de la vista y elegir que parte del dominio invocar