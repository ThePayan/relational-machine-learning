## Preparacion del entorno

Requisitos:
- Windows PowerShell
- Python 3.10+ (o que `uv` pueda descargarlo)
- `uv` instalado

Pasos (PowerShell):
1) Crear el entorno virtual:

```
uv venv .venv
```

2) Activar el entorno:

```
.\.venv\Scripts\activate
```

3) Instalar dependencias:

```
uv pip install pandas networkx scikit-learn ipykernel torch keras
```

## Notebooks

- `preparacion_datos_Twitch.ipynb`: limpieza y transformaciones iniciales; prepara los datasets para el modelado.
- `modelo_prediccion.ipynb`: entrenamiento y evaluacion del modelo usando los datos preparados.

## Ejecutar los notebooks

1) Abre `preparacion_datos_Twitch.ipynb` en VS Code.
2) Selecciona el kernel del entorno `.venv`.
3) Ejecuta las celdas.
4) Luego abre `modelo_prediccion.ipynb` y ejecuta sus celdas.
