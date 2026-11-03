---
name: healthcare-roster-coverage
description: Comprobar un cuadrante frente a requisitos de cobertura y disponibilidad aportados. En IAbot.io, asígnala a un empleado de planificación administrativa y aporta cuadrante, perfiles habilitados y reglas de cobertura aprobadas.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Gestión sanitaria y sociosanitaria
---

# Revisar cobertura de turnos del centro

## Uso en IAbot.io

Asigna esta skill a **un empleado de planificación administrativa** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta cuadrante, perfiles habilitados y reglas de cobertura aprobadas.

**Ejemplo de encargo:** «Revisa el cuadrante y señala conflictos con los requisitos facilitados, sin asignar cualificaciones no confirmadas.»

**Resultado a revisar:** Matriz de cobertura por turno con conflictos y opciones de revisión.

## Cuándo usarla y qué necesita

Comprobar un cuadrante frente a requisitos de cobertura y disponibilidad aportados

Trabaja con cuadrante, perfiles habilitados y reglas de cobertura aprobadas. Usa exclusivamente datos y sistemas autorizados, con minimización de información personal. Los criterios clínicos, de urgencia y de dotación asistencial los fija el centro y sus profesionales.

## Procedimiento

1. Relaciona puestos y habilitaciones necesarias con los perfiles confirmados.
2. Comprueba disponibilidad, ausencias y solapes con el mínimo dato personal.
3. Contrasta cada turno con las reglas de cobertura facilitadas por el centro.
4. Prepara alternativas que respeten restricciones conocidas sin fijar ratios asistenciales por criterio propio.
5. Entrega la propuesta al responsable sin publicar ni cambiar el cuadrante real.

## Comprobación del resultado

- Las cualificaciones proceden de un registro autorizado.
- No se convierte disponibilidad supuesta en cobertura real.
- Las reglas laborales o asistenciales pendientes quedan identificadas.

## Entrega

Matriz de cobertura por turno con conflictos y opciones de revisión.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Ministerio de Sanidad](https://www.sanidad.gob.es/)
- [Agencia Española de Protección de Datos](https://www.aepd.es/)
