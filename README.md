# Gestión sanitaria y sociosanitaria · Skills para empleados IA de IAbot.io

Organización administrativa de centros sanitarios y de cuidados, sin diagnóstico ni decisiones clínicas.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Revisar capacidad administrativa de citas](skills/healthcare-appointment-capacity/SKILL.md) | un empleado de administración de citas | Informe de capacidad y conflictos con propuestas pendientes de validación. |
| [Revisar documentación administrativa de derivaciones](skills/healthcare-referral-document-check/SKILL.md) | un empleado de gestión documental sanitaria | Lista de documentos presentes, ausentes y contradictorios por expediente. |
| [Control de consumibles no farmacológicos](skills/healthcare-consumables-stock/SKILL.md) | un empleado de suministros del centro | Relación de stock utilizable, vencimientos y reposición propuesta. |
| [Instrucciones administrativas para usuarios del centro](skills/patient-administrative-instructions/SKILL.md) | un empleado de atención administrativa sanitaria | Guía administrativa con pasos, documentos y contactos confirmados. |
| [Registro administrativo de incidencias de calidad](skills/healthcare-quality-incident-register/SKILL.md) | un empleado de calidad del centro | Registro de incidencias, responsables y evidencias de seguimiento. |
| [Revisar cobertura de turnos del centro](skills/healthcare-roster-coverage/SKILL.md) | un empleado de planificación administrativa | Matriz de cobertura por turno con conflictos y opciones de revisión. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/healthcare-operations-skills --list
npx skills add Iabot-io/healthcare-operations-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Revisar capacidad administrativa de citas:** «Revisa estas agendas anonimizadas y prepara alternativas para los conflictos, sin priorizar pacientes por síntomas.»
- **Revisar documentación administrativa de derivaciones:** «Contrasta estos expedientes con la lista de documentos y devuelve únicamente los pendientes administrativos.»
- **Control de consumibles no farmacológicos:** «Revisa existencias de guantes y material de oficina clínica y prepara necesidades sin crear pedidos.»

## Herramientas y límites

Usa exclusivamente datos y sistemas autorizados, con minimización de información personal. Los criterios clínicos, de urgencia y de dotación asistencial los fija el centro y sus profesionales.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Ministerio de Sanidad](https://www.sanidad.gob.es/)
- [Agencia Española de Protección de Datos](https://www.aepd.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
