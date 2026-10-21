# SimpliQ ReportFlow · Demo 01

Demo de análisis y exportación de ventas con Streamlit. Datos de muestra 100% ficticios.

## Ejecutar en Windows

1. Instala Python 3.11 o 3.12.
2. Abre PowerShell dentro de esta carpeta.
3. Ejecuta:

```powershell
py -m pip install -r requirements.txt
py -m streamlit run app.py
```

## Publicar en Streamlit Community Cloud

1. Crea un repositorio NUEVO en GitHub, por ejemplo `simpliq-reportflow`, y sube el contenido de esta carpeta (incluyendo `data/ventas_demo.csv`, `.streamlit/config.toml`, `app.py`, `requirements.txt`). No reemplaces el repositorio `simpliq-web`.
2. En https://share.streamlit.io/ inicia sesión con GitHub y elige **Create app** / **Deploy a public app from GitHub**.
3. Selecciona el repositorio, rama `main` y archivo principal `app.py`.
4. Publica y prueba el enlace de la app con los datos ficticios.
5. Añade un botón «Probar demo» desde el portafolio de https://simpliq.mx que abra la URL de Streamlit.

## Avisos

- La app no usa base de datos ni persiste los archivos por diseño, pero los datos sí se procesan en servidores de Streamlit; NO subir información confidencial o personal real.
- Los despliegues públicos gratuitos pueden tener suspensión por inactividad y límites de recursos.
- Esta demo valida columnas y tipos esperados, pero no sustituye un sistema contable.
