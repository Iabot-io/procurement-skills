---
name: supplier-onboarding-checklist
description: Preparar altas de proveedores con verificación documental y excepciones visibles. En IAbot.io, asígnala a un empleado de administración de compras y aporta política de alta, documentos y datos aportados por el proveedor.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Compras y proveedores
---

# Expediente de alta de proveedores

## Uso en IAbot.io

Asigna esta skill a **un empleado de administración de compras** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta política de alta, documentos y datos aportados por el proveedor.

**Ejemplo de encargo:** «Revisa este expediente de proveedor y prepara los campos validados y pendientes para el alta.»

**Resultado a revisar:** Checklist de alta y propuesta de datos maestros.

## Cuándo usarla y qué necesita

Preparar altas de proveedores con verificación documental y excepciones visibles

Trabaja con política de alta, documentos y datos aportados por el proveedor. Usa documentos y datos autorizados del ERP o de proveedores. Las compras, cambios contractuales y comunicaciones vinculantes conservan su circuito de aprobación.

## Procedimiento

1. Identifica entidad y servicio y extrae los requisitos realmente aplicables de la política.
2. Contrasta denominación e identificadores entre documentos sin investigar datos personales innecesarios.
3. Revisa vigencias y datos bancarios mediante el procedimiento seguro establecido, sin aceptar un correo como cambio suficiente.
4. Prepara datos maestros con fuente por campo y excepciones que requieren revisión.
5. Entrega el expediente sin activar proveedor o modificar pagos automáticamente.

## Comprobación del resultado

- Los datos bancarios siguen una verificación independiente autorizada.
- Las vigencias pertenecen al proveedor y servicio correctos.
- Alta propuesta y alta ejecutada permanecen diferenciadas.

## Entrega

Checklist de alta y propuesta de datos maestros.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Información europea para empresas](https://europa.eu/youreurope/business/index_es.htm)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
