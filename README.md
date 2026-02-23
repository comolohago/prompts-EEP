# ENGINEERING EXECUTION PROTOCOL
### LLM Strict Mode

Una forma estructurada y segura de trabajar con IA para resolver problemas de ingeniería.

Este protocolo existe por una razón simple:

Los modelos de lenguaje tienden a:
- Asumir información que no fue entregada
- Generar código demasiado rápido
- Ignorar casos borde
- Inventar garantías externas

Este documento obliga al modelo a pensar antes de actuar.

---

# 🎯 ¿Qué problema resuelve?

Cuando usamos IA para programar o diseñar sistemas, muchas veces obtenemos:

- Código apresurado
- Supuestos ocultos
- Arquitecturas innecesariamente complejas
- Errores que solo aparecen en producción

Este protocolo fuerza:

- Modelado explícito del problema
- Separación clara entre diseño e implementación
- Validación estructurada
- Declaración de limitaciones

---

# 🧠 Idea central

Nunca generar código antes de entender completamente el problema.

---

# 📋 Estructura del Protocolo

El modelo DEBE seguir estas fases en orden:

---

## PHASE 1 — PROBLEM MODELING

1. PROBLEM_RESTATEMENT  
2. ASSUMPTIONS  
3. CONSTRAINTS  
4. SUCCESS_CRITERIA  

Objetivo: entender el problema antes de diseñar nada.

---

## PHASE 2 — DESIGN

5. INVARIANTS  
6. MINIMAL_DESIGN  
7. ALTERNATIVES  
8. RISKS  

Objetivo: diseñar con claridad, simplicidad y conciencia de riesgos.

---

## PHASE 3 — IMPLEMENTATION

9. IMPLEMENTATION  

Reglas:
- Comportamiento determinista
- Manejo explícito de errores
- Sin efectos secundarios ocultos
- Sin abstracciones especulativas
- Sin optimización prematura

---

## PHASE 4 — VALIDATION

10. CRITERIA_VERIFICATION  
11. EDGE_CASE_COVERAGE  
12. LIMITATIONS  

Objetivo: comprobar que lo construido realmente cumple lo prometido.

---

# 🌎 Reglas Globales

- Está prohibido generar código antes de PHASE 3.
- Si falta información, el modelo debe responder:

  "INSUFFICIENT INFORMATION"

  y listar exactamente qué falta.
- Preferir corrección sobre elegancia.
- Preferir simplicidad sobre inteligencia innecesaria.
- Nunca asumir garantías externas no especificadas.
- Si una sección no tiene contenido, escribir "NONE".

---

# 💡 Cómo usarlo

1. Copia el protocolo.
2. Pégalo antes de tu pregunta.
3. Luego describe el problema.
4. Obliga al modelo a seguir las fases.
5. No permitas que salte pasos.

---

# 🔍 Ejemplo simple

Pregunta normal:

"Implementa un sistema de pagos."

Resultado típico:
- Código inmediato
- Supuestos inventados
- Sin definición de estados

Con Strict Mode:

El modelo primero:
- Pregunta por moneda
- Define estados válidos
- Identifica riesgos de doble cobro
- Declara información faltante

Eso cambia completamente la calidad del resultado.

---

# ⚠️ Importante

Este protocolo no hace que la IA sea más inteligente.

Hace que piense de forma más estructurada.

---

# 📌 Filosofía

La ingeniería no es escribir código.
Es reducir incertidumbre.

Este protocolo reduce incertidumbre antes de permitir implementación.

---

# 🚀 Próximos pasos

En este repositorio encontrarás:
- Ejemplos comparativos
- Casos con información incompleta
- Problemas con riesgos ocultos
- Implementaciones demostrativas

---

# Licencia

Uso libre. Mejora continua bienvenida.