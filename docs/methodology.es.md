# Metodología: de respuestas por roles a una prueba de estrés de decisiones

**Idiomas:** [中文](methodology.md) · [English](methodology.en.md) · [日本語](methodology.ja.md) · [Français](methodology.fr.md) · [Español](methodology.es.md)

## Objetivo

Five-Advisor Review no consiste en que cinco roles hablen por turnos. Usa métodos de razonamiento distintos para exponer vulnerabilidades, oportunidades omitidas y bloqueos de ejecución de una misma propuesta. La salida debe ayudar a decidir si avanzar, avanzar con condiciones, pausar o abandonar, y qué validar después.

## Flujo

```text
Ficha de revisión
  → Cinco opiniones iniciales aisladas
  → Revisión cruzada anónima
  → Prueba de estrés del consenso
  → (Riesgo alto y desacuerdo relevante) revisión adversarial
  → Decisión de la presidencia y acción de validación
```

### 1. Ficha de revisión

Fije propuesta, objetivo, público, restricciones, decisión actual e incógnitas críticas. Así todos los asesores revisan el mismo objeto.

### 2. Cinco opiniones iniciales aisladas

Cada asesor lee solo la ficha. El aislamiento no crea independencia ficticia de modelos; reduce el anclaje en la primera opinión.

| Asesor | Método | Resultado principal |
|---|---|---|
| Refutador | Inversión | Fallos probables, contraejemplos y efectos a largo plazo |
| Cuestionador de fundamentos | Descomposición | Supuestos causales que pueden cambiar la decisión |
| Descubridor de oportunidades | Analogía | Alternativas omitidas y prioridad |
| Persona no experta | Preguntas ingenuas | Comprensión, confianza, precio y esfuerzo de una persona común |
| Ejecutor implacable | Grafo de dependencias | Primer bloqueo, acción de hoy, entregable y condición de parada |

En modo completo, cada asesor también indica evidencia crítica, mayor incógnita y evidencia que invertiría su conclusión.

### 3. Revisión cruzada anónima

Reordene las opiniones como candidatas A a E sin mostrar roles. Evalúe el razonamiento: la opinión más decisiva, la más débil, si el desacuerdo es una compensación de valores o una corrección factual, y qué omitieron todas.

### 4. Prueba de estrés del consenso

- **Comprobación de origen compartido:** si la mayoría depende de un supuesto o ruta de razonamiento, cuenta como una opinión repetida.
- **Abogado del diablo:** escriba el argumento único más fuerte contra el consenso. Si puede ser correcto, consérvelo para la decisión final.

### 5. Decisión de la presidencia

La presidencia no es un sexto asesor. Edita, arbitra e integra la acción: conserva disensos con evidencia, separa compensaciones de valores de errores factuales, explicita bloqueos y convierte incógnitas en validaciones.

## Riesgo, modos y etiquetas

| Riesgo | Salida |
|---|---|
| Bajo | Modo rápido: una frase por asesor y una validación de bajo coste |
| Medio | Modo completo: aislamiento, revisión cruzada, prueba y criterios de validación |
| Alto | Modo completo con validación reforzada; revisión adversarial si procede |

Las etiquetas son: `[Hecho verificado]`, `[Proporcionado por el usuario]`, `[Inferencia lógica]`, `[Incógnita crítica]` y `[Umbral experimental]`. Se puede pedir una respuesta breve, pero no desactivar las protecciones para riesgos altos.
