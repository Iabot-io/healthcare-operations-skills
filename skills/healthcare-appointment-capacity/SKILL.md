---
name: healthcare-appointment-capacity
description: Detectar conflictos y huecos de agenda con las reglas administrativas aprobadas. En IAbot.io, asígnala a un empleado de administración de citas y aporta agenda autorizada, duraciones, recursos y reglas del centro.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Gestión sanitaria y sociosanitaria
---

# Revisar capacidad administrativa de citas

## Uso en IAbot.io

Asigna esta skill a **un empleado de administración de citas** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta agenda autorizada, duraciones, recursos y reglas del centro.

**Ejemplo de encargo:** «Revisa estas agendas anonimizadas y prepara alternativas para los conflictos, sin priorizar pacientes por síntomas.»

**Resultado a revisar:** Informe de capacidad y conflictos con propuestas pendientes de validación.

## Cuándo usarla y qué necesita

Detectar conflictos y huecos de agenda con las reglas administrativas aprobadas

Trabaja con agenda autorizada, duraciones, recursos y reglas del centro. Usa exclusivamente datos y sistemas autorizados, con minimización de información personal. Los criterios clínicos, de urgencia y de dotación asistencial los fija el centro y sus profesionales.

## Procedimiento

1. Fija periodo, recurso, duración y estado de las citas con identificadores mínimos.
2. Comprueba solapes, tiempos de preparación y restricciones del centro.
3. Identifica huecos utilizables según reglas aportadas, sin convertir cancelaciones pendientes en disponibilidad confirmada.
4. Propón alternativas administrativas respetando recursos y preferencias registradas.
5. Entrega opciones sin modificar citas ni aplicar prioridades clínicas por cuenta propia.

## Comprobación del resultado

- No se infiere urgencia a partir de datos del paciente.
- Se evita mostrar información clínica innecesaria en el informe.
- Las alternativas cumplen las mismas reglas que las citas existentes.

## Entrega

Informe de capacidad y conflictos con propuestas pendientes de validación.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Ministerio de Sanidad](https://www.sanidad.gob.es/)
- [Agencia Española de Protección de Datos](https://www.aepd.es/)
