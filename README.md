Construyo sistemas de datos que una operación usa todos los días, y los construyo para que
fallen antes de escribir algo mal.

### Lo que he construido

- **Un sistema de datos para una operación de cobranza**, diseñado y llevado a producción:
  11 módulos y 4 flujos de ejecución, con contratos de datos, barreras de validación
  *fail-closed* y trazabilidad de cada corrida. Procesaba dos carteras aisladas entre sí,
  con más de 250,000 cuentas, y bajó el ciclo de preparación de cartera y entregables de
  ~12 horas a ~10 minutos.
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

Elegí las cinco optativas de la carrera en estadística, y mi fuerte está en optimización y
modelación.

**[Mi tesis](https://github.com/israelcervantes31416/regresion-multivariada-censo2020)**
modela en conjunto cuatro indicadores de rezago social en los 2,469 municipios del país, con
los datos completos del Censo 2020: 126 millones de personas, no una muestra. Programé la
regresión multivariada desde el álgebra lineal —estimación, pruebas de Wilks y Pillai,
diagnóstico de residuos y análisis canónico—, porque ninguna biblioteca lo resolvía de forma
transparente. La primera dirección canónica concentra el 93.8% de la asociación, y la domina
el analfabetismo adulto. La tesis también dice dónde falla el modelo: qué supuestos no se
cumplen, qué pasa al excluir los municipios influyentes y por qué sus resultados describen
municipios, no personas.

Antes, en mi práctica profesional, condensé 276 variables del mismo censo en tres
componentes principales que explican el 91.13% de la varianza, y lo presenté como
infografía en el 58.º Congreso Nacional de Matemáticas.

Desde julio de 2026 desarrollo un proyecto cuantitativo propio sobre futuros de cripto, en
repositorios privados por ahora: investigación prerregistrada, validación fuera de muestra,
costos de ejecución incluidos y la regla de no arriesgar capital mientras la evidencia no lo
justifique.

Formación complementaria: Diplomado en Ciencia de Datos (BUAP, 120 h), Técnico en Big Data
(Fundación Carlos Slim, 542 h) y certificados de Google Cloud, Google e IBM.

### Cómo trabajo

- Parto una especificación grande en incrementos que se pueden verificar, y antes de cada uno
  compruebo el estado real de la base.
- Dejo por escrito qué está verificado y qué no.
- Uso asistentes de IA para escribir código y pruebas; las decisiones de diseño, los criterios
  de aceptación y la responsabilidad sobre cada cambio son míos.
