---
name: supplier-offer-comparison
description: Comparar ofertas por coste total, cumplimiento y riesgo documentado. En IAbot.io, asígnala a un empleado de análisis de compras y aporta ofertas completas, requisitos, criterios y pesos aprobados.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Compras y proveedores
---

# Comparativa de ofertas de proveedores

## Uso en IAbot.io

Asigna esta skill a **un empleado de análisis de compras** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta ofertas completas, requisitos, criterios y pesos aprobados.

**Ejemplo de encargo:** «Compara estas ofertas con los criterios indicados y muestra cómo cambia la preferencia si varían los pesos.»

**Resultado a revisar:** Matriz comparativa con evidencias, exclusiones y sensibilidad.

## Cuándo usarla y qué necesita

Comparar ofertas por coste total, cumplimiento y riesgo documentado

Trabaja con ofertas completas, requisitos, criterios y pesos aprobados. Usa documentos y datos autorizados del ERP o de proveedores. Las compras, cambios contractuales y comunicaciones vinculantes conservan su circuito de aprobación.

## Procedimiento

1. Normaliza alcance, cantidades, moneda, impuestos y horizonte de coste de cada oferta.
2. Relaciona requisitos con evidencias y separa incumplimiento de falta de información.
3. Calcula coste total comparable incluyendo conceptos documentados de entrega, mantenimiento o uso. Respeta mínimos y múltiplos de compra: un coste proporcional de diez unidades no representa una oferta que exige comprar veinte.
4. Aplica puntuaciones solo con criterios y pesos visibles; muestra las compensaciones relevantes. Si faltan pesos, conserva una comparativa factual y no inventes una puntuación para elegir ganador.
5. Entrega opciones y aclaraciones pendientes sin adjudicar ni emitir pedidos.

## Comprobación del resultado

- No se comparan costes de alcances diferentes sin ajuste explícito.
- Los pesos suman la base acordada y las fórmulas son reproducibles.
- Una ausencia de evidencia no se puntúa como cumplimiento.

## Entrega

Matriz comparativa con evidencias, exclusiones y sensibilidad.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Información europea para empresas](https://europa.eu/youreurope/business/index_es.htm)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
