# Sistema de Gestión Logística y Trazabilidad en Tiempo Real
## La Camionera Mendocina S.R.L.

**Trabajo Práctico Integrador y Progresivo (TPI)**  
**Carrera:** Tecnicatura Universitaria en Programación a Distancia (TUPaD)  
**Institución:** Universidad Tecnológica Nacional (UTN)  
**Asignatura:** Organización Empresarial (2026)  
**Estudiante:** Bernardo Luciano Fernández  
**Cuerpo Docente:** Prof. Gabriela Martínez (Titular), Prof. Carolina Bruno, Prof. Mario Raúl López, Prof. Andrea Ramos  

---

### Descripción del Sistema
Módulo de software diseñado para transformar integralmente las operaciones de transporte de cargas y encomiendas de **La Camionera Mendocina S.R.L.**. El sistema incorpora:
1. **Admisión y Cubicaje Digital:** Registro de peso bruto, peso volumétrico y emisión de rótulos con código QR (entidad ENVIO_ENCOMIENDA).
2. **Consolidación de Viajes:** Asignación de bultos a unidades vehiculares y trayectos troncales (entidad HOJA_RUTA_VIAJE).
3. **Telemetría y Rutas Satelitales en Vivo:** Monitoreo en tiempo real de coordenadas, velocidad y alertas reportadas por módems GPS a bordo (entidad POSICION_GPS).
4. **Remito Digital y Conformidad Móvil (PoD):** Captura de firma digital táctil y DNI del receptor en destino (entidad ENTREGA_REMITO).

---

### Enlaces Oficiales del Proyecto
* **Repositorio en GitHub:** https://github.com/bernardolfernandez/TPI-Organizacion-Empresarial-La-Camionera-Mendocina
* **Tablero Ágil de Gestión:** https://github.com/users/bernardolfernandez/projects/1

---

### Dinámica de Versionado y Trabajo Colaborativo (Git Flow)
* **Rama main:** Versión oficial consolidada y aprobada para el Coloquio Integrador.
* **Rama secundaria feature/tpi4-bpmn-kpis-agile:** Modelado BPMN, historias de usuario y matriz de control (KPIs).
* **Pull Requests (PR):** Integración formal con revisión y cierre de tareas.

---

### Declaración Crítica sobre el Uso de Inteligencia Artificial
En estricto cumplimiento con la pauta pedagógica de la cátedra:
* Se recurrió al uso de asistentes de IA Generativa para agilizar la sintaxis de diagramación gráfica (código Mermaid para BPMN) y parametrizar la estructura de historias de usuario y métricas de desempeño.
* **Control humano estricto:** El estudiante corrigió las propuestas del modelo descartando entidades genéricas de e-commerce, incorporó la entidad de telemetría POSICION_GPS, desglosó el peso real y volumétrico, y aseguró la coherencia con las restricciones operativas de La Camionera Mendocina S.R.L.
