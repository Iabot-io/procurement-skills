---
name: purchase-order-reconciliation
description: Conciliar compras por línea y detectar diferencias de cantidad, precio o recepción. En IAbot.io, asígnala a un empleado de control de compras y aporta pedidos, recepciones, facturas y tolerancias aprobadas.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Compras y proveedores
---

# Conciliar pedido, recepción y factura

## Uso en IAbot.io

Asigna esta skill a **un empleado de control de compras** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta pedidos, recepciones, facturas y tolerancias aprobadas.

**Ejemplo de encargo:** «Revisa estos pedidos contra recepciones y facturas y separa las diferencias que requieren aclaración.»

**Resultado a revisar:** Conciliación a tres documentos y registro de excepciones.

## Cuándo usarla y qué necesita

Conciliar compras por línea y detectar diferencias de cantidad, precio o recepción

Trabaja con pedidos, recepciones, facturas y tolerancias aprobadas. Usa documentos y datos autorizados del ERP o de proveedores. Las compras, cambios contractuales y comunicaciones vinculantes conservan su circuito de aprobación.

## Procedimiento

1. Relaciona líneas de pedido, recepción y factura por identificadores y referencias verificables.
2. Normaliza unidades y separa recepciones parciales, devoluciones y abonos.
3. Calcula diferencias de cantidad y precio frente al pedido y las tolerancias autorizadas.
4. Identifica facturación sin recepción, duplicados y servicios pendientes de aceptación.
5. Entrega excepciones y propuesta de revisión sin aprobar pagos ni modificar pedidos.

## Comprobación del resultado

- Una recepción parcial no se considera entrega total.
- Las facturas y abonos no se computan dos veces.
- Cada diferencia se localiza en sus tres documentos.

## Entrega

Conciliación a tres documentos y registro de excepciones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Información europea para empresas](https://europa.eu/youreurope/business/index_es.htm)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
