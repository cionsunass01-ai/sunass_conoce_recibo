# sunass_conoce_recibo

## Mi Recibo Claro

Mockup web estático para explicar, de manera referencial y en lenguaje sencillo, qué financia un recibo de saneamiento de SEDAPAR.

## Ejecutar

No requiere dependencias. Abra `index.html` en un navegador o sirva esta carpeta con su servidor estático preferido.

## Metodología inicial

La persona solo ingresa el monto por pagar. El mockup muestra el cargo fijo publicado de **S/ 3,71/mes** y considera, de manera didáctica, el resto como componente de consumo. También explica los tramos de referencia de un cliente doméstico de Arequipa Metropolitana.

Para CAPEX, se usa el **año 5** del estudio tarifario de SEDAPAR (periodo regulatorio 2021–2026): el **30,7 %** de los ingresos facturados por agua potable y alcantarillado, incluido el cargo fijo y sin IGV/IPM, se destina al Fondo de Inversiones. El mockup presenta ese porcentaje como CAPEX y el 69,3 % complementario como recursos para la operación del servicio.

No afirma que cada sol individual se contabilice de forma trazable ni que el complemento sea OPEX contable puro: es una explicación regulatoria y debe presentarse como estimación. Sin consumo en m³, categoría y localidad no se pueden identificar los tramos realmente facturados; por ello esta prueba de concepto no pretende recalcular un recibo oficial.

La POC ahora solicita empresa, distrito/localidad y la categoría que figura en el recibo. Con ello estima el consumo invirtiendo los tramos tarifarios y separa cargo fijo, consumo de agua y saneamiento e IGV/IPM. La categoría subsidiada **debe ser confirmada por la persona**: no se deriva del monto.

El portafolio muestra una selección verificable de proyectos de ampliación, reposición y otros, con su presupuesto total sin IGV. No se reparte un recibo individual entre proyectos porque los fondos regulatorios son comunes y la normativa no establece esa trazabilidad.

## Fuentes

- [Estudio Tarifario de SEDAPAR S. A. 2021–2026 (SUNASS)](https://www.gob.pe/institucion/sunass/informes-publicaciones/5872749-estudio-tarifario-de-sedapar-s-a): Fondo de Inversiones, p. 22; costos operativos, pp. 217–219; ingresos, p. 220.
- [RCD N.° 146-2025-SUNASS-CD](https://www.gob.pe/institucion/sunass/normas-legales/7549273-146-2025-sunass-cd): rebalanceo que modifica la estructura tarifaria aplicable al resto del periodo.
- [Estructura tarifaria de SEDAPAR](https://www.gob.pe/institucion/sedapar/informes-publicaciones/4878047-estructura-tarifaria): referencia de categorías y tarifas vigentes.
- [Estudio tarifario de SEDAPAL 2022–2027](https://www.gob.pe/institucion/sunass/informes-publicaciones/5872676-estudio-tarifario-de-la-empresa-sedapal-s-a): programa de inversiones, fondo y reservas.
- [RCD N.° 145-2025-SUNASS-CD](https://www.gob.pe/institucion/sunass/normas-legales/7549211-145-2025-sunass-cd): estructura tarifaria vigente de SEDAPAL.

## Pendiente antes de producción

1. Confirmar si el monto que ingresa la persona incluye IGV/IPM y separar la base regulada.
2. Validar con SUNASS/SEDAPAR la vigencia del porcentaje del fondo después del rebalanceo 2025.
3. Si se desea cálculo exacto en el futuro, solicitar consumo en m³, categoría, localidad y condición de subsidio.
