# III. Exploración y visualización de datos

La exploración y visualización de datos son pasos cruciales en el análisis de datos. Permiten comprender mejor la estructura, patrones y relaciones dentro del conjunto de datos.

## Objetivos

- Familiarizarse con técnicas de exploración de datos.
- Aprender a crear visualizaciones efectivas para comunicar hallazgos.
- Utilizar herramientas y bibliotecas como `Matplotlib`, `Seaborn` y `Plotly`.

## Temas

1. Importación de datos
2. Análisis exploratorio de datos (EDA)
3. Visualización de datos
4. Herramientas y bibliotecas para visualización

## Prerequisito para esta sesión

### Métodos vs atributos

🔹 Atributo

- Es **una variable asociada a un objeto**.
- Representa un **estado o característica** del objeto.
- Se accede sin paréntesis `()` porque no se "ejecuta".

**Ejemplo**

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre   # atributo
        self.edad = edad       # atributo

p = Persona("Ana", 25)
print(p.nombre)  # "Ana"
print(p.edad)    # 25
```

🔹 Método

- Es una función **definida dentro de una clase**.
- Representa un **comportamiento o acción** que puede realizar el objeto.
- Se llama con paréntesis `()` porque se ejecuta.

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):  # método
        return f"Hola, soy {self.nombre} y tengo {self.edad} años."

p = Persona("Ana", 25)
print(p.saludar())  # "Hola, soy Ana y tengo 25 años."
```

## Datos

Trabajaremos con el siguiente conjunto de datos:

[![Descargar datos](https://img.shields.io/badge/descargar-datos-blue)](../datos/iris_.csv)

## Contenidos de esta sesión

En esta sesión estaremos trabajando con este cuaderno de trabajo:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/patymunoz/curso-machine-learning-python/blob/main/docs/notebooks/exploracion-visualizacion.ipynb)
