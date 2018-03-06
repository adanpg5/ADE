# Bases de datos distribuidas y replicadas en SQL Server

## Definición

* Una base de datos distribuida es un conjunto de múltiples bases de datos lógicamente relacionadas
las cuales se encuentran distribuidas en diferentes espacios lógicos y geográficos
(pej. un servidor corriendo 2 máquinas virtuales) e interconectados por una red de comunicaciones.
Dichas BDD tienen la capacidad de realizar procesamientos autónomos, estos permiten realizar operaciones locales o distribuidas.

* Un Sistema de Bases de Datos Distribuida (SBDD), es un sistema en el cual múltiples sitios de bases de datos están ligados entre si por un sistema de comunicaciones de tal forma que, un usuario en cualquier sitio puede acceder los datos en cualquier parte de la red exactamente como si estos fueran accedidos de forma local.

* La replicación es el proceso de copiar y mantener actualizados los datos en varios nodos de bases de datos ya sean estos persistentes o no. En informática, la persistencia se refiere a la propiedad de los datos para que estos sobrevivan de alguna manera.

---

## Ventajas e inconvenientes

* **Ventajas**:

* *ORGANIZATIVAS*:
  * Adaptación a la organización de la institución (unión de compañías/descentralización), respondiendo a cambios
  * Almacenar los datos donde son generados y/o usados, la mayor parte locales
  * Proporcionar autonomía local, controlándose desde cada nodo. Política general contra política local

* *ECONÓMICAS*:
  * Costos de comunicación y de creación de pequeños sistemas

* *TÉCNICAS*:
  * Flexibilidad, acceso desde distintos lugares y por distintas personas a la vez
  * Fiabilidad/disponibilidad, en un determinado momento / intervalo. Varios sitios, duplicaciones, evitan fallos
  * Mejora del rendimiento, BD más pequeñas, operaciones de menor volumen

* **Desventajas**:
  * Complejidad del sistema, desarrollo de software más costoso, problemas de sincronización, dificultad para conocer la corrección de los algoritmos paralelos, detección de caídas de nodos
  * Dependencia de la red de comunicaciones, sobrecarga de procesamiento de mensajes
  * Dificultad de diseño, fases adicionales
