---
kit: "Kaizen Dōjō 2026 — Compromiso de misión"
version_catalogo: "C2 / 1.1"
participante: "César Ortega Martínez"
equipo: "Makuin"
mision: "M03"
plataforma: "Seguidor de línea"
territorio_personal: "E · EXPLORAR"
frontera_personal: "F1 · INTEGRAR"
validacion_docente: "PENDIENTE"
---

# Mi compromiso Kaizen · 2026

> **Mi desafío:** Hacer un controlador para que el seguidor se mantenga en el centro de la línea

## 1. Mi misión y mi frontera

- **Participante:** César Ortega Martínez
- **Equipo:** Makuin
- **Plataforma:** M03 · Seguidor de línea
- **Territorio personal:** E · EXPLORAR
- **Frontera personal:** F1 · INTEGRAR

**Hoy todavía no puedo:**

Integrar un sistema de seguidor de línea funcional, eficaz y óptimo que vaya a una gran velocidad y siga un recorrido sin desviarse y suavemente

**Al finalizar Kaizen Dōjō demostraré que puedo:**

Hacer un controlador para que el seguidor se mantenga en el centro de la línea

**La evidencia o indicador que utilizaré:**

Por medio de videos, que muestres el adecuado funcionamiento del seguidor realizando el recorrido.

**Mi motivación:**

Porque es el primer paso para tener un prototipo funcional de seguidor de línea, para después optimizarlo y tenerlo listo para competir.

## 2. Alcances y katas seleccionados

Esta es mi propuesta individual dentro de una misión colaborativa. Cada alcance requiere evidencia de contribución propia y negociación de viabilidad.

### 1. SL03 · Integrar control diferencial de motores

- **Tipo:** Preestablecido · catálogo C2
- **Territorio sugerido:** DOMINAR
- **Frontera sugerida:** F1 · INTEGRAR
- **Carta:** D1 · AUTONOMOUS SYSTEM
- **Duración estimada:** 2–3 h
- **Resultado esperado / aceptación:** Control PWM independiente por rueda, con pruebas de avance y giro.
- **Recursos o prerequisitos:** Driver y electrónica compatibles; plataforma lista.

**Katas elegidos**

- [ ] Identificar conexiones y comprobar polaridad/paro.
- [ ] Programar velocidades izquierda y derecha con rango seguro.
- [ ] Ejecutar avance recto y giro, midiendo desvíos visibles.
- [ ] Crear una proporción entre el valor del PWM de un motor con respecto al otro para que tengan la misma velocidad _(propuesta propia)

**Mi evidencia final:** _Completar al avanzar el proyecto_

**Enlaces a código/CAD/pruebas:** _Agregar enlaces relativos al repositorio_

### 2. SL05 · Estimar posición lateral de línea

- **Tipo:** Preestablecido · catálogo C2
- **Territorio sugerido:** DOMINAR
- **Frontera sugerida:** F2 · DECIDIR
- **Carta:** D1 · AUTONOMOUS SYSTEM
- **Duración estimada:** 3–4 h
- **Resultado esperado / aceptación:** Función que transforme el arreglo de sensores en error firmado respecto al centro.
- **Recursos o prerequisitos:** Sensor calibrado y datos seriales disponibles.

**Katas elegidos**

- [ ] Representar patrones de sensores para izquierda/centro/derecha.
- [ ] Implementar cálculo de posición ponderada o regla equivalente.
- [ ] Mover manualmente el robot y contrastar signo y magnitud de error.

**Mi evidencia final:** _Completar al avanzar el proyecto_

**Enlaces a código/CAD/pruebas:** _Agregar enlaces relativos al repositorio_

### 3. SL06 · Programar seguidor proporcional básico

- **Tipo:** Preestablecido · catálogo C2
- **Territorio sugerido:** DOMINAR
- **Frontera sugerida:** F2 · DECIDIR
- **Carta:** D1 · AUTONOMOUS SYSTEM
- **Duración estimada:** 3–4 h
- **Resultado esperado / aceptación:** Robot que completa un tramo sencillo mediante corrección proporcional.
- **Recursos o prerequisitos:** Lectura de error lateral y motores integrados.

**Katas elegidos**

- [ ] Programar una corrección P con ganancias acotadas.
- [ ] Seguir una recta y una curva de ensayo sin perder la pista.
- [ ] Ajustar ganancia y comparar oscilación antes/después.
- [ ] Realizar análisis estadísticos para encontrar el mejor valor P _(propuesta propia)

**Mi evidencia final:** _Completar al avanzar el proyecto_

**Enlaces a código/CAD/pruebas:** _Agregar enlaces relativos al repositorio_

## 3. Planeación y viabilidad

- **Alcances:** 3 de un máximo de 3
- **Katas:** 11
- **Esfuerzo técnico estimado:** 8–11 horas
- **Disponibilidad orientativa:** 8–10 horas de trabajo técnico dentro de las 15 horas presenciales.
- **Estado:** REQUIERE REVISIÓN: el máximo estimado supera 10 horas

## 4. Mi bitácora Kaizen (cinco sesiones)

| Día | Evidencia que registraré | Estado |
|---|---|---|
| D1 · Atreverse | Diagnóstico y pacto de frontera | [ ] |
| D2 · Hacer | Prototipo / primera integración V1 | [ ] |
| D3 · Medir | Ensayo base y ciclo Kaizen 1 | [ ] |
| D4 · Iterar | Ciclo Kaizen 2 y comparación V1–Vn | [ ] |
| D5 · Demostrar | Desafío, evidencia y reflexión | [ ] |

## 5. Mi protocolo de mejora

### Ciclo Kaizen 1

- **Hipótesis:** _Por documentar_
- **Cambio implementado:** _Por documentar_
- **Métrica base:** _Por documentar_
- **Resultado:** _Por documentar_

### Ciclo Kaizen 2

- **Hipótesis:** _Por documentar_
- **Cambio implementado:** _Por documentar_
- **Comparación con V1:** _Por documentar_
- **Aprendizaje:** _Por documentar_

## 6. Cierre y reflexión

**Antes no podía:** _Por completar_

**Ahora puedo:** _Por completar_

**Cómo lo demostré:** _Por completar_

**Qué intentaría mejorar después:** _Por completar_

---

_Documento generado localmente con el configurador Kaizen Dōjō 2026 · catálogo C2. El estudiante debe revisar y acordar con el profesor los alcances y condiciones de seguridad antes de operar robots físicos._

**Fuente de catálogo:** https://docs.google.com/spreadsheets/d/1FKxFzoyu9KJb3RlOwB609vliS5hAtmwWFu2G2zG3Ky4/edit
