### Introducción

Versión parchada de [Mediapipe](https://github.com/google/mediapipe) que incorpora la solución IRIS al paquete ```mediapipe``` de Python.

### Uso

Después de compilar Mediapipe siguiendo [estas instrucciones](https://google.github.io/mediapipe/getting_started/python#building-mediapipe-python-package), la API se puede usar así:

```python
import mediapipe as mp
mp_iris = mp.solutions.iris
iris = mp_iris.Iris()
```
