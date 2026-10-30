# Revisión de etiqueta NOM-051 / NOM-050 por SKU

Revisa por SKU la etiqueta de alimentos y productos preenvasados contra la NOM-051-SCFI/SSA1-2010 (sellos frontales, leyendas precautorias y fechas de fase vigentes, incluido el Acuerdo DOF 2025-07-31) y, para productos no alimenticios sin NOM propia, la NOM-050-SCFI-2004. Calcula qué sellos le tocan a cada producto a partir de su tabla nutrimental, compara versiones del arte de la etiqueta y arma el expediente de evidencia para tu especialista o unidad de inspección. Precio previsto del paquete empresarial: **USD 20**. Es un paquete de instrucciones para un asistente de IA; no incluye los textos oficiales de las normas, laboratorio ni trámites ante la autoridad.

Su valor está en ordenar la revisión: qué debe declarar cada SKU, qué cambió entre dos artes, qué queda sin comprobar y qué evidencia hay que juntar. No promete certificación, Contraseña Oficial ni aceptación de la autoridad.

## Cómo usarlo

1. Copia **toda esta carpeta** (con `skills/`, `references/`, `ejemplos/` y `LICENSE`) y dile a tu asistente de IA que siga `skills/revision-etiqueta-nom051/SKILL.md`. No copies solo SKILL.md: perderías las fuentes y los ejemplos. No hay que instalar, configurar ni editar nada.
2. Adjunta por cada SKU: arte o foto de la etiqueta (cara frontal y panel nutrimental), tabla nutrimental o ingredientes si las tienes, fecha prevista de impresión y, si comparas versiones, ambas versiones completas. No compartas fórmulas propietarias ni datos personales.
3. Pide el checklist por SKU, la tabla de sellos con operación visible, la comparación de versiones y el expediente para el especialista; revísalo antes de usarlo. El paquete no imprime, no manda mensajes ni presenta trámites.

*Nota para plataformas que solo instalan la carpeta de la skill:* pon una copia de `references/` y `ejemplos/` junto a `SKILL.md`; el asistente los encontrará igual. El asistente debe poder leer Markdown; consultar fuentes oficiales nuevas requiere internet.

Solicitud sugerida:

> Usa revision-etiqueta-nom051 para revisar estos SKU antes de mandar el arte a imprenta. Para cada uno dime qué debe declarar según la fase vigente a mi fecha de impresión, qué sellos y leyendas le tocan según la tabla nutrimental (calculando con los umbrales de fase 2 del paquete y mostrando la operación), qué cambió entre las versiones del arte y qué evidencia falta para el especialista. Lo que caiga fuera de esos umbrales, contrástalo con el texto oficial o márcalo como no verificable.

## Qué recibes

- Checklist por SKU con lo que debe declarar (NOM-051 numeral 4.2 y sellos; NOM-050 solo en no alimenticios), evidencia y regla con fuente y fecha.
- Tabla de sellos y leyendas con la operación visible: valor declarado, base, umbral de la fase vigente (los de fase 2 vienen incluidos en el paquete) y resultado.
- Comparación de versiones del arte que separa cambios normativos de cosméticos.
- Expediente para el especialista: pendientes con responsable propuesto y el límite explícito de la revisión.

El [ejemplo de Andén Norte](ejemplos/entrada-skus-anden-norte.md) usa solo datos **ficticios**. Su [salida esperada](ejemplos/salida-esperada.md) se puede seguir a mano, sin ejecutar programas: muestra sellos quitados sin justificación, un sello EXCESO CALORÍAS que ni la v1 traía, una leyenda de edulcorantes faltante, una tabla nutrimental incompleta, un país de origen faltante y un personaje infantil que ya incumplía en v1, y el cálculo de cada sello con la operación visible usando los umbrales de fase 2 del paquete.

## Fuentes y límites

Las referencias del paquete traen las **fechas de fase vigentes** (fase 2 del 2023-10-01 al 2027-12-31 y fase 3 desde 2028-01-01, por el Acuerdo DOF 2025-07-31 que sustituyó al del 2025-05-09), los sellos y leyendas por fase, y los **umbrales numéricos de la fase 2** (Tabla 6 de la Modificación, DOF 2020-03-27). La skill calcula con esos umbrales mostrando la operación y marca NO VERIFICABLE lo que caiga fuera de ellos y no se pueda confirmar en el texto oficial. Las URL (permalinks de dof.gob.mx), fechas de consulta (2026-10-29) y reglas de integridad están en [references/fuentes.md](references/fuentes.md). Los documentos oficiales se atribuyen al DOF y a la Secretaría de Economía; no se presentan como obra propia.

No incluye los textos íntegros de las normas, catálogos de unidades de inspección, laboratorios, ni la regulación de categorías con norma propia (lácteos, cárnicos, bebidas alcohólicas, cosméticos, suplementos). No sustituye a la unidad de verificación o inspección acreditada, al laboratorio, a la autoridad sanitaria ni al especialista legal: **pre-revisa, cruza y arma evidencia**.

## Estado de esta entrega

Revisada y cerrada por cuatro IA de frontera por separado sobre esta versión. Página: https://heroldo.org/skills/revision-etiqueta-nom051/ · a la venta en [Agensi](https://agensi.io/skills/revision-etiqueta-nom051).

## Licencia

**Propiedad intelectual de Heroldo Escobedo**, con el código a la vista ([Licencia de uso de Heroldo 1.0](LICENSE)):

- **Uso personal: gratis.** Léelo, pruébalo y adáptalo para aprender o en tus propios datos.
- **Uso en una empresa o con fines de lucro: solo con compra.** Cómpralo en [Agensi](https://agensi.io/skills/revision-etiqueta-nom051)
  o escribe a heroldo@lolo-enterprises.com. La compra cubre a tu empresa.
- **Siempre se cita la fuente:** «Basado en una skill de Heroldo Escobedo — heroldo.org».
- No se revende ni se vuelve a publicar.

> **In English:** Source-available, not open source. Free for personal use. Business use requires purchase on
> [Agensi](https://agensi.io/skills/revision-etiqueta-nom051). Attribution to Heroldo Escobedo — heroldo.org is always required.
