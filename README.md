# Clover-Club-2.0

**Esta parte es el back-end del proyecto**

## Iniciar el servidor
1. Crear el entorno virtual dentro de la carpeta correspondiente: python -m venv venv
2. Activar entorno virtual: ```venv\Scripts\activate``` **(Windows)** o source ```venv/bin/activate``` **(MAC / Linux)**
3. Correr el servidor (para cuando se quieran hacer pruebas o usarlo): ```uvicorn app.main:app --reload```

### Primeros pasos
Instala FastAPI y Uvicorn (el servidor para correr la aplicación):

```
  pip install fastapi uvicorn
```

Base de datos: SQL Sever.

**Importante** tener instalado el controlador ODBC adecuado para SQL Server en tu sistema.
Después de tener el controlador, instalar la librería en el proyecto
```
  pip install pyodbc
```
_Nota_ : Cambiar el código de conexión según corresponda la versión del ODBC
