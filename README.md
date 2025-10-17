# Dashboard de Ventas — Excel (Proyecto 1)
**Rol:** Data/BI Analyst · **Herramientas:** Excel (Tablas, Pivots, Slicers, Gráficos)

## Problema
Monitorear ingresos, margen, ticket y mix por canal/producto para decisiones comerciales.

## Dataset
Sintético (~5.000 filas) generado para demostración.
Columnas: fecha, canal, región/ciudad, categoría, producto, unidades, precio, descuento, revenue, costo, margen, medio de pago.

## Proceso
- Tabla **Sales** limpia para pivots.
- Pivots:
  - Ventas por Mes (tendencia)
  - Top Productos (ranking)
  - Canal × Segmento (mix)
- Slicers: channel, region, product_category, payment_method
- KPIs: Revenue, Orders únicos, Units, Avg Ticket, Margin %

## Capturas
![Overview](images/Captura de pantalla 2025-10-16 201113.png)
![Ventas por Mes](Captura de pantalla 2025-10-16 201151.png)
![Top Productos](Captura de pantalla 2025-10-16 201314.png)
![Canal × Segmento](Captura de pantalla 2025-10-16 201400.png)

## Entregables
- [`/data/proyecto1_ventas_retail.csv`](data/proyecto1_ventas_retail.csv)
- [`/excel/proyecto1_excel_ventas.xlsx`](excel/proyecto1_excel_ventas.xlsx)
- `/images/*.png`
