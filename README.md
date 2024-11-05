# coder2j-pyspark-tutorial
1. [Intro](#schema1)
2. [PySpark Install and Setup with JupyterLab](#schema2)

[Resources](#schemaref)

<hr>
<a name='schema1'></a>

## 1. Intro

![Content](./img/content.jpg)
![spark](./img/spark-1.jpg)

<hr>
<a name='schema2'></a>

## 2. PySpark Install and Setup with JupyterLab

1. Install Java Development Kit (JDK), spark run on java 8, 11, or 17
    - https://www.oracle.com/java/technologies/downloads/#jdk21-mac

2. Install Apache Spark
    - https://spark.apache.org/downloads.html

3. Install Python

4. Create env
    ``` bash
    python3 -m venv nombre_del_entorno
    ```
5. Activate
    ``` bash
    source pyspark-env/bin/activate
    ```
6. Install Pyspark and jupyterlab
    ```
    pip install pyspark
    
    pip install findspark

    pip install jupyterlab
    ```
`findspark` es una herramienta útil cuando trabajas con PySpark en entornos de desarrollo como Jupyter Notebook o directamente en Python, ya que simplifica la configuración inicial de Spark. Aquí te explico su función:

- ¿Para qué se usa findspark?
Configuración del entorno Spark: findspark facilita la localización de la instalación de Spark y agrega automáticamente las rutas necesarias a las variables de entorno de Python, como SPARK_HOME y PYTHONPATH. Esto asegura que PySpark pueda encontrar los archivos y bibliotecas necesarios para ejecutarse correctamente.

- Uso en notebooks: Al trabajar en entornos como Jupyter Notebook, findspark permite que el notebook detecte la instalación de Spark sin necesidad de configuraciones complejas. Esto es especialmente útil si Spark no se ha instalado en rutas estándar o si se está ejecutando en un entorno donde los paquetes no están configurados globalmente.

- Simplificación de la inicialización: Con findspark, puedes simplemente importar e inicializar PySpark sin tener que realizar configuraciones manuales en cada script. Esto es práctico para desarrolladores y data scientists, ya que evita posibles problemas de configuración y facilita la reproducción de entornos de Spark en distintas máquinas.


7. Launch JupyterLab and use PySpark
```
jupyter-lab
```
[PySpark-Get-Started](PySapk-Get-Started.ipynb)


<hr>
<a name='schemaref'></a>

## Resources

https://www.youtube.com/watch?v=EB8lfdxpirM

https://github.com/coder2j/pyspark-tutorial