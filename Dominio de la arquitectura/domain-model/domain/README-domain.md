# Dominio

Es la razon de ser el sistema.

#### Otros nombres del domino
- Lógia de negocio
- Lógica de dominio
- Negocio

> "El dominio involucra lo que debe hacer el neogico, haya o no sistemas de información."

**Ejemplo de que hace el dominio:**
En el contexto de un supermercado
- Calcular descuentos
- Verificar 

**¿Que no corresponde al dominio?**
- Si los empleados utilizan aplicación web o una consola.
- Si los empleados tienen lectores de códigos de barra o no

**Situaciones a evitar con el dominio**
- Referenciar una capa externa en el dominio
- Mencionar elementos de la capa externa
- Retornar datos con un formato especifico (*retornar en html como ejemplo*)
- Permitir que la logica de negocio de filtre (*a otras capas*)

**Formas de organizar las capas de dominio**
- Script de transacción
- Modelo de dominio
- Capas de servicios
- Casos de uso (*no aplica en esta estructura*)

El dominio tiene muchas maneras de organizarse, algunas opciones pueden ser
- Dividir la aplicación (servicios o script de transacción y el modelo (patrones de diseño))