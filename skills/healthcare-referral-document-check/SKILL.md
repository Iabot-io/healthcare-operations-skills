---
name: healthcare-referral-document-check
description: Comprobar completitud administrativa de expedientes sin valorar pertinencia clínica. En IAbot.io, asígnala a un empleado de gestión documental sanitaria y aporta expediente autorizado y lista de documentos exigidos por el centro.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Gestión sanitaria y sociosanitaria
---

# Revisar documentación administrativa de derivaciones

## Uso en IAbot.io

Asigna esta skill a **un empleado de gestión documental sanitaria** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta expediente autorizado y lista de documentos exigidos por el centro.

**Ejemplo de encargo:** «Contrasta estos expedientes con la lista de documentos y devuelve únicamente los pendientes administrativos.»

**Resultado a revisar:** Lista de documentos presentes, ausentes y contradictorios por expediente.

## Cuándo usarla y qué necesita

Comprobar completitud administrativa de expedientes sin valorar pertinencia clínica

Trabaja con expediente autorizado y lista de documentos exigidos por el centro. Usa exclusivamente datos y sistemas autorizados, con minimización de información personal. Los criterios clínicos, de urgencia y de dotación asistencial los fija el centro y sus profesionales.

## Procedimiento

1. Identifica el expediente mediante un código y comprueba el alcance de acceso.
2. Relaciona documentos exigidos con los archivos aportados y sus fechas.
3. Señala ausencias, problemas de legibilidad e incoherencias de identificación sin copiar contenido clínico innecesario.
4. Prepara peticiones de subsanación administrativa para revisión del centro.
5. Conserva la decisión clínica y de aceptación de la derivación en el profesional correspondiente.

## Comprobación del resultado

- El informe contiene el mínimo dato identificativo necesario.
- No se decide idoneidad de pruebas o tratamientos.
- La ausencia de un documento no se confunde con ausencia de atención previa.

## Entrega

Lista de documentos presentes, ausentes y contradictorios por expediente.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Ministerio de Sanidad](https://www.sanidad.gob.es/)
- [Agencia Española de Protección de Datos](https://www.aepd.es/)
