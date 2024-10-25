# Fundamentos de Estadística y Probabilidad

## Estadística

La **estadística** en el análisis de datos es una rama de la matemática que se encarga de recolectar, analizar, interpretar y presentar datos. Su objetivo principal es identificar patrones, tendencias y relaciones dentro de los datos para tomar decisiones informadas.

En el contexto del análisis de datos, la estadística se divide en dos grandes áreas:

1. **Estadística descriptiva**: Se enfoca en resumir y describir las características principales de un conjunto de datos. Utiliza medidas como la media, la mediana, la moda, la desviación estándar, entre otras, para proporcionar una visión clara y concisa de los datos.

2. **Estadística inferencial**: Se utiliza para hacer predicciones o inferencias sobre una población a partir de una muestra de datos. Emplea técnicas como pruebas de hipótesis, intervalos de confianza y regresión para generalizar los resultados obtenidos de la muestra a toda la población.

La estadística es fundamental en el análisis de datos porque permite transformar grandes volúmenes de datos en información útil y accionable, facilitando la toma de decisiones basadas en evidencia.

## **Conceptos Clave**

### **Datos**

Los datos se leen mejor en tablas, entonces se procede a ordenar los datos en una tabla.

Los datos a estudiar son:

* Los individuos: que son los objetos de estudio.
* Las variables: que son las características que posee el objeto.

        Ejemplo:

        * Individuos → personas
        * Variables → altura (m)

> ![alt text](Imagenes/1.png)

### **Variables**

* **Variables cuantitativas (numéricas):**

    - Discretas: Pueden contarse y toman valores enteros (por ejemplo, el número de hijos).
    - Continuas: Pueden tomar cualquier valor dentro de un rango, incluyendo decimales (por ejemplo, la altura).

* **Variables cualitativas (categóricas):**

    - Nominales: No tienen un orden intrínseco (por ejemplo, el color de los ojos).
    - Ordinales: Tienen un orden o jerarquía (por ejemplo, las clasificaciones de satisfacción: baja, media, alta).

* **Niveles de medida:**
    - Nominal: Categorías sin orden (por ejemplo, tipos de frutas).
    - Ordinal: Categorías con un orden (por ejemplo, niveles de educación).
    - De intervalo: Tienen un orden y la diferencia entre valores es significativa, pero no tienen un cero absoluto (por ejemplo, la temperatura en grados Celsius).
    - De proporción: Tienen un orden, la diferencia entre valores es significativa y tienen un cero absoluto (por ejemplo, la altura, el peso).


            Ejemplo de variables cualitativas:

            * Individuos → 6 tipos de maletas.
            * Variable cuatitativa → Cantidad de maletas.
            * Variable cualitativa → El color de maleta y si tiene o no rueditas.

>![alt text](Imagenes/2.png)

        Ejemplo de niveles de medidas:

        Tenemos en el ejemplo:

        * 2 individuos → 2 departamentos
        * Variables → 19

>![alt text](Imagenes/3.png)

## **Software Estadístico**

* **Hojas de cálculo**: Son archivos que se componen por libros. Los libros se componen por hojas, y las hojas se componen de celdas ubicadas en filas y columnas. Se pueden insertar datos (numéricos, de texto, fórmulas y/o imágenes) para generar tablas o gráficos e interpretar los datos.
  * Excel
  * Google Sheets
  * Numbers

* **Industria Open Source**:
  * R → Creadas por y para estadísticos.
  * Python → Software de desarrollo con librerías que ayudan en el análisis de datos.

* **Herramientas de BI y análisis**: Facilitan la interpretación y analítica de datos. Crean dashboards interactivos o gráficos de tendencia para hacer reportes de negocio entendibles.
  * Power BI
  * Tableau
  * Minitab
  * Looker

* **Industria paga**: Las empresas temen por la seguridad de los datos, por lo que usan software de paga.
  * SPSS → Genera tendencias de datos y visualizaciones simples.
  * SAS → Lenguaje de programación con usos como análisis, visualización y generación de modelos de inteligencia artificial o machine learning.

