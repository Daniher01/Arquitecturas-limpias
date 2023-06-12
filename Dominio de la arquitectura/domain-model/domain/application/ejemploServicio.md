Aqui va la implenetacion del script de transacción, el servicio no necesita saber donde se guardan los datos
ni de donde vienen, esto se puede hacer aplicando inyecccion de dependencias

**Ejemplo de script de transacción**
- Generar una boleta: todo los pasos para la generación de una boleta

**Cuando es recomentable usar el script de transacción**
- Aplicaciones con poca lógica de negocio
- Problemas simples

**Problemas del script de transacción**
- Se vuelve dificil de mantener cuando la lógica crece
- No aprovecha el POO

**Formas de hace inyección de dependencias**
- Por constructor (*mejor opción*)
- Por setter
- Por método
- Por interfaz

> El servicio actua como fachada abstrayendo en modelo de dominio a las capas externas, aqui va la lógica de negocio y/o los script de transacción