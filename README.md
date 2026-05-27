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
uv pip install pandas networkx scikit-learn ipykernel
```

## Ejecutar el notebook

1) Abre `clasificacion__Twitch.ipynb` en VS Code.
2) Selecciona el kernel del entorno `.venv`.
3) Ejecuta las celdas.