* **Academia**:
  * Matlab → Preferido por físicos y matemáticos. Modela y calibra modelos, también genera animaciones.
  * Stata → Enfocado en el área médica y política.



 ## **Tablas Unidimensionales y Bidimensionales**

Para identificar si la tabla es unidimensional o bidimensional, debo responder a la pregunta: ¿Cuántas preguntas me tengo que hacer para identificar el valor que estoy buscando?

- Las **tablas unidimensionales** son aquellas en las que con una pregunta podemos identificar el valor que se está buscando.
- Las **tablas bidimensionales** son aquellas en las que con dos preguntas podemos identificar el valor que se está buscando.

**Frecuencia Estadística**: La frecuencia nos indica las veces en las que se repite un valor dentro de un conjunto de datos.

**Frecuencia relativa**: Nos indica el valor convertido en porcentaje del total.

### **Visualización**

**Diagramas de tallo**

 Una tabla de tallos y hojas se utiliza para mostrar datos. El 'tallo' a la izquierda muestra el primer dígito o dígitos, en este caso las decenas. La 'hoja' a la derecha muestra el último dígito, es decir, las unidades.

>![alt text](Imagenes/4.png)


**Gráfico de puntos**

Un diagrama de puntos muestra datos y sus frecuencias a lo largo de una recta numérica. Cada punto puede tomar el valor de una unidad o un valor representativo dentro de una escala.

**Gráfico de barras**

Un diagrama de barras es un gráfico usado para mostrar un grupo de datos repetidos (representa la frecuencia). Pueden tomar datos más grandes.

**Gráfico de barras horizontal**

Es recomendable usar el gráfico de barras horizontal si se quiere mostrar un orden específico, para mostrar los valores más representativos.

**Gráfico de pastel o circular (pie chart)**

Este diagrama también representa la frecuencia en un set de datos. Se puede tomar valores de la frecuencia total o frecuencia relativa.

**Gráfico de línea**

Los gráficos de líneas muestran puntos conectados mediante una línea. Es recomendable usar esta gráfica con muchos datos y que tienen lugar durante un período continuado de tiempo.

**Gráfico de ojiva**

Es similar al gráfico de línea, pero este representa acumulación respecto al tiempo.

>![alt text](Imagenes/5.png)


**Diagramas de Venn**

Nos ayudan a acomodar los datos respecto a cierta preferencia o pertenencia. Es importante para las preferencias combinadas.

**Histograma**

Agrupa intervalos de tamaño o valor similar. Se usan rangos.

>![alt text](Imagenes/6.png)

## **Estadística descriptiva**

La distribución conjunta es cómo se comporta una variable en relación a otra. Estas distribuciones son pensadas respecto a otra variable.

    Ejemplo: Entrevista a 100 individuos que tienen como hábito hacer ejercicio y se quiere relacionar las horas durmiendo respecto a los kilos perdidos en un mes.

    En la tabla conjunta bidimensional tenemos estas dos variables.

>![alt text](Imagenes/7.png)

**Distribución marginal**

Es la distribución que está a los márgenes de nuestra tabla bidimensional.

Independientemente de la otra variable, se pueden hacer conclusiones específicas de mi variable de columnas o de mi variable de filas.

    Ejemplo:

    Podemos observar la distribución marginal sumando los totales de las filas y columnas.

    Si se quiere enfocar la distribución marginal respecto a los kilos perdidos, solo se necesitaría la última fila de la tabla (total). Marginal por columnas - Distribución por kilos perdidos.

**Distribución condicional**

Dada una variable, ¿qué pasa con la otra variable? Se hacen preguntas sobre una variable respecto a la otra.

    Ejemplo:

    Distribución condicional por filas → Las filas suman el 100%.

    De las personas que durmieron entre 3-6 horas, ¿cuánto porcentaje perdió entre 2-4 kilos?

**Medidas de tendencia central**

Las medidas de tendencia central son estadísticas que proporcionan un valor representativo o central de un conjunto de datos. Las medidas más comunes de tendencia central son la media, la mediana y la moda.

