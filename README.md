# python-cruce-archivo-domiciliar

# Cruce para archivo de Domiciliar

Script en Python para realizar cruces entre bases de datos en Excel y obtener coincidencias por negocio y agente.

## Archivos

* Script principal: realiza el cruce entre dos bases
* BaseAyR.xlsx: información principal
* BaseNegocios.xlsx: catálogo de negocios

## Uso

1. Configurar rutas en el script:

```python id="conf2"
INPUT_FILE_1 = "C:\\Ruta\\BaseAyR.xlsx"
INPUT_FILE_2 = "C:\\Ruta\\BaseNegocios.xlsx"
OUTPUT_FILE = "C:\\Ruta\\Resultado.xlsx"
```

2. Ejecutar:

```bash id="run2"
python script_CruceDomi.py
```

## Funcionalidad

* Lectura de archivos Excel
* Filtrado de registros inválidos (DEFAULT)
* Cruce por múltiples campos
* Limpieza de resultados sin coincidencia
* Exportación a Excel

## Requisitos

```bash id="req2"
pip install pandas openpyxl
```

## Notas

* Las columnas deben coincidir entre archivos
* Ajustar nombres de columnas si cambia la estructura
* No incluir datos sensibles
