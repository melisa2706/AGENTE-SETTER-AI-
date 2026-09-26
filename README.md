# Agente Setter IA — Instagram (MELYS AI)

Setter IA que atiende DMs de Instagram calificando leads y agendando llamadas con el closer,
hablando con el tono de la creadora.

## Contenido

- `docs/icp-hipotesis-v1-reinillonarias.md` — hipótesis de ICP (fundadoras de mentoría/consultoría
  premium en español, ticket US$3K+, venden por llamada con closer). A validar en entrevistas.
- `prompts/setter-instagram-v1.md` — system prompt del setter (5 bloques: rol y límites, producto,
  criterios de calificación, objeciones, cuándo escalar) + estados del lead + herramientas que
  puede ejecutar. Es un **template**: los `{PLACEHOLDER}` se completan por clienta.

## Estado del proyecto

Escalón: práctica. Falta antes de la primera demo real:

1. Elegir una clienta piloto (o cuenta propia) con Instagram profesional conectable.
2. Levantar el canal: app de Meta + webhook + primer mensaje de punta a punta.
3. Hacer el "voice mining" de esa clienta (ver sección final de `setter-instagram-v1.md`) y
   completar los placeholders del prompt con su tono, criterios y objeciones reales.
4. Conectar las herramientas (agenda real, CRM/planilla real) y probar contra conversaciones
   viejas reales antes de soltarlo con leads nuevos.

Ver el detalle de riesgos, permisos de Meta y arquitectura completa en la evaluación de la guía
técnica de referencia (setter IA vía Instagram Graph API).