* **Media (promedio)**: La media es la suma de todos los valores en un conjunto de datos dividida por el número total de elementos. Se denota como "μ" (mu) para una población o "x̄" (x barra) para una muestra.

**Fórmula**: 
$$\mu = \frac{x₁ + x₂ + \ldots + x_n}{n}$$ 
$$\bar{x} = \frac{x₁ + x₂ + \ldots + x_n}{n}$$

>![alt text](Imagenes/8.png)


**Mediana**: La mediana es el valor central en un conjunto de datos ordenados. Divide el conjunto de datos en dos partes iguales, donde la mitad de los valores están por encima y la otra mitad están por debajo. Es útil para resumir datos cuando hay valores atípicos o cuando el conjunto de datos no sigue una distribución simétrica.

**Fórmula**: Para un conjunto de datos ordenado de manera ascendente:
- **Impar**: La mediana es el valor en la posición \((n + 1) / 2\).
>![alt text](Imagenes/9.png)
- **Par**: La mediana es el promedio de los dos valores centrales, en las posiciones \(n / 2\) y \((n / 2) + 1\).
>![alt text](Imagenes/10.png)

    Ejemplo: 
    Consideremos el conjunto de datos: 5, 7, 9, 10, 12. El conjunto de datos ordenado sería: 5, 7, 9, 10, 12. La mediana sería el valor en la posición \((5 + 1) / 2 = 3\), que es 9.

**Moda**: La moda es el valor que ocurre con mayor frecuencia en un conjunto de datos. Puede haber una moda (unimodal) si un solo valor se repite con más frecuencia, o múltiples modas (multimodal) si varios valores tienen la misma frecuencia máxima. También puede haber casos donde no haya moda en absoluto (datos sin modas).

    Ejemplo: Consideremos el conjunto de datos: 2, 4, 4, 6, 8. En este caso, la moda es 4, ya que ocurre con mayor frecuencia en el conjunto de datos.

**Medidas de dispersión**


Las medidas de dispersión describen qué tan juntos o separados entre sí se encuentran los valores. Esta vez estudiaremos el rango e índice intercuartílico (IQR).

* **Rango**: Medida que nos indica la distancia de nuestros valores y se calcula restando: valor máximo - valor mínimo.
    **Formúla**
    $$\text{Rango} = \text{max} - \text{min}$$

* **Índice intercuartílico (RIQ o IQR)**: Diferencia entre el tercer y primer cuartil de una distribución.

    **Formúla:**
    $$\text{IQR} = Q3 - Q1$$

* **Cuartil**: Distribución en cuartiles o en cuartos de los datos.


## Desplazamiento y escala de valores

El desplazamiento y la escala de valores son modificaciones que les puede ocurrir a nuestros datos y esto afecta las medidas de dispersión y tendencia. Estos son los siguientes casos que se pueden presentar de desplazamiento y sus implicaciones en los datos:

1. **Desplazamiento (suma y resta).**
La media, la mediana y la moda se modificarán, si todos los datos de nuestra escala se suma o resta el mismo número, la media, mediana y moda tambien sufrirán de esta modificación.
El rango y el IQR no reciben ninguna modificación cuando todos los valores de nuestra tabla sufren la misma cantidad de sumatoria o resta.

2.**Escalar (multiplicación y división).**
Todas las medidas de dispersión y tendencia sufren una modificación, sin embargo, si todos los datos son multiplicados por la misma cifra, al multiplicar por dicha cifra nuestras medidas obtendremos el resultado.
Añadir o quitar un punto de datos en el conjunto.
En estos casos nuestras medidas cambian completamente dependiendo los datos que eliminemos, para asegurarnos de tener las medidas correctas debemos reformular todas las medidas. 
    
    Ejemplo: Si eliminamos el número que obtuvimos en la moda, puede que este ya no sea el valor que mas se repita, al eliminar o añadir un dato, tanto el rango como la mediana, la media y el IQR se dividen por otros números totales, dándonos un valor diferente al inicial.

>![alt text](Imagenes/11.png)

## Boxplot o diagrama de caja

Este tipo de gráficos nos permite identificar valores atípicos y comparar distribuciones. Además de conocer de forma rápida como se distribuyen el 50% de los valores centrales.

