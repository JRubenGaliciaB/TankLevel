Control Automático de Nivel para Tanque Industrial

🛠️ Aplicación Física e InstrumentaciónLa lógica del PLC está diseñada para interactuar directamente con componentes reales de planta

Sensor analógico (Level): Transmisor de nivel ultrasónico o de presión hidrostática (escalado de 0.0% a 100.0%).
Actuadores (FillCmd / DrainCmd): Salidas digitales hacia los contactores de la bomba de alimentación y la bomba de descarga (o electroválvulas).
Interfaz de Operador (FillButton / DrainButton): Pulsadores físicos momentáneos (Normalmente Abiertos) en tablero de control.

🔒 Cerraduras de Seguridad ImplementadasAnti-Desbordamiento (Overflow): Un bloque de comparación LT (Less Than) monitorea el nivel y corta automáticamente la retención de la bomba de llenado al alcanzar el 100.0%.Protección contra Trabajo en Seco (Run-Dry): Un bloque GT (Greater Than) detiene la bomba de descarga inmediatamente al llegar al 0.0%, previniendo cavitación y daños mecánicos.Alertas Tempranas: Comparadores dinámicos que activan alarmas críticas en HMI para Alto Nivel (80%) y Bajo Nivel (20%).
