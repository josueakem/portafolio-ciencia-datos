## Del problema a la tarea

- **Petición del jefe**: "Necesitamos mejorar el rendimiento de nuestras electrolineras y aprovechar mejor la infraestructura que tenemos actualmente."
- *Traducido a pregunta*: ¿En qué electrolineras y en qué horarios se registra la menor utilización de los cargadores?
- *Decisión que apoyaría*: Identificar en qué electrolineras implementar promociones o incentivos para aumentar la utilización de los cargadores con menor demanda.
- *Datos que necesitaría*: Básicamente, información sobre las transacciones de cada electrolinera, las cargas, fecha y hora de transacción, cargador y el tipo de conector. La información está contenida en una base de información sobre las cargas (datos sobre los cargadores y conectores) y otra sobre las transacciones (relativo al dinero que genera cada transacción), por lo que hay que fusionar las dos tablas para obtener la base completa. Ambas relacionadas por un ID de transacción.
- *Tipo de tarea*: Detección de anomalías, porque permite identificar electrolineras y horarios con comportamientos inusuales con una cantidad de cargas menor a la habitual.