Las ventajas  principales de representar la distribución de los datos utilizando este método son:

Visualizar si la distribución de una variable es asimétrica o se aleja de la distribución normal.
La facilidad al comparar distribuciones entre grupos. Aunque se tendrá que usar técnicas estadísticas para establecer la significación de las diferencias percibidas.
Interpretación:

Caja:

La caja está determinada por la distancia del rango cuartilico, que es la diferencia entre el primer y tercer cuartil. El segmento que divide a la caja es la mediana.

Si la mediana se sitúa en el centro de la caja, entonces la distribución es simétrica y tanto la media, mediana y moda coinciden.
Si la mediana corta la caja en dos lados desicuales se tiene:
Asimetría positiva o sesgada a la derecha si la parte más larga de la caja es la parte superior a la mediana. Los datos se concentran en la parte inferior de la distribución. La media suele ser mayor a la mediana.

Asimetría negativa o sesgada a la izquierda si la parte más larga es la inferior a la mediana. Los datos se concentran en la parte superior de la distribución. La media suele ser menor que la mediana.

>![alt text](Imagenes/12.png)

💡 Que un lado de la caja sea más amplio que el otro, no quiere decir que contenga más datos, si no que los datos están más dispersos. Un rango menos amplio, indica que los datos están más próximos. </aside>
Bigotes:

Los Bigotes son las líneas verticales que se extienden desde la caja hasta los valores máximo y mínimo de la serie o 1.5 veces el IQR.

Valores átipicos (outliers):

Estos valores son aquellos que están más allá del límite inferior o superior.

## Media, varianza y desviación estándar


- **Media**: Es el promedio de un conjunto de datos. Para la media poblacional se usa la letra griega µ (miu), y para la media muestral se usa X̅ (promedio aritmético). La fórmula es la suma de todos los valores dividida por la cantidad de datos.

- **Varianza**: Mide la dispersión de los datos respecto a la media. La varianza muestral se calcula restando cada valor del promedio, elevando al cuadrado esas diferencias, sumándolas y dividiendo por n-1 (donde n es el tamaño de la muestra). La varianza poblacional se calcula de manera similar, pero se divide por N (tamaño de la población).

- **Desviación estándar**: Es la raíz cuadrada de la varianza y proporciona una medida de dispersión en la misma escala que los datos originales. Si la desviación estándar es mayor, los datos están más alejados de la media; si es menor, están más cerca del promedio.

>![alt text](Imagenes/13.png)

>![alt text](Imagenes/14.png)

## Histogramas, polígonos de frecuencia y curvas de densidad

* Histograma: Toma un intervalo y dentro de ese intervalo cuenta los eventos.
* Histograma de frecuencia relativa: mismo histograma pero comparado con un todo en porcentaje.

>![alt text](15.png)


* Polígono de frecuencia: Unión de los puntos más altos del histograma.

![alt text](image-1.png)


* Curva de densidad: Polígono de frecuencia suavizado del 100% de los datos utilizado para visualizar el rango de los datos.

![alt text](image-2.png)


## Distribuciones simétricas y asimétricas

### Distribuciones Simétricas 

Cuando los datos de la izquierda son los mismos que la derecha respecto a la media. La media y mediana están en el punto central.
En los gráficas podemos determinar que la moda es diferente para cada gráfica, el gráfico superior nos indica que las medidas de tendencia central están en el mismo punto (media, mediana y moda); mientras que la segunda gráfica que es bimodal, indica que tiene 2 modas.

![alt text](image-3.png)

Distribución normal

* Tambien llamada “de campana”,”de Gauss” o “Gaussiana”
* Sus medidas de tendencia central son las mismas
* Su “50%” central está dentro de 2/3 de desviación estándar hacia la izquierda y derecha de la media.

### Distribuciones asímetricas

 Cuando los datos tienden hacia la izquierda o hacia la derecha. Gran cantidad de valores atípicos. La cola es la gran concentración de valores atípicos
Menor frecuencia a mayor distancia que nos estemos alejando de nuetros datos.

