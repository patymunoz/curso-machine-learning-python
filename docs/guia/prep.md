# II. Preparación de herramientas y entorno de trabajo

Antes de adentrarnos en los contenidos del curso, es fundamental configurar correctamente el entorno en el que trabajaremos. Esto asegurará que todas y todos podamos seguir los ejemplos de manera práctica y sin complicaciones.

## A) Jupyter Notebook

El Jupyter Notebook es un entorno interactivo que permite escribir y ejecutar código directamente en el navegador.

- Es ampliamente utilizado por científicos de datos y desarrolladores para el análisis exploratorio de datos.

- Facilita la combinación de código, texto, imágenes y visualizaciones, lo que lo convierte en una herramienta ideal para aprender y documentar proyectos de Machine Learning.

## B) Bibliotecas necesarias

Durante el curso utilizaremos las siguientes bibliotecas de Python:

- [Scikit-learn](https://scikit-learn.org/stable/) → Biblioteca principal de Machine Learning.
- [Pandas](https://pandas.pydata.org/) → Manipulación y análisis de datos.
- [NumPy](https://numpy.org/) → Cálculo numérico y manejo de arreglos.
- [Matplotlib](https://matplotlib.org/) → Visualización de datos en gráficos básicos.
- [Seaborn](https://seaborn.pydata.org/) → Visualización de datos estadísticos con gráficos más elaborados.

## C) Entorno de trabajo: Google Colab

Google Colab nos permitirá trabajar en notebooks de Python sin necesidad de instalar nada en la computadora.

### 1. Crear una cuenta de Google

Para utilizar Google Colab, es necesario contar con una cuenta de Google. Si aún no tienes una, puedes crearla de forma gratuita siguiendo estos pasos:

1. Ve a la página de [creación de cuentas de Google](https://accounts.google.com/signup).
2. Completa el formulario con tu información personal.
3. Acepta los términos y condiciones.
4. Haz clic en "Crear cuenta".

Una vez que tengas tu cuenta de Google, podrás acceder a Google Colab y comenzar a trabajar en tus proyectos de Machine Learning.

### 2. Acceder a Google Colab

Google Colab es una plataforma en línea que permite escribir y ejecutar código Python en un entorno de cuadernos (notebooks). Para acceder a Google Colab, sigue estos pasos:

1. Abre tu navegador web y ve a la página de [Google Colab](https://colab.research.google.com/).
2. Inicia sesión con tu cuenta de Google si aún no lo has hecho.
3. Una vez dentro, puedes crear un nuevo cuaderno haciendo clic en "Archivo" > "Nuevo cuaderno".
4. También puedes abrir cuadernos existentes desde tu Google Drive o desde GitHub.

### 3. Familiarizarse con la interfaz de Google Colab

La interfaz de Google Colab es bastante intuitiva, pero aquí hay algunos elementos clave que debes conocer:

- **Celdas de código**: Son bloques donde puedes escribir y ejecutar código Python. Puedes agregar nuevas celdas haciendo clic en el botón "+" en la barra de herramientas.

- **Celdas de texto**: Son bloques donde puedes escribir texto en formato Markdown para documentar tu código. Puedes agregar nuevas celdas de texto haciendo clic en el botón "+" y seleccionando "Texto".

- **Barra de herramientas**: Contiene botones para ejecutar celdas, guardar el cuaderno, agregar celdas, entre otras funciones.

- **Entorno de ejecución**: Puedes seleccionar el tipo de entorno de ejecución (CPU, GPU, TPU) desde el menú "Entorno de ejecución" > "Cambiar tipo de entorno de ejecución".

### 4. Instalar bibliotecas necesarias

En Google Colab, muchas bibliotecas populares ya están preinstaladas. Sin embargo, es posible que necesites instalar algunas adicionales para tus proyectos de Machine Learning. Puedes hacerlo utilizando el comando `!pip install` en una celda de código. Por ejemplo:

```python
!pip install pandas numpy scikit-learn matplotlib seaborn
```

Asegúrate de ejecutar esta celda para instalar las bibliotecas necesarias antes de comenzar a trabajar en tus proyectos.

### 5. Guardar y compartir tu trabajo

Google Colab guarda automáticamente tu trabajo en tu Google Drive, pero también puedes descargar el cuaderno en formato `.ipynb` o `.py` haciendo clic en "Archivo" > "Descargar". Además, puedes compartir tu cuaderno con otras personas usuarias haciendo clic en el botón "Compartir" en la esquina superior derecha y configurando los permisos de acceso.

Con estos pasos, estarás list@ para comenzar a trabajar en proyectos de _Machine Learning_ utilizando Google Colab.
