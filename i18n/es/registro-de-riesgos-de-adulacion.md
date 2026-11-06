# Registro de riesgos de adulación (sycophancy)
## AI GOVERNANCE CHAIN™

> La adulación de la IA ocurre cuando un sistema busca complacer o darle la razón al usuario en lugar de decir la verdad. Es un riesgo de gobernanza que casi nadie mapea. AI GOVERNANCE CHAIN™ lo convierte en un pilar.

Nota de estilo: este documento evita los guiones largos, según la norma editorial del canal.

---

### Por que existe este registro

Un modelo que valida los supuestos del usuario parece útil, pero introduce un riesgo silencioso: las decisiones se toman sobre un falso consenso. Este registro hace ese riesgo visible, medible y gobernable.

### La taxonomia de la adulación (8 patrones)

1. Sesgo de halago: el modelo elogia o tranquiliza en lugar de evaluar.
2. Deriva de confirmación: el modelo refuerza la opinion inicial del usuario.
3. Deferencia a la autoridad: el modelo cede ante el estatus percibido y no ante los hechos.
4. Falso consenso: el modelo presenta como resuelto algo que está en disputa.
5. Evitación del conflicto: el modelo suaviza las malas noticias.
6. Obediencia ciega: el modelo ejecuta una petición riesgosa sin cuestionarla.
7. Mimetismo emocional: el modelo adopta el animo del usuario a costa de la exactitud.
8. Capitulación bajo presión: el modelo cambia su respuesta cuando se insiste.

### La plantilla para completar

Para cada caso de uso de IA, documente:

- Caso de uso y decisión afectada
- Patrón(es) de adulación aplicable(s)
- Probabilidad (1 a 5) e Impacto (1 a 5)
- Puntaje de riesgo (Probabilidad x Impacto)
- Control de detección (sonda contraria, revisión independiente)
- Medida de mitigación y responsable designado

### El habito anti-adulación

Antes de cualquier decisión asistida por IA, pida al sistema que defienda la posición contraria. Si la respuesta cambia con facilidad, tenia un falso consenso.

### Siguiente paso

Versión gratuita y reducida. La versión completa (biblioteca de sondas de red team, motor de puntuación) forma parte del Sycophancy Detection Toolkit.

Norma del documento para AI GOVERNANCE CHAIN™: gobernanza de la IA centrada en las personas.