La gráfica superior indica que tiene distribución asimétrica positiva ya que la cola tiende hacia la derecha (se hace más delgada a la derecha).

La gráfica inferior indica que la mayoría de datos se concentran en la parte derecha y nuestos valores atípicos tienden hacia la izquierda, entonces tenemos una distribución asimétrica negativa.

![alt text](image-4.png)

La moda será el punto más alto, es decir el valor más frecuente.

La mediana (representa el punto de equilibrio) :

1. En la distribución asimétrica positiva estará a la derecha de la moda
2. En la distribución asimétrica negativa estará a la izquierda de la moda:

La media:

1. En la distribución asimétrica positiva estará a la derecha de la mediana
2. En la distribución asimétrica negativa estará a la izquierda de la mediana

![alt text](image-5.png)

**Valores Atípicos**

* Valores atípicos bajos
Q1 - 1.5 (IQR)
* Valores atípicos altos
Q3 + 1.5 (IQR)


## Métodos de recopilación de datos

Objetivo de la Estadística → Tener valores representativos que nos indiquen dentro de una población o muestra de estudio algo que necesitamos saber.

**Población:** Es el universo, conjunto o todo, de datos sobre los que se harán estudios.
* Medidas de tendencia central y medidas de dispersión. (Media poblacional y desviación estándar poblacional).

**Muestra:** Selección aleatoria y respresentativa de la población que vamos a analizar.

* Medidas de tendencia central y medidas de dispersión. (Media muestral y desviación estándar muestral).

**Recopilación de datos**

* Estudios Observacionales → Son aquellos en los cuales nuestra muestra es intacta, sólo se analiza. No se introducirá ningun tratamiento o afectación. Estos datos se recopilan en:
    - Tablas unidimensionales
    - Tablas bidimensionales

* Estudio Experimental → Dentro de este estudio se aplicará un tratamiento a la muestra, se introduce algo que se quiere identificar como afectador o no.

    Características
    - Muestras aleatorias.
    - Se usan 2 grupos: 
        - Grupo de control: Se divide en **control ciego** (La muestra no sabe si recibe placebo/tratamiento) o **doblemente ciego** (Ni experimentadores ni muestreo saben en que grupo estan).
        - Grupo de estudio.
    - Replicación
    - Bloqueo (matched pairs) Que el grupo sea equitativo respecto a género, edad etc.
    - Comumente estos estudios Involucran adicciones o medicamentos.

## Muestreo y Sesgo

![alt text](image-6.png)

**Muestreo:** Proceso de selección de una muestra de una población para realizar un estudio estadístico.

**Sesgo:** Variación que no nos ayuda a encontrar lo que estamos buscando, no es un error.

* Sesgo de respuesta
    - Medición incorrecta
    - Deseabilidad social
    - Preguntas inductivas o capciosas

* Sesgo de infracobertura
    - Selección
    - Respuesta voluntaria
    - Muestreo a conveniencia

* Sesgo de no respuesta

## ¿Qué es la probabilidad y cómo se relaciona con la estadística?

La probabilidad es la ciencia que mide la certidumbre de que ocurra o no un evento.

* Probabilidad simple o teórica:  número de resultados favorables/número total de resultados posibles. Los eventos deben tener la misma probabilidad de ocurrir. Valor de 0 a 1 o de 0 a 100%

![alt text](image-7.png)

* Probabilidad experimental: El evento que cumpla con nuestro criterio esté dentro de todos los resultados que hayamos anotado con cada experimento hecho.

![alt text](image-8.png)

**Regla de la suma**

La probabilidad de tener un evento u otro va a ser igual a la suma de la probabilidad de mi primer evento más la probabilidad de mi segundo evento menos la probabilidad de la intersección de ambos eventos.

![alt text](image-9.png)

**Probabilidad condicional**

Aquella medida que nos dice cuál es la probabilidad de un eventoo afectado por otro previamente.

![alt text](image-10.png)

* Eventos independientes: Solo los eventos que realizados de forma sucesiva no afectan al siguiente evento/acción.
* Eventos dependientes: Aquellos que a cada una de su realización van a afectar al evento subsecuente.