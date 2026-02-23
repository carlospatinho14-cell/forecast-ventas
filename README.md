# Forecast de demanda (12 semanas) con percentiles P10/P50/P90

Este proyecto genera forecasts semanales (lun–sáb) por categoría usando Random Forest y features tipo lags/rolling.  
Además estima escenarios P10/P50/P90 a partir de las predicciones de los árboles del modelo.

## Requisitos
> Recomendado: ejecutar en un entorno virtual (venv).

```bash
pip install -r requirements.txt
Datos de entrada
Colocar un Excel llamado Ventas 2026.xlsx en la raíz del proyecto con estas columnas mínimas:

fecha (fecha de la venta)

Categoría (categoría del producto)

cantidad (unidades)

El dataset no se incluye en el repositorio por privacidad.


Después, en VS Code: **Ctrl + Shift + V** para ver el preview. Si se ve con títulos y bullets, ya quedó perfecto.
::contentReference[oaicite:0]{index=0}