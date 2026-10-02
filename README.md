## Israel Cervantes Juárez

Desarrollador de software. Estudié Matemáticas Aplicadas en la BUAP y programo en Python,
sobre datos que alguien usa para trabajar todos los días.

Hoy desarrollo módulos de una aplicación interna de gestión en Python y PostgreSQL, sobre
una base de código existente y dentro de un equipo con revisión de código, migraciones
versionadas y ciclos de QA.

Antes diseñé y llevé a producción:

- **Un sistema de cobranza completo.** 11 módulos y 4 flujos de ejecución, con contratos de
  datos, barreras de validación que abortan el proceso antes de escribir algo mal, y
  trazabilidad de cada corrida. Procesaba dos carteras aisladas entre sí, más de 250,000
  cuentas, con frontera dura entre ambas. Siguió operando después de que salí de la empresa.
- **Un motor territorial de cobranza de campo.** Cartografía del INEGI, agrupamiento y ruteo
  con OSRM con respaldo controlado. Organiza cerca de 9,000 clientes en más de 600 tramos
  operativos, con entregables por gestor.
- **Automatización con Selenium** de la descarga y conciliación de reportes de pago.

Ese código es de las empresas donde trabajé, así que no está aquí. Por eso existe el primer
proyecto de esta lista.

### Proyectos

**[motor-cartera](https://github.com/israelcervantes31416/motor-cartera)**
Reimplementación pública, sobre datos sintéticos, de los patrones de ingeniería de un sistema
de cartera de crédito. Ingesta con contratos de datos versionados, validación *fail-closed*
con rechazo por registro y motivo, firma del contenido y trazabilidad por corrida, sobre
PostgreSQL con migraciones versionadas. Expuesto como API REST con FastAPI, con un motor de
decisión versionado y determinista, Docker e integración continua. Dos versiones publicadas.
Tiene una sección de limitaciones conocidas, escrita a propósito.

**[regresion-multivariada-censo2020](https://github.com/israelcervantes31416/regresion-multivariada-censo2020)**
Mi tesis de licenciatura. Regresión multivariada por formulación matricial sobre los 2,469
municipios de México, con datos del Censo de Población y Vivienda 2020 del INEGI. Incluye
contrastes multivariados, análisis de correlación canónica, diagnóstico de supuestos y las
limitaciones del modelo escritas explícitamente. Proceso reproducible con semilla fija.

**[Airbnb_Price_Prediction](https://github.com/israelcervantes31416/Airbnb_Price_Prediction)**
Proyecto independiente. Modelos supervisados para predecir precios de Airbnb en la Ciudad de
México sobre 26,536 registros, con comparación entre modelos. Presentado como cartel en la
XVII Semana Internacional de la Estadística y la Probabilidad, BUAP.

**[BTC_GeometricBrownianMotion](https://github.com/israelcervantes31416/BTC_GeometricBrownianMotion)**
Modelado del precio de Bitcoin con movimiento browniano geométrico, con deriva y
estacionalidad. En coautoría; presentado como ponencia en la misma edición del congreso.

### Herramientas

Python (pandas, NumPy, GeoPandas, scikit-learn, openpyxl, Selenium, pytest) · SQL y
PostgreSQL · R · FastAPI · Docker · Git, GitHub Actions y revisión de código · Alembic ·
Power BI (reportes) · LaTeX

### Cómo trabajo

Uso asistentes de IA como herramienta de ingeniería: para explorar alternativas, escribir
código y pruebas, y revisar cambios. Las decisiones de arquitectura, los criterios de
aceptación y la responsabilidad sobre cada cambio siguen siendo míos. Ningún cambio se da
por terminado solo porque lo haya generado un agente.

### Dónde más

- [LinkedIn](https://www.linkedin.com/in/israelcervantes31416)
- [Credenciales verificables en Credly](https://www.credly.com/users/israelcervantes31416)
