---
name: healthcare-consumables-stock
description: Preparar reposición de consumibles y detectar lotes o caducidades que requieren revisión. En IAbot.io, asígnala a un empleado de suministros del centro y aporta inventario, consumos, lotes, caducidades y política de reposición.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Gestión sanitaria y sociosanitaria
---

# Control de consumibles no farmacológicos

## Uso en IAbot.io

Asigna esta skill a **un empleado de suministros del centro** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta inventario, consumos, lotes, caducidades y política de reposición.

**Ejemplo de encargo:** «Revisa existencias de guantes y material de oficina clínica y prepara necesidades sin crear pedidos.»

**Resultado a revisar:** Relación de stock utilizable, vencimientos y reposición propuesta.

## Cuándo usarla y qué necesita

Preparar reposición de consumibles y detectar lotes o caducidades que requieren revisión

Trabaja con inventario, consumos, lotes, caducidades y política de reposición. Usa exclusivamente datos y sistemas autorizados, con minimización de información personal. Los criterios clínicos, de urgencia y de dotación asistencial los fija el centro y sus profesionales.

## Procedimiento

1. Identifica referencia, unidad, lote, ubicación y condiciones documentadas de almacenamiento.
2. Separa existencias disponibles, reservadas, bloqueadas y con caducidad próxima según la política.
3. Relaciona consumo y plazo de reposición con los niveles aprobados.
4. Prepara propuestas por referencia manteniendo lotes y equivalencias autorizadas.
5. Entrega alertas al responsable sin decidir sustituciones clínicas ni gestionar medicación.

## Comprobación del resultado

- No se incluye dosificación ni elección de medicamentos.
- Las unidades de envase y consumo se convierten con datos confirmados.
- Un lote bloqueado no se cuenta como utilizable.

## Entrega

Relación de stock utilizable, vencimientos y reposición propuesta.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Ministerio de Sanidad](https://www.sanidad.gob.es/)
- [Agencia Española de Protección de Datos](https://www.aepd.es/)
