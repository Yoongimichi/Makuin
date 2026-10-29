---
kaizen_dojo: "2026"
formato: "Entregable diario G2"
evidencia: "E2"
dia: 2
responsable_registro: "equipo"
estado: "PENDIENTE"
fecha: "2026-10-27"
revision_docente: "PENDIENTE"
---

# E2 · Día 2 — HACER | Primera integración funcional y línea base V1

> **Regla:** sustituir los corchetes, registrar lo realmente observado y enlazar a evidencias del repositorio. **No inventar datos ni marcar pruebas no realizadas.** Los archivos del equipo resumen el trabajo compartido; las reflexiones y evidencias personales van en `participantes/<alias>/dias/E2.md`.

## 0 · Identificación y continuidad

| Campo | Dato |
|---|---|
| Fecha, equipo, misión y plataforma | 2026-10-27, Makuin, M03 seguidor |
| Dōjō real y mesa/zona utilizada | laboratorio de electrónica |
| Estado del gate E1 / cambios desde D1 | Pendiente la revisión de Camilo, decidimos continuar con lo ya pensado |
| Kit por integrante / compromisos modificados | [enlaces relativos y motivo de modificación] |
| Materiales recibidos y pendientes | PLA, Motores, QTR, Multímetro, Pinzas, cable, Arduino IDE, Pista|
| Objetivo técnico del Día 2 | Probar sensores, motores y tener el Cad del seguidor de línea listo |

## 1 · Ruta de las actividades de hoy (180 min)

| Bloque | Minutos | Registro requerido / evidencia |
|---|---:|---|
| Revisión de misión y compromisos | 0–15 | [pactos; bloqueos abiertos y resueltos] |
| Microlección aplicada | 15–35 | [técnica, recurso, ejemplo, pregunta clave] |
| Katas de integración | 35–105 | [quién realizó qué kata; archivo o foto de su aporte] |
| Ensayos iniciales / línea base | 105–145 | [protocolo, ensayos, valores y unidad] |
| Consolidación de evidencia | 145–170 | [commits, CAD, logs y versión V1] |
| Gate E2 | 170–180 | [aprobación y objetivos para Kaizen 1] |

## 2 · Microlección e integración por alcances

**Tema que resolvió un problema real del equipo:** [...]. **Material / referencia utilizada:** [...].

| Alias | Alcance | Kata seleccionado / nuevo | Acción técnica ejecutada | Archivo, commit o plano | Estado (pendiente/probado/bloqueado) | Dependencia de otro integrante |
|---|---|---|---|---|---|---|
| Michelle Corona | [SL01+02] | [Kata 1,2,3] | Se realizó la primera versión del CAD | [`../../codigo/...`] | pendiente a imprimir/mejorar | nada |
| César Ortega | [SL03+05+06] | [Kata 1,2,3+propia] | Se consiguieron los motores | [`../../codigo/...`] | [...] | Dependencia de tener la carcasa para poder probar de manera correcta los motores|
| Diego Flores | [SL04+09,10] | [Kata 1,2] | Se obtuvo el QTR y se probó que funcionara | [`../../codigo/...`] | [probado | nada|
## 3 · Estado de integración V1

| Subsistema | Entrada | Salida esperada | Responsable | Prueba de integración y observación | Evidencia |
|---|---|---|---|---|---|
| Estructura/mecánica | [...] | [...] | [...] | [...] | [...] |
| Energía y accionamiento | [...] | [...] | [...] | [...] | [...] |
| Sensores/percepción | [...] | [...] | [...] | [...] | [...] |
| Control/software | [...] | [...] | [...] | [...] | [...] |
| Integración global | [...] | [...] | [...] | [...] | [...] |

**Versión identificable:** [commit SHA/etiqueta/firmware/CAD/paquete; no usar solo “última versión”]. **Comportamiento que SÍ demuestra V1:** [...]. **Lo que aún falla:** [...].

## 4 · Protocolo y línea base del robot (datos observados)

Completar también [`pruebas/protocolo.md`](../../pruebas/protocolo.md) y registrar datos crudos en [`datos/ensayos.csv`](../../datos/ensayos.csv).

| Campo de validez experimental | Respuesta obligatoria |
|---|---|
| Pregunta y resultado que se quiere medir | [...] |
| Métrica primaria + unidad (segundos, %, cm, rad, etc.) | [...] |
| Éxito/fallo (criterio cuantitativo u observable) | [...] |
| Lugar, configuración, pista/dohyō/estaciones/marcadores | [...] |
| Configuración del robot: batería, firmware y sensores | [...] |
| Condiciones controladas: luz, rival, posición de inicio, etc. | [...] |
| Número de corridas planeadas / ejecutadas | [... / ...; justificar si menos de 5] |
| Procedimiento reproducible, responsable y seguridad/aborto | [...] |
| Datos sin procesar y video/foto corta | [enlace a CSV y evidencias externas de acceso controlado] |

| Ensayo | Condición inicial | Valor (+ unidad) | Éxito/fallo | Observación relevante / incidencia |
|---:|---|---|---|---|
| 1 | [...] | [...] | [...] | [...] |
| 2 | [...] | [...] | [...] | [...] |
| 3 | [...] | [...] | [...] | [...] |
| 4 | [...] | [...] | [...] | [...] |
| 5 | [...] | [...] | [...] | [...] |

**Línea base resumida (no fabricada):** [n válido; media/mediana si aplica; dispersión; tasa de éxito; casos descartados y razón — no borrar ensayos desfavorables].

## 5 · Decisiones al cierre, bloqueos y Kaizen de mañana

| Fallo o cuello de botella observado | Hipótesis preliminar | Prioridad | Responsable | Material / apoyo necesario |
|---|---|---|---|---|
| [...] | [...] | [...] | [...] | [...] |

- [ ] Hay prototipo V1, subsistema funcional verificable o fallo reproducible con condiciones registradas.
- [ ] Existen archivos fuente o evidencia técnica enlazada, además de videos de uso controlado cuando correspondan.
- [ ] Hay protocolo reproducible y valores basales con unidad o justificación de lo que no pudo medirse.
- [ ] Cada alumno actualizó su [E2 personal](../../participantes/_plantilla/dias/E2.md) con contribución propia y límite de capacidad actual.
- [ ] Se mantuvieron límites de seguridad y protección de datos.

**Gate E2:** [APROBADO / CONDICIONADO / REPLANIFICAR]. **Revisor:** [...] **Fecha:** [...].

**Próxima prioridad de Kaizen 1:** [...]. **Enlace al commit/PR:** [...].
