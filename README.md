# Proyecto final de Estucturas de datos
## Integrantes

- Lechuga Canales Héctor Jair
- Luz Martínez Bryan
- Pérez de la Torre Ian Axel

## Tema
Agenda de contactos

**Funciones de la agenda:** 
1. Insertar nombre, insertar número, insertar correo electronico: El usuario podra ingresar y guardar los datos mensionados.
2. Mostrar todos los contactos en forma de lista: Se desplegara una liosta con todos los contactos.
3. Buscar contactos: El usuario podra buscar contactos especifocos.

**Estructuras a utilizar.**
- Listas: Descartamos esta estructura ya que al realizar una búsqueda para consultar información o realizar una modificación, en el peor de los casos tendría que recorrer los "n" datos que estén insertados en la agenda.

- Pilas: Descartamos esta estructura por la complejidad que se tiene para acceder a los datos y que se requieren más pasos para hacer una modificación de algún dato en la agenda. Colas: Descartamos esta estructura ya que cuando queremos realizar alguna acción en la agenda la complejidad es de grado “n”.

- Arboles: También descartamos esta estructura, aunque esta es más rápida que las anteriores para realizar búsquedas o modificaciones en los datos de la agenda no es la más eficiente.

- **Tablas hash:** Finalmente elegimos esta estructura ya que las búsquedas o modificaciones a los datos de la agenda son de complejidad constante es decir no importa cuantos datos tengas ingresados en la agenda siempre se va tardar lo mismo para encontrar un dato, esto se debe a que esta estructura trabaja asignando claves a los datos que se van insertando.
