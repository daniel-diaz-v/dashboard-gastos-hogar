# 💡 Dashboard de Gastos del Hogar 2024-2026

Dashboard en Power BI para analizar mis gastos de luz, agua e internet durante 34 meses (ene 2024 - oct 2026), con datos reales de mis recibos.

## 🎯 Objetivo
Controlar y entender en qué categoría gasto más, cómo cambia mi gasto año a año y qué meses son los más caros.

## 🛠️ Herramientas
- **Excel:** digitación de recibos en tabla estructurada
- **SQLite (DB Browser):** importación, limpieza y consultas SQL
- **Power BI + DAX:** modelado, medidas y dashboard

## 🔄 Proceso
1. Digité los recibos de luz, agua e internet en Excel (Fecha, Categoría, Consumo, Unidad, Monto, Proveedor).
2. Importé el CSV a SQLite y creé la tabla limpia `gastos_final` (fechas AAAA-MM-DD, montos numéricos).
3. Conecté Power BI y creé medidas DAX (Variación %, Promedio Mensual, Mes Más Caro).
4. Diseñé 4 páginas: Resumen, Luz, Agua e Internet, con filtros de Año y Mes.

## 📊 Hallazgos
- Gasto total: **S/ 6,834.50** en 34 meses (promedio **S/ 201 al mes**).
- El mes más caro fue **enero 2024 (S/ 304)**.
- Luz representa el **43.9%** del gasto, internet el **42.2%** y agua el **13.9%**.
- El promedio mensual bajó **6.4%** frente al año previo.

## 🖼️ Capturas
![Resumen](img/01_resumen.png)
![Luz](img/02_luz.png)
![Agua](img/03_agua.png)
![Internet](img/04_internet.png)

## 📁 Archivos
- `data/`: datos originales
- `sql/`: base de datos SQLite y consultas
- `dashboard/`: archivo .pbix

## 👤 Autor
Daniel Díaz · Estudiante de Ing. de Sistemas (UCV) · [LinkedIn](https://www.linkedin.com/in/daniel-diaz-data)
