---
kaizen_dojo: "2026"
formato: "Entregable diario G2"
evidencia: "E3"
dia: 3
responsable_registro: "equipo"
  estado: "Completo"
fecha: "2026-10-28"
revision_docente: "PENDIENTE"
---

# E3 · Día 3 — MEDIR Y APRENDER | Kaizen 1: ensayo, hipótesis y mejora

> **Regla:** sustituir los corchetes, registrar lo realmente observado y enlazar a evidencias del repositorio. **No inventar datos ni marcar pruebas no realizadas.** Los archivos del equipo resumen el trabajo compartido; las reflexiones y evidencias personales van en `participantes/<alias>/dias/E3.md`.

## 0 · Contexto de investigación de hoy

**Fecha/equipo/misión:** 28-10-2026 · **Dōjō exacto:** laboratorio de electrónica · **Versión de partida:** [commit/etiqueta V1] · **Protocolo E2:** [enlace].

## 1 · Ruta del Día 3 (180 min)

| Actividad | Minutos | Evidencia a registrar |
|---|---:|---|
| Analizar un fallo real / demostración | 0–15 | [fallo observado; condiciones] |
| Diseño del experimento | 15–40 | [hipótesis, variable, controles, riesgo] |
| Diagnóstico del prototipo V1 | 40–80 | [causa probable y prueba discriminante] |
| Kaizen 1: cambio técnico | 80–125 | [diff, firmware, CAD, integración] |
| Reensayo equivalente | 125–160 | [datos crudos V1 vs K1] |
| Documentar, debatir, reflejar | 160–180 | [conclusión y E3 personal] |

## 2 · Problema, hipótesis y trazabilidad

| Campo | Completar |
|---|---|
| Fallo / oportunidad de mejora observada (con evidencia) | [El CAD tuvo errores de diseño] |
| Dónde se presenta y cuántas veces | [En el diseño CAD, se presentó en dos impresiones siendo la tercera la correcta] |
| Diagnóstico: causas alternativas que se consideraron | [Los pines soldados en el qtr estaban mal colocados] |
| Hipótesis contrastable: **si cambio X, espero que Y ocurra porque Z** | [Si cambio el hoyo de los tornillos, espero que el qtr quepa en los diferentes soportes porque se movio la distancia de los centros de los hoyos.] |
| Variable independiente que se modifica | [Hoyo de los tornillos] |
| Métrica de resultado con unidad y criterio de mejora | [Los soportes de los qtr quedan derechos sin necesidad de moverlos para que queden alineados.] |
| Variables que se mantendrán iguales | [Diametro de los hoyos, largo de los soportes.] |
| Ensayos requeridos y forma de muestreo | [En las 5 distancias posibles, los qtr quedan alineados en todas sin necesidad de doblarlos.] |
| Riesgo de sesgo/confusión y cómo se mitigará | [A ojo quedarían bien, pero se mitiga usando un nivel para ver que quede recto.] |
| Parada de seguridad / condición de aborto | [Que se quiebre la línea.] |

## 3 · Colaboración y cambio técnico Kaizen 1

| Alias y alcance | Kata asociado (código o propio) | Qué cambió exactamente | Por qué | Código/CAD/commit y responsable de revisión | Validación de interfaz |
|---|---|---|---|---|---|
| [Michelle] | [...] | [Nada | [Ha cumplido con su trabajo] | [CAD] | [...] |
| [César] | [...] | [Nada | [Ha cumplido con su trabajo] | [Motores] | [...] |
| [Diego] | [...] | [Nada | [Ha cumplido con su trabajo] | [Calibración QTR] | [...] |

**Identificador de versión K1:** [...]. **Otras modificaciones involuntarias o perturbaciones:** [...].

## 4 · Ensayos comparables

**Enlace a datos crudos CSV:** [`../../datos/ensayos.csv`](../../datos/ensayos.csv) · **Protocolo:** [`../../pruebas/protocolo.md`](../../pruebas/protocolo.md).

| Prueba emparejada o bloque | Condición/escenario idéntico | V1, valor + unidad | K1, valor + unidad | Cambio / resultado | Incidencia o desviación |
|---:|---|---|---|---|---|
| 1 | [...] | [...] | [...] | [...] | [...] |
| 2 | [...] | [...] | [...] | [...] | [...] |
| 3 | [...] | [...] | [...] | [...] | [...] |
| 4 | [...] | [...] | [...] | [...] | [...] |
| 5 | [...] | [...] | [...] | [...] | [...] |

**N válido V1 / K1:** [... / ...]. **Resumen, variabilidad y tasa de éxito:** [...]. **Incertidumbres/limitaciones:** [...].

## 5 · Interpretación y decisión

- **¿La evidencia respalda, contradice o no permite decidir la hipótesis?** [...]
- **Si no hubo mejora, qué aprendimos:** [...]
- **¿Qué riesgo o compromiso generó el cambio?** [...]
- **Decisión:** [conservar K1 / revertir / revisar / recolectar más datos], con razón: [...]
- **Siguiente pregunta para Kaizen 2:** [...]

## 6 · Puerta de salida E3

- [ ] V1 y K1 tienen identificadores o referencias inequívocas.
- [ ] La hipótesis está conectada con una medida y un problema diagnosticado.
- [ ] Se documentó una modificación técnica y su responsable.
- [ ] Ensayos y resultados mantienen condiciones comparables o exponen diferencias explícitamente.
- [ ] La conclusión es honesta, incluso si el resultado es negativo.
- [ ] Cada estudiante registró su [E3 personal](../../participantes/_plantilla/dias/E3.md).

**Gate E3:** [APROBADO / CONDICIONADO]. **Revisor:** [...]. **Enlace a PR/commit:** [...].
