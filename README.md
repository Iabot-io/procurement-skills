# Compras y proveedores · Skills para empleados IA de IAbot.io

Solicitudes, comparativas, homologación y seguimiento de compras con decisiones documentadas.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Preparar solicitudes de oferta](skills/supplier-rfq-preparation/SKILL.md) | un empleado de compras | Solicitud de oferta y plantilla de respuesta por proveedor. |
| [Comparativa de ofertas de proveedores](skills/supplier-offer-comparison/SKILL.md) | un empleado de análisis de compras | Matriz comparativa con evidencias, exclusiones y sensibilidad. |
| [Expediente de alta de proveedores](skills/supplier-onboarding-checklist/SKILL.md) | un empleado de administración de compras | Checklist de alta y propuesta de datos maestros. |
| [Conciliar pedido, recepción y factura](skills/purchase-order-reconciliation/SKILL.md) | un empleado de control de compras | Conciliación a tres documentos y registro de excepciones. |
| [Calendario de renovaciones de proveedores](skills/supplier-renewal-calendar/SKILL.md) | un empleado de gestión de contratos de compra | Calendario revisable de vencimientos, preavisos y decisiones de renovación. |
| [Preparar una negociación de compras](skills/procurement-negotiation-brief/SKILL.md) | un empleado de apoyo al responsable de compras | Brief de negociación y matriz de concesiones posibles. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/procurement-skills --list
npx skills add Iabot-io/procurement-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Preparar solicitudes de oferta:** «Prepara una solicitud de oferta que permita comparar precio, plazo, alcance y exclusiones de tres proveedores.»
- **Comparativa de ofertas de proveedores:** «Compara estas ofertas con los criterios indicados y muestra cómo cambia la preferencia si varían los pesos.»
- **Expediente de alta de proveedores:** «Revisa este expediente de proveedor y prepara los campos validados y pendientes para el alta.»

## Herramientas y límites

Usa documentos y datos autorizados del ERP o de proveedores. Las compras, cambios contractuales y comunicaciones vinculantes conservan su circuito de aprobación.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Información europea para empresas](https://europa.eu/youreurope/business/index_es.htm)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
