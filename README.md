# Matriz Productividad vs Seguridad — Google Sheets (GViz/JSONP)

App web estática para generar una matriz 2×2 (Productividad vs Seguridad) por **SIGLA**, leyendo dos hojas del **mismo Google Sheet**:
- `Base_Producciones` (campos: MES, SIGLA, N° GUIAS, DIAS TRABAJADOS)
- `Base_Precursores` (campos: MES, SIGLA, TIPOS, # EVENTOS)

## Instrucciones
1. Comparte el Google Sheet como **“Cualquiera con el enlace → Lector”**.
2. Verifica que las pestañas se llamen exactamente **Base_Producciones** y **Base_Precursores**.
3. Abre `index.html` y actualiza el `SHEET_ID` si usas otro documento.
4. Sube estos archivos a un repo de GitHub y activa **GitHub Pages** (Settings → Pages → Deploy from branch → main → /root).

## Uso
- Click en **“Cargar desde Google Sheets”**.
- Selecciona meses (chips), ajusta **Pesos** y **Umbrales** si quieres.
- Click en **“Generar”** para ver KPIs, gráfico y tabla.
- **Exportar CSV** para descargar la tabla.
