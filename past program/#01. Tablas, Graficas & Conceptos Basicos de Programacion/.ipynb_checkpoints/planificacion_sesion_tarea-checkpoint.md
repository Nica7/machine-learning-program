# Planificacion

# Sesion

**Duración Estimada:**

- **Sesión:** `90 minutos`
- **Tarea:** `60 minutos`
- **Corrección:** `60 minutos`

## Definir una variable

> Asignar un `objeto` (numero, letras) a una `variable`.

## El Registro

> Lugar donde Python va a buscar las palabras que escribimos.

## Uso de Funciones

### Funciones Predefinidas en Python (_Built-in_ Functions)

> https://docs.python.org/3/library/functions.html

### La Disciplina. Necesidad & Solución

> Aplicar la siguiente lógica cuando **busques soluciones en Internet**:
>
> 1. **Necesidad**: ¿Cómo hacer un gráfico de barras?
> 2. **Solución**: ¿Cuál es la `función()` que me hace un gráfico de barras?
>
> De todas las letras que pueden haber en una página web, nosotros nos centraremos en **detectar paréntesis `()`** porque nos indican la presencia de una función.-

### Funciones Externas

> Descarga [estos datos](https://raw.githubusercontent.com/jesusloplar/data/main/uso_internet_espana.csv).
> Aplica la disciplina para buscar ayuda en Internet.

### Elementos de la Programación

> - `Librería`: donde se encuentran las funciones.
>   - `Función`: recurso de la programación para repetir un proceso con **menos líneas de código**.
>   - `Parámetro`: se usa para **configurar** el proceso de la función.
>     - `Objeto`: **estructuras de datos** donde se almacena la información que vamos procesando. Diferentes tipos de objetos:
>       - `Listas`
>       - `Series`
>       - `DataFrame`-

### Sintaxis

**¿Qué sucede al Ejecutar una Función?**

> ¿En qué orden lee Python el código?
> - De izquierda a derecha.
> - De arriba abajo.
> ¿Qué orden sigue el código anterior?
> ¿Cuáles son los elementos de la programación que se usan?

### Funciones dentro de Objetos

> - El `perro` que `ladra()`: `perro.ladra()`
> - El `gato` que `maulla()`: `gato.maulla()`
> - El `DataFrame` que `mean()`: `DataFrame.mean()`

## Acceder a `Objetos`

> Los objetos son **estructuras de datos** que contienen información. 
> ¿Qué `sintaxis` usamos para acceder a ellos?-

### Notación de Puntos `.`

+

### Corchetes `[]`

+

## Manipulación de Tablas con `DataFrames`

> ¿Qué podemos hacer con el objeto `DataFrame`?-

### Contar número de personas que hay en cada categoría de estudio

+

### Edad media de los que usan internet y los que no usan internet

+

### Edad media de los que usan internet y los que no usan internet según el sexo

+

## Visualización Datos en Python

### Cargamos otros Datos

> Cargamos este [archivo csv](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv).
> ¿Qué significa `csv`?
> ¿Por qué no usar un `Excel` donde se ve todo más claro?

### Scatterplot

#### Con `Matplotlib`

> Scatterplot

#### Con `Seaborn`

> Scatterplot

#### Con `Plotly`

> Scatterplot

### Otros Tipos de Gráficas

#### Histogramas

+

#### Boxplot

+

#### Barras

+

#### Pie

+

#### Mapas

+

# Tarea

## Cargar Datos

> Si ejecutamos los siguientes comandos:

```python
import seaborn as sns
sns.get_dataset_names()
```

> Veremos una lista de posibles `datasets` que podemos descargar desde internet y convertirlos directamente a un `DataFrame` de `pandas`. Por ejemplo:

```python
sns.load_dataset(name='mpg')
```

## Scatterplot con 2 Variables

> - Variable en Eje X
> - Variable en Eje Y

## Scatterplot con 3 variables

> - Variable en Eje X
> - Variable en Eje Y
> - Variable en Color de los Puntos

## Otras Gráficas

> Ahora vamos a ir a las galerías de las 3 librerías que más se usan en la actualidad para visualizar datos en Python.
>
> Vamos a reproducir un ejemplo como mínimo de cada librería. Por tanto, en cada apartado:
>
> 1. Visiar la página web
> 2. Seleccionar un ejemplo
> 3. Copiar y pegar código
> 4. Ejecutar-

### Seaborn Example Gallery

> - https://seaborn.pydata.org/examples/index.html

### Matplotlib Example Gallery

> - https://matplotlib.org/stable/gallery/index.html

### Plotly Example Gallery

> - https://plotly.com/python/

## Repetir Estilo de Gráficas Anteriores con tus Datos

> Resulta muy fácil copiar y pegar. Sin embargo, debemos empezar a **copiar y pegar con criterio**: sabiendo qué copiar y donde pegarlo. Entonces:
>
> - Trataremos de emular cada una de las gráficas del apartado anterior con la tabla de datos que cargamos en el primer apartado de la tarea.-

### Seaborn

+

### Matplotlib

+

### Plotly

+

## Objetivos Alcanzados

_Haz doble click sobre esta celda y pon una `X` dentro de las casillas [X] si crees que has superado los objetivos:_

- [ ] Identificar los **Elementos de la Programación** gracias a la sintaxis.
- [ ] Usar `funciones` que están contenidas en `librerías`.
- [ ] Hacer que _la máquina trabaje para ti. No contra ti_. Existen trucos para ir **pidiéndole ayuda al ordenador** sin tener que buscar cosas en Internet o mirar tutoriales...
- [ ] Entender que un `perro` NO `maulla()`. Sino que `ladra()`... de la misma manera que un `DataFrame` no `vuela()`.
- [ ] Todos los caminos llevan a Roma. Entender que podemos obtener el **mismo resultado con diferentes líneas de código**.
- [ ] **`Librerías` diferentes** que contienen `funciones` que hacen prácticamente **lo mismo**.
- [ ] Entender que **el código es una cuestión de necesidad**. No una serie mecánica de pasos a seguir.
- [ ] Entender que **no existe una solución única**. Sino que pueden ser diferentes e igualmente válidas (siempre y cuando se entienda y se razone lo que se hace).-
