## 1. Crear el virtualenv

```py
python3 -m venv .venv
```

o

```py
conda create -n mi_env python=3.12
```

## 2. Activar el virtualenv

```py
source .venv/Scripts/activate
```

o

```py
conda activate mi_env
```

### Si no se instalo notebook, instalarlo:
```py
pip install notebook
```

## 3. Levantamos un server Jupyter para poder trabajar:
```py
jupyter notebook --no-browser --port 8888
```
O
```py
python -m jupyterlab --no-browser --port 8888
```
