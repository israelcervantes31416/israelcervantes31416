Construyo sistemas de datos que una operación usa todos los días, y los construyo para que
fallen antes de escribir algo mal.

### Lo que he construido

- **Un sistema de datos para una operación de cobranza**, diseñado y llevado a producción:
  11 módulos y 4 flujos de ejecución, con contratos de datos, barreras de validación
  *fail-closed* y trazabilidad de cada corrida. Procesaba dos carteras aisladas entre sí,
  con más de 250,000 cuentas, y bajó el ciclo de preparación de cartera y entregables de
  ~12 horas a ~10 minutos. Siguió operando después de mi salida.
- **Un motor territorial de cobranza de campo**: cartografía del INEGI, zonificación por
  clustering y ruteo con OSRM con respaldo controlado, para cerca de 9,000 clientes en más
  de 600 tramos.
- **Reportería convertida en procesos**: alrededor de diez reportes recurrentes que se hacían
  a mano en Excel y Google Sheets, sustituidos por procesos ejecutables y reproducibles.
- **Hoy**, módulos de una aplicación interna en Python (Reflex) y PostgreSQL sobre una base
  de código existente, desde el modelo de datos hasta la interfaz, con revisión de código en
  ambos sentidos y ciclos de QA.

[motor-cartera](https://github.com/israelcervantes31416/motor-cartera) es un proyecto propio,
escrito desde cero sobre datos sintéticos y sin código ni datos de ninguna empresa: ahí
perfecciono y llevo más lejos lo que aprendí construyendo esos sistemas.

### Del lado matemático

Estadística multivariada, optimización y modelación. Mi tesis implementa regresión
multivariada desde la formulación matricial sobre los 2,469 municipios del Censo 2020, con
los supuestos que no se cumplen escritos y un proceso reproducible.

### Cómo trabajo

- Parto una especificación grande en incrementos que se pueden verificar, y antes de cada uno
  compruebo el estado real de la base.
- Dejo por escrito qué está verificado y qué no.
- Uso asistentes de IA para escribir código y pruebas; las decisiones de diseño, los criterios
  de aceptación y la responsabilidad sobre cada cambio son míos.
