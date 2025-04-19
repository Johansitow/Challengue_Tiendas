# Proyecto Data Science - Análisis de Tiendas 📊

## Descripción
Este repositorio contiene un proyecto de Data Science desarrollado en Python (Colab) para analizar datos de cuatro tiendas en línea. Se realizan cinco evaluaciones clave por cada tienda:

1. **Análisis de facturación**: Suma total de ingresos (`valor_total`).
2. **Ventas por categoría**: Conteo de ventas agrupadas por categoría de producto.
3. **Calificación promedio**: Media de las valoraciones recibidas.
4. **Productos más y menos vendidos**: Identificación de los productos con mayor y menor número de ventas.
5. **Envío promedio**: Valor medio de costo de envío.

Además, se incluye un reporte automático dirigido al Señor Juan, indicando la tienda con menor facturación y una recomendación.

---

## Estructura del Proyecto

```text
├── README.md           # Documentación del proyecto
├── analiza_tiendas.ipynb  # Notebook de Colab con el código principal
└── data/               # Carpeta opcional para datos locales (no incluida)
```

- **analiza_tiendas.ipynb**: Notebook de Google Colab con los bloques de código ordenados:
  - Carga y concatenación de datos
  - Creación de la columna `valor_total`
  - Cálculo de facturación por tienda
  - Ventas por categoría por tienda
  - Calificación promedio por tienda
  - Productos más/menos vendidos por tienda
  - Envío promedio por tienda
  - Generación de un relatorio final

---

## Requisitos

- Python 3.7+  
- Librerías:
  - pandas

> **Nota**: El proyecto está pensado para ejecutarse en Google Colab, donde las librerías estándar ya están disponibles. Si trabajas localmente, instala:
>
> ```bash
> pip install pandas
> ```

---

## Uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Johansitow/Challengue_Tiendas.git
   cd Challengue_Tiendas
   ```
2. Abrir el notebook en Colab:
   - Sube el archivo `analiza_tiendas.ipynb` a Colab o usa la URL directa desde GitHub.
3. Ejecutar todas las celdas en orden.
4. Revisa la salida en cada bloque y el mensaje final del relatorio.



---

*Autor: Johan Steve Ospina Prieto — Proyecto Challenge1 Data Science Latam*

