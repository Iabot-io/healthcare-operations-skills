---
name: healthcare-quality-incident-register
description: Organizar incidencias de servicio sanitario con datos mínimos y seguimiento del circuito del centro. En IAbot.io, asígnala a un empleado de calidad del centro y aporta incidencias autorizadas, categorías y circuito de comunicación aprobado.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Gestión sanitaria y sociosanitaria
---

# Registro administrativo de incidencias de calidad

## Uso en IAbot.io

Asigna esta skill a **un empleado de calidad del centro** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta incidencias autorizadas, categorías y circuito de comunicación aprobado.

**Ejemplo de encargo:** «Prepara un registro anonimizado de estas incidencias de atención y señala las que requieren derivación inmediata según el protocolo.»

**Resultado a revisar:** Registro de incidencias, responsables y evidencias de seguimiento.

## Cuándo usarla y qué necesita

Organizar incidencias de servicio sanitario con datos mínimos y seguimiento del circuito del centro

Trabaja con incidencias autorizadas, categorías y circuito de comunicación aprobado. Usa exclusivamente datos y sistemas autorizados, con minimización de información personal. Los criterios clínicos, de urgencia y de dotación asistencial los fija el centro y sus profesionales.

## Procedimiento

1. Extrae hechos, fecha y área de servicio eliminando datos identificativos que no sean necesarios.
2. Aplica categorías del centro y conserva casos que no encajan para revisión.
3. Separa hechos comunicados, comprobados y acciones realizadas.
4. Deriva por el circuito indicado los casos de seguridad clínica o privacidad, sin investigar fuera del acceso concedido.
5. Define evidencia de respuesta y cierre administrativo para cada incidencia.

## Comprobación del resultado

- La agregación no permite identificar a personas innecesariamente.
- No se decide causalidad o gravedad clínica automáticamente.
- Los cierres mantienen el responsable y la evidencia.

## Entrega

Registro de incidencias, responsables y evidencias de seguimiento.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Ministerio de Sanidad](https://www.sanidad.gob.es/)
- [Agencia Española de Protección de Datos](https://www.aepd.es/)
