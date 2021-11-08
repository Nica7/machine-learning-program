# Planificacion

# Sesion

**Duración Estimada:**

- **Sesión:** `90 minutos`
- **Tarea:** `60 minutos`
- **Corrección:** `60 minutos`

## Machine Learning, qué significa?

> Por muy esotérico que suene, ¿qué significa en **español, literal**?

## Funciones Matemáticas

> ¿Qué representa una ecuación matemática?

## Cargar Datos

> Cargamos los datos de una tabla de accidentes de coches en Estados Unidos, `car_crashes`. En ella, cada fila representa un estado y cada columna características sobre cada estado en relación a los accidentes de tráfico.
>
> PD: Los datos están relativizados y las columnas de `alcohol, velocidad,...` nos dicen el % de accidentes donde dicha característica fue un motivo del siniestro.

```python
sns.load_dataset(name='mpg')
```

## Seleccionar Variables para el Modelo

> Comúnmente se conoce a esta temática de la Estadística como **Análisis Exploratorio de los Datos _(EDA)_**. El objetivo fundamental de este tópico es encontrar las variables que más se correlacionen y que den a entender un modelo de Regresión Lineal.
>
> No vamos a entrar mucho en detalle, de momento. Así que tan solo seleccionaremos variables que nos parezcan interesantes. Estas variables deberemos distinguirlas según su papel en el modelo:
>
> 1. Explicativas/Features/Input `X`
> 2. Objetivo/Class/Target `y`

## Visualizar Selección de Variables

> Las dos variables son numéricas. Por tanto, usaremos un **scatterplot** para visualizar la relación entre ellas.

## Modelo de Regresión Lineal en Python

### Entrenar Modelo

> 1. **Necesidad**: Entrenar Modelo
> 2. **Solución**: Función `fit()`

### Jerarquía de las Librerías

> 1. `Librería`
> 2. `Módulo1.Módulo2.`
> 3. `Función()` / `Objeto()`
>
> - **Si es Objeto**
>   - 3.1 `Función()`

### Ecuación Matemática del Modelo

> Los modelos no son más que ecuaciones matemáticas que nos ayudan a calcular algo. Por ejemplo:
>
> 1. La probabilidad de que un cliente deje de acudir a mi tienda.
> 2. La probabilidad de que un cliente del banco pueda afrontar un préstamo.
> 3. La probabilidad de que un atleta se lesione.
> 4. El número de bicicletas que se alquilarán hoy.

### Predicciones con el Modelo

> En nuestro caso, ¿cómo usamos la ecuación matemática para predecir el total de accidentes?

### Visualización del Modelo

> 1. Los **datos reales**.
> 2. **Modelo: las predicciones** con la ecuación matemática.

### Interpretación del Modelo

> ¿Qué **influencia tiene el alcohol** en el número de accidentes?

## Explicación Algoritmo Regresión Lineal

```python
%%HTML
<iframe width="560" height="315" src="https://www.youtube.com/embed/jEEJNz0RK4Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

## Cómo se ha Calculado el Modelo con el Código?

> ¿Qué sucede por dentro al ejecutar la función `.fit()`?

## ¿Cómo de Bueno es mi Modelo? **Bondad de Ajuste**

> Tan solo comparamos la predicción con la realidad.

## Otros Modelos de Regresión

### `RandomForestRegression()`

+

### `SVR()`

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

## Seleccionar 2 Variables para la Regresión

> - Variable Objetivo `y`
> - Variable Explicativa `X`

## Scatterplot con las Variables

> Deberíamos observar en la gráfica que los puntos podrían relacionarse a través de una línea que los cruce.
>
> Si no es así, debemos seleccionar otras variables.

## Modelo de Regresión Lineal `LinearRegression()`

### Entrenar Modelo

> 1. **Necesidad:** Entrenar Modelo
> 2. **Solución: Función** `fit()`

### Realizar Predicciones

> - `model.predict()`

## Visualizar Modelo

> 1. Los **datos reales**.
> 2. **Modelo: las predicciones** con la ecuación matemática.

## Interpretar Modelo

> 1. Especifica la **Fórmula Matemática** del Modelo.
> 2. **Interpreta los Coeficientes** de la Ecuación Matemática.

## Realidad vs Predicciones

> ¿Cómo de bueno es nuestro modelo?
>
> 1. Si pasamos las predicciones como una nuevo columna del `DataFrame`, podremos observar que **las predicciones de nuestro modelo pueden no coincidir con la realidad**.
>
>    - `df['pred'] = predicciones`
>
> 2. ¿Cómo medimos el **error de nuestro modelo**? ¿Cómo de bueno es nuestro modelo para describir la realidad?
>    - `df.sample(10)` para comprobar si las predicciones de nuestro modelo coinciden con la realidad...

## Objetivos Alcanzados

> Haz doble click sobre esta celda y pon una `X` dentro de las casillas [X] si crees que has superado los objetivos:

- [ ] Entender **cómo la máquina optimiza un modelo**, que no es más que encontrar **los números** una ecuación matemática.
- [ ] La `función` como elemento indivisible de la programación. Como un **átomo**: el núcleo de todo.
- [ ] Entender **qué sucede dentro del ordenador** cuando ejecutamos una función. Descargamos código de internet, o es un proceso local del ordenador?
- [ ] Usar **la programación como una herramienta**, como un medio hacia un fin. No como el fin en sí mismo.
- [ ] Entender que la estadística no es una ciencia perfecta. Sino que trata de **aproximarse a la realidad** de la mejor forma posible.
- [ ] **Medir el error** del modelo no es más que comparar la predicción contra la realidad.
- [ ] De la misma manera que en el código existen diversas formas de obtener el mismo resultado, en la programación existen **diversos algoritmos/modelos/ecuaciones para predecir la misma variable**.
