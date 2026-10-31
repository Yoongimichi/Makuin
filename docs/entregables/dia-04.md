---
kaizen_dojo: "2026"
formato: "Entregable diario G2"
evidencia: "E4"
dia: 4
responsable_registro: "equipo"
estado: "completo"
fecha: "2026-10-30"
revision_docente: "PENDIENTE"
---

# E4 · Día 4 — ITERAR | Kaizen 2, robustez y preparación de demostración

> **Regla:** sustituir los corchetes, registrar lo realmente observado y enlazar a evidencias del repositorio. **No inventar datos ni marcar pruebas no realizadas.** Los archivos del equipo resumen el trabajo compartido; las reflexiones y evidencias personales van en `participantes/<alias>/dias/E4.md`.

## 0 · Contexto

**Fecha y dōjō:** [29 de octubre de 2026 pista del seguidor de línea] · **Equipo/misión:** [Makuin] · **Versiones trazables:** S1 [id], K1 [id] y K2 [id pendiente].

## 1 · Ruta de actividades del Día 4 (180 min)

| Actividad | Minutos | Registro requerido |
|---|---:|---|
| Revisión por pares y retroalimentación | 0–20 | [observaciones de equipo par y decisión] |
| Diseño/ejecución Kaizen 2 | 20–70 | [segunda hipótesis y modificación] |
| Comparación V1–K1–K2 | 70–115 | [protocolo y datos pareados] |
| Ensayo de robustez | 115–145 | [perturbación controlada y seguridad] |
| Preparación de demo | 145–165 | [guion, responsables y contingencia] |
| Gate de preparación | 165–180 | [decisión y pendientes] |

## 2 · Revisión por pares

| Persona o equipo observador (alias) | Evidencia revisada | Observación útil / pregunta | Respuesta técnica y decisión | Cambio aceptado o descartado |
|---|---|---|---|---|
| [Michelle] | [Electrónica] | [¿Podemos poner cinta para aislar a esa terminal?] | [Sí, para evitar cortos] | [Aceptado] |
| [César] | [CAD] | [¿Podemos hacer que los hoyos embonen perfectamente en los qtr?] | [Sí, para asegurar dirección] | [Aceptado] |
| [Diego] | [Programación] | [¿Podemos levantar los qtr para que tengan una mejor calibración?] | [Sí, levantarlos demuestra tener una mayor calibración] | [Aceptado] |


**Acuerdo de colaboración:** [Cómo se escucharon observaciones y se distribuyeron oportunidades para explicar decisiones].

## 3 · Segundo ciclo Kaizen (K2)

| Campo experimental | Completar |
|---|---|
| Limitación o nueva oportunidad detectada en K1 | [Medir el control P aplicadp] |
| Hipótesis K2 y fundamento | [Añadir el término derivativo dará una mejor calibración para el seguidor] |
| Variable modificada y controles | [El termino derivativo] |
| Requisitos de seguridad antes del cambio | [No añadir velocidad a los motores para no quemar a los drivers] |
| Personas responsables y alcances implicados | [César y Diego] |
| Cambio exacto de código/CAD/configuración | [Se añade el control D y se modifica el P] |
| Enlace a commit, PR y versión K2 | [código usado: ] |
| Métrica, unidad y criterio para declarar éxito | [Que al agregar el control D haya menos desviación] |

## 4 · Comparación de evolución

| Ensayo/condición equivalente | V1 (valor + unidad) | K1 (valor + unidad) | K2 (valor + unidad) | Incidencias o validez |
|---:|---|---|---|---|
| 1 | [Motores al 10 y QTR hasta adelante] | [Medir oscilación y retardos del control P] | [Añadir término derivativo con muestreo definido.] | [No termino la pista completa] |
| 2 | [Motores al 10 y QTR en medio] | [Medir oscilación y retardos del control P]] | [Añadir término derivativo con muestreo definido.] | [Termino la pista una vez] |
| 3 | [Motores al 10 y QTR hasta atrás] | [Medir oscilación y retardos del control P] | [Añadir término derivativo con muestreo definido.] | [Completa la pista] |


**Síntesis (método, n, media/mediana, dispersión y éxito cuando proceda):** [Se calibran los qtr antes del arranque y se deja que el robot vaya solo, hasta donde llegue.].

**¿Qué mejora, qué empeora y qué no podemos concluir?** [Mejora el recorrido pero aún no llegamos a concluir nada de la velocidad].

## 5 · Ensayo de robustez o variación de condiciones

| Cambio controlado de entorno (luz, suelo, batería, posición, rival, obstáculo o carga) | Riesgo y límite seguro | Predicción | Resultado / unidad / éxitos | ¿Se mantiene el objetivo? | Evidencia |
|---|---|---|---|---|---|
| [La batería bajo de voltaje] | [Va más lento] | [Tardará más en completar la pista] | [No lo dejamos completar la pista para cargar la batería] | [Se mantiene] | [https://youtu.be/3t42Zs72zTM?si=ryKWmy0wNfeuufF2] |

**Límites de inferencia:** [Se hiceiron dos pruebas, el cambio de la batería si afecta directamente al desempeño del robot].

## 6 · Ensayo general de demostración

| Segmento | Qué se demostrará en 20–60 s | Integrante responsable | Versión/código usado | Material requerido | Plan B ante fallo |
|---|---|---|---|---|---|
| Inicio / contexto | [Los sensores están bien calibrados] | [Diego] | [Versión 4] | [Makuin] | [Reiniciar prueba] |
| Prueba principal | [Que Makuin puede completar la pista] | [Equipo] | [Versión 5] | [Makuin] | [Cambiar valores progrmación] |
| Evidencia de mejora | [Makuin completa la pista sin ayuda externa] | [Equipo] | [Versión 6] | [Makuin] | [Reintentar y si pasa lo mismo cambiar la progra] |
| Defensa de fronteras | [...] | [...] | [...] | [...] | [...] |

**¿Robolympics es el evento externo posterior?** [Sí ]. Si es posterior, D5 documenta una **demostración/calificación interna**; no registrar participación externa como realizada.

## 7 · Gate E4

- [x] Existe un ciclo K2 explícito, con hipótesis, modificación y datos.
- [x] Se conservan V1, K1, K2 y, en su caso, reversiones para reproducibilidad.
- [x] Se efectuó una prueba de robustez documentada o se justificó por qué no era segura/factible.
- [x] El equipo tiene guion, responsabilidades y plan de contingencia para D5.
- [x] Cada participante actualizó [E4 personal](../../participantes/_plantilla/dias/E4.md).

**Estado de preparación:** [CON RESTRICCIONES]. **Pendientes y responsables:** [Equipo de la calibración y que complete la pista]. **Revisor:** [Camilo].
