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
* **Repositorio en GitHub:** https://github.com/Lucianof85/TPI-Organizacion-Empresarial-La-Camionera-Mendocina
* **Tablero Ágil de Gestión:** https://github.com/users/Lucianof85/projects/1

---

### Dinámica de Versionado y Trabajo Colaborativo (Git Flow)
* **Rama `main`:** Versión publicada de la documentación del proyecto.
* **Rama secundaria `docs/portada-y-versionado`:** Corrección de los enlaces de la portada y documentación del flujo de colaboración.
* **Commits descriptivos:** Cada cambio debe indicar qué se modificó y con qué propósito.
* **Pull Requests (PR):** Los cambios de la rama secundaria se proponen hacia `main`. Antes de integrarlos, un compañero debe revisar el contenido y dejar su revisión registrada en GitHub.
* **Revisión de pares e integración:** [PR #1](https://github.com/Lucianof85/TPI-Organizacion-Empresarial-La-Camionera-Mendocina/pull/1) integrado a `main` el 29 de octubre de 2026, con revisión de `rojovelero` registrada mediante comentario de revisión.

---

### Declaración Crítica sobre el Uso de Inteligencia Artificial
En estricto cumplimiento con la pauta pedagógica de la cátedra:
* Se recurrió al uso de asistentes de IA Generativa para agilizar la sintaxis de diagramación gráfica (código Mermaid para BPMN) y parametrizar la estructura de historias de usuario y métricas de desempeño.
* **Control humano estricto:** El estudiante corrigió las propuestas del modelo descartando entidades genéricas de e-commerce, incorporó la entidad de telemetría POSICION_GPS, desglosó el peso real y volumétrico, y aseguró la coherencia con las restricciones operativas de La Camionera Mendocina S.R.L.


### Asistencia de IA en esta actualización
Se utilizó ChatGPT para revisar la portada, detectar enlaces que no correspondían a este repositorio y proponer la documentación del flujo de ramas, commits y Pull Requests. La revisión del contenido por un compañero y su aprobación deben quedar registradas antes de integrar esta actualización en `main`.


### Seguimiento del backlog ágil
El tablero de GitHub Projects está vinculado a este repositorio y organiza el trabajo en **Por Hacer**, **En Progreso** y **Listo**. Incluye el PR #1 integrado como evidencia de una actividad terminada. Las tres historias de usuario están vinculadas al tablero como issues del repositorio:

| Historia | Funcionalidad | Estado |
| --- | --- | --- |
| [US-01](https://github.com/Lucianof85/TPI-Organizacion-Empresarial-La-Camionera-Mendocina/issues/2) | Transmisión periódica de coordenadas GPS | Listo |
| [US-02](https://github.com/Lucianof85/TPI-Organizacion-Empresarial-La-Camionera-Mendocina/issues/3) | Escaneo QR y asociación a hoja de ruta | Listo |
| [US-03](https://github.com/Lucianof85/TPI-Organizacion-Empresarial-La-Camionera-Mendocina/issues/4) | Firma digital y DNI para comprobante de entrega | Listo |

El 31 de octubre de 2026 el responsable del proyecto confirmó que las tres funcionalidades están implementadas y verificadas. El estado del tablero refleja esa confirmación. El historial de cada issue conserva su incorporación y cierre; no se reconstruyen etapas anteriores.


Para esta actualización se utilizó ChatGPT como apoyo para completar el formato «Como [usuario], quiero [funcionalidad], para [beneficio]» a partir de los títulos cargados por el estudiante. La confirmación de implementación y verificación fue proporcionada por el responsable del proyecto.
