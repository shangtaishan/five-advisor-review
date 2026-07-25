# Five-Advisor Review

**Idiomas:** [中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [Español](README.es.md)

Un Skill para someter ideas, propuestas, temas, decisiones y conceptos de negocio a una prueba de estrés con múltiples perspectivas.

No trata el acuerdo entre varios asesores como un hecho ni presenta cinco roles como cinco modelos independientes. El marco genera primero juicios iniciales aislados, después una revisión cruzada anónima y una prueba de estrés del consenso. Por último, la presidencia da una recomendación reversible con una acción de validación.

> El README en chino es la versión canónica. El README, la metodología, el diseño central y la guía de contribución se mantienen en chino, inglés, japonés, francés y español. Un cambio material debe actualizar los cinco documentos correspondientes en el mismo cambio.

## Qué resuelve

Muchas revisiones parecen tener varias perspectivas, pero repiten una misma ruta de razonamiento. Este proyecto separa cinco métodos:

1. **Refutador**: anticipa mecanismos probables de fracaso.
2. **Cuestionador de fundamentos**: descompone metas, causalidad y supuestos sin validar.
3. **Descubridor de oportunidades**: busca alternativas omitidas en contextos cercanos.
4. **Persona no experta**: pregunta por comprensión, confianza, precio y esfuerzo desde el sentido común.
5. **Ejecutor implacable**: identifica el primer bloqueo y lo convierte en una validación que puede completarse hoy.

El marco comprueba después si el consenso depende de un solo supuesto, expresa la objeción más fuerte y exige preservar los desacuerdos relevantes.

## Inicio rápido

1. Copie [`skill/`](skill/) en su directorio de Codex Skills, o impórtelo desde su entorno.
2. En una conversación:

   ```text
   Usa $five-advisor-review para revisar esta idea: …
   ```

3. Las ideas reversibles y de bajo coste usan el modo rápido. Las decisiones de riesgo medio/alto, irreversibles o con hechos críticos inciertos usan el modo completo con criterios de validación.

Las instrucciones completas están en [`skill/SKILL.md`](skill/SKILL.md), actualmente en chino.

## Principios centrales

- **El consenso no es evidencia.** La validación aumenta la credibilidad.
- **Haga explícitas las incógnitas.** No las sustituya por cifras que parezcan profesionales.
- **Un umbral experimental no es un estándar del sector.** Márquelo como `[Umbral experimental]` e indique su fin de control de riesgo.
- **No fabrique independencia.** Cinco perspectivas de un modelo son aislamiento procedimental, no evidencia de varios modelos.
- **Haga un movimiento reversible antes de apostar.** La primera acción en una decisión riesgosa debe validar o aislar el riesgo.

## Documentación

- [Metodología](docs/methodology.es.md)
- [Diseño central y límites de investigación](docs/core-design.es.md)
- [Guía de contribución](CONTRIBUTING.es.md)

## Licencia

Este proyecto se publica bajo la [licencia MIT](LICENSE). Puede estudiarlo, reutilizarlo, modificarlo y redistribuirlo.
