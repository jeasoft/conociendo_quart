# Conociendo a Quart

#### Jearel Alcántara Febrier

- [@jeasoft](https://github.com/jeasoft) donde sea
- jeasoft@gmail.com

---

# ¿Qué es Quart?

- Microframework para desarrollo de aplicaciones web hecho en Python basado en [Asyncio](https://docs.python.org/3/library/asyncio.html).
- Enfocado en la sencillez al momento de desarrollo.
- Websockets son pasajeros de primer nivel.
- Su creador lo llama como la "Evolución de [Flask](http://flask.pocoo.org/)".

---

# ¿Y KLK con Quart?
- Python 3.6 como mínima versión
- [Jinja2](http://jinja.pocoo.org/docs/2.10/) como motor de templates.
- Se sube al camión de [ASGI (Asynchronous Server Gateway Interface)](https://github.com/django/asgiref/blob/master/specs/asgi.rst)
- [Hypercorn](https://pgjones.gitlab.io/hypercorn/) como web server recomendado.
-  [Secure Cookie Sessions](https://pgjones.gitlab.io/quart/session_storage.html).
- Soporte a WebSockets y a HTTP/2

---

# Evolución de Flask, ¿tu ta loco?
- Compatible con una cantidad X de extensiones de Flask [(Aquí)](https://pgjones.gitlab.io/quart/flask_extensions.html#supported-extensions).
- Guía para migrar apps de Flask a Quart [(Dale!)](https://pgjones.gitlab.io/quart/flask_migration.html).
- Blueprints (igualitico que en Flask) [(Que sí león!)](https://pgjones.gitlab.io/quart/blueprints.html).
- No lo dije yo, [lo dijo el](https://pgjones.gitlab.io/quart/flask_evolution.html).

---

# ¡¡Dame Código!!
- #ThuRehalHolaMundoh!:
Quart

```python
from quart import Quart

app = Quart(__name__)

@app.route('/')
async def hello():
    return 'Hola Pueblo!'

app.run()
```
---

# ¿Notan el parecido a Flask?
Chequea:

```python

from flask import Flask
app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello World!"

app.run()
```
---
# Documentación disponible
- [Web oficial](https://pgjones.gitlab.io/quart/index.html)
- [Repositorio de código oficial en gitlab](https://gitlab.com/pgjones/quart)
- [Mirror en Github](https://github.com/pgjones/quart)
- [HowTos!](https://pgjones.gitlab.io/quart/index.html#how-to-guides)
- Y porqué no, en la documentación de [Flask](http://flask.pocoo.org/docs/1.0/) (XD)
---

# ¿Preguntas?
---

# ¡Muchas Gracias!
### Mi sobrina dice:
![alt text](thanks.jpg)
[@jeasoft](https://github.com/jeasoft)
