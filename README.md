# ejemplo-paquete-python

Paquete mínimo para probar la instalación directa desde este repositorio privado de GitHub.

## Instalación

Requiere que Git y una clave SSH autorizada para GitHub estén configurados:

```bash
python -m pip install "git+ssh://git@github.com/igalanji/python-package.git@main"
```

## Uso

```python
from ejemplo_paquete import saludar

print(saludar("Ana"))  # Hola, Ana!
```
