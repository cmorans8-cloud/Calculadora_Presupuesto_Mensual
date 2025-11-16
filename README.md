# 📊 Calculadora de Presupuesto Mensual

## 📌 Descripción del Caso
La **Calculadora de Presupuesto Mensual** es una aplicación web/móvil diseñada para ayudar a los usuarios a gestionar sus ingresos y gastos personales.  
El sistema permite registrar fuentes de ingreso, clasificar gastos, calcular automáticamente el saldo mensual y generar reportes gráficos.  
En versiones posteriores se añadieron funcionalidades avanzadas como metas de ahorro, importación de datos desde archivos CSV/Excel, categorización automática de gastos y simulaciones de gastos futuros.

---

## 🎯 Objetivos
- Ofrecer una herramienta sencilla e intuitiva para el **control financiero personal**.  
- Permitir al usuario **registrar ingresos y gastos** de manera organizada.  
- Generar **reportes gráficos y alertas automáticas** cuando los gastos superen los ingresos.  
- Incorporar funciones avanzadas como **metas de ahorro, notificaciones y simulaciones de gastos futuros**.  
- Asegurar que el sistema sea **portable, escalable y mantenible** en diferentes plataformas (iOS, Android, Web).

---

## 📑 Requerimientos

### Funcionales (RF)
- **RF1:** Registrar diferentes fuentes de ingreso.  
- **RF2:** Registrar y clasificar gastos por categoría.  
- **RF3:** Calcular automáticamente el saldo mensual.  
- **RF4:** Mostrar reportes gráficos del presupuesto.  
- **RF5:** Generar alertas si los gastos superan los ingresos.  
- **RF6 (v2):** Establecer metas de ahorro mensual.  
- **RF7 (v2):** Importar ingresos y gastos desde CSV/Excel.  
- **RF8 (v2):** Clasificación automática de gastos.  
- **RF9 (v2):** Notificaciones programadas sobre gastos.  
- **RF10 (v2):** Simulador de gastos futuros.  

### No Funcionales (RNF)
- **RNF1:** Interfaz clara y fácil de usar.  
- **RNF2:** Respuesta a cálculos en menos de 2 segundos.  
- **RNF3:** Seguridad mediante cifrado de datos.  
- **RNF4 (v2):** Portabilidad en iOS, Android y navegadores web.  
- **RNF5 (v2):** Escalabilidad para manejar hasta 10.000 registros mensuales.  
- **RNF6 (v2):** Mantenibilidad mediante arquitectura modular.  

---

## 🧪 Tabla de Pruebas y Validación

| Tipo de Prueba       | Requerimiento | Datos de Entrada                  | Resultado Esperado                          | Resultado Obtenido |
|----------------------|---------------|-----------------------------------|---------------------------------------------|--------------------|
| Prueba Unitaria 1    | RF1           | Ingreso: Sueldo = 800             | Se registra correctamente                   | Correcto           |
| Prueba Unitaria 2    | RF2           | Gasto: Alimentación = 200         | Se registra y clasifica correctamente       | Correcto           |
| Prueba Unitaria 3    | RF3           | Ingreso: 800, Gasto: 200          | Saldo = 600                                 | Correcto           |
| Validación 1         | RF4           | Ingresos y gastos cargados        | Se muestra gráfico de barras                | Correcto           |
| Validación 2         | RF5           | Ingreso: 500, Gasto: 600          | Alerta: "Gastos superan ingresos"           | Correcto           |
| Prueba Unitaria 4    | RF6 (v2)      | Meta ahorro: 300; Ingreso: 800; Gasto: 400 | Mensaje: "Faltan 100 para llegar a la meta" | Correcto           |
| Prueba Unitaria 5    | RF7 (v2)      | Archivo CSV con 3 ingresos y 5 gastos | Importa y registra los 8 datos sin errores | Correcto           |
| Prueba Unitaria 6    | RF8 (v2)      | Gasto: "Uber 5.50"                | Clasifica automáticamente en "Transporte"   | Correcto           |
| Validación 3         | RF9 (v2)      | Recordatorio diario activado      | Envía notificación al usuario               | Correcto           |
| Validación 4         | RF10 (v2)     | Gasto futuro: 200; Saldo actual: 150 | Alerta: "El gasto futuro excederá tu presupuesto disponible" | Correcto |

---

## 🔧 Tipo de Mantenimiento Propuesto
Según Sommerville y Pressman, se aplican los siguientes tipos de mantenimiento:

- **Correctivo:** Resolver fallos como pérdida de datos o ausencia de alertas.  
- **Perfectivo:** Añadir nuevas funcionalidades (metas de ahorro, simulaciones, notificaciones).  
- **Adaptativo:** Asegurar compatibilidad con navegadores y móviles (PWA).  
- **Preventivo:** Refactorizar código en módulos y añadir pruebas para evitar errores futuros.  

---

## 🔄 Reflexión sobre el Control de Versiones
El uso de **GitHub y control de versiones** es esencial para este proyecto:  
- Permite mantener un historial claro de cambios en requerimientos, pruebas y mantenimiento.  
- Facilita la colaboración entre varios autores y el seguimiento de responsabilidades.  
- Garantiza que cada versión del sistema (v1, v2, mejoras de mantenimiento) quede documentada y accesible.  
- Reduce riesgos de pérdida de información y asegura trazabilidad en el ciclo de vida del software.  

---

## 📚 Bibliografía
- Sommerville, Ian. *Ingeniería del Software*. Pearson Addison-Wesley, 2005.  
- Pressman, Roger S. *Ingeniería del Software: Un enfoque práctico*. McGraw-Hill, 2005.  
- IEEE Std 830-1998. *Recommended Practice for Software Requirements Specifications*. IEEE, 2014.  
