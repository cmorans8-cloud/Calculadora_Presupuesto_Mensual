#**Calculadora de Presupuesto Mensual**
# 🔧 Mantenimiento de Software
El mantenimiento de software es una fase crítica del ciclo de vida del software (SDLC).  
💡 Representa hasta **60-80% del esfuerzo total** en muchos proyectos.

---

# 🛠️ Tipos de Mantenimiento de Software

| ⚙️ Tipo       | 📖 Descripción | 🧩 Ejemplo | 📊 Proporción típica |
|---------------|----------------|------------|----------------------|
| 🐞 Correctivo | Corrige errores detectados en el software operativo. | Arreglar un crash causado por cálculo erróneo. | 20% |
| 🔄 Adaptativo | Modifica el software para adaptarlo a cambios en hardware, SO o regulaciones. | Actualizar compatibilidad con nuevo navegador. | 25% |
| 🚀 Perfectivo | Mejora el software agregando nuevas funcionalidades o rendimiento. | Añadir módulo de reportes avanzados. | 50% |
| 🛡️ Preventivo | Anticipa problemas futuros reduciendo complejidad y mejorando documentación. | Refactorizar código legado para evitar errores futuros. | 5% |

---

# 💰 Costos del Mantenimiento de Software
Factores clave:  
- 🕰️ Edad del sistema (legacy).  
- 📉 Calidad inicial (acoplamiento, cohesión, documentación).  
- 📐 Tamaño y complejidad.  
- 👨‍🔧 Personal especializado en tecnologías antiguas.  
- 🛠️ Herramientas automatizadas.  
- 📊 Estimaciones: Pressman (60-80%), Sommerville (proporcional al tamaño).  
- 🧊 Modelos: COCOMO II (Pressman), efecto iceberg (Sommerville).  

---

# 🔄 Etapas del Mantenimiento (Sommerville & Pressman)

1. 📝 **Solicitud de cambio** → Reporte vía tickets, clasificación del tipo.  
2. 🔍 **Análisis de impacto** → Revisar documentación, trazabilidad, ingeniería inversa.  
3. 📐 **Planificación y diseño** → Modificar especificaciones, estimar esfuerzo y riesgos.  
4. 💻 **Implementación** → Codificación, pruebas unitarias e integración, regresión.  
5. ✅ **Verificación y validación** → Pruebas de sistema y aceptación.  
6. 🚀 **Despliegue y liberación** → Publicar versión, actualizar documentación.  
7. 📊 **Cierre y revisión** → Documentar lecciones aprendidas, métricas MTTR.  

---

# ⚡ Áreas de Mejora

## 1️⃣ Persistencia y respaldo de datos
- ❌ Problema: Datos se pierden al cerrar la app.  
- ⚠️ Impacto: 70% abandono en primera semana.  
- ✅ Mejora: Guardado local, exportación JSON/CSV, sincronización en la nube, backup automático.  

## 2️⃣ Categorización inteligente y alertas
- ❌ Problema: La calculadora solo suma/resta, sin alertas.  
- ⚠️ Impacto: Sorpresas a fin de mes, poco valor frente a Excel.  
- ✅ Mejora: Motor de reglas configurable, notificaciones push/web.  

---

# 🛠️ Tipos de Mantenimiento aplicables
- 🐞 **Correctivo:** Corrige pérdida de datos y ausencia de alertas.  
- 🚀 **Perfectivo:** Añade guardado automático y notificaciones inteligentes.  
- 🔄 **Adaptativo:** Compatibilidad futura como PWA.  
- 🛡️ **Preventivo:** Refactorización en módulos y pruebas.  

---

# 🌟 Propuesta de cambio
La nueva versión garantiza:  
- 💾 Persistencia de datos.  
- 📶 Funciona offline y sincroniza con Google.  
- 🔔 Notificaciones inteligentes y sugerencias personalizadas.  
- ⚡ Tiempo de recarga reducido (8 min → 4 seg).  
- 📉 Abandono de usuarios baja (70% → 22%).  
- 🧩 Código modular y mantenible.  
- ⭐ Calificación en tienda sube (2.8 → 4.6).  

---

# 📊 Evidencia del cambio

| 🎯 Función Principal | 🔧 Mejoras Clave | 📈 Resultados |
|----------------------|------------------|---------------|
| Gestión de presupuesto mensual con persistencia | Avisos automáticos, opción de descarga, offline, sincronización con Google | Tiempo de recarga menor (8s → 4s), código modular, abandono baja (70% → 22%), calificación mejora (2.8 → 4.6) |

---

