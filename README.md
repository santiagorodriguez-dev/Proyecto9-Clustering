
# Proyecto Clustering y Modelos de Regresión

En este proyecto, asumirás el rol de **cientifico de datos en una empresa de comercio global**. La compañía busca comprender mejor su base de clientes, productos y operaciones para tomar decisiones informadas que maximicen el beneficio y optimicen sus procesos. 

Trabajarás con un conjunto de datos del comercio global que incluye información sobre ventas, envíos, costos y beneficios a nivel de cliente y producto. Tu tarea será segmentar los datos mediante **clustering** y luego diseñar modelos de **regresión** específicos para cada segmento, lo que permitirá obtener insights personalizados sobre los factores que influyen en el éxito de la compañía.


## Objetivo del Proyecto

La empresa tiene las siguientes preguntas clave:

1. **¿Cómo podemos agrupar a los clientes o productos de manera significativa?**

   - Por ejemplo, identificar clientes según su comportamiento de compra o productos según su rentabilidad.

2. **¿Qué factores son más relevantes para predecir el beneficio o las ventas dentro de cada grupo?**

   - Esto ayudará a diseñar estrategias específicas de marketing, optimizar precios o ajustar políticas de descuento.

3. **¿Cómo podemos utilizar estos *insights* para tomar decisiones estratégicas?**

   - Por ejemplo, enfocarse en los segmentos más rentables o intervenir en los menos rentables.

Para contestar estas preguntas, el objetivo en este proyecto es realizar: 

1. **Clustering**: Realizar un análisis de segmentación para agrupar clientes o productos según características clave, las cuales deberás elegir personalmente además de justificar el porque de su elección.

2. **Regresión por Segmentos**: Diseñar modelos de predicción para cada segmento, explicando las relaciones entre variables, intentando predecir el total de ventas en cada uno de los segmentos. 

## Estructura del Proyecto

1. **Preparación de los Datos**:

   - **Carga de datos**: Familiarízate con las variables incluidas en el conjunto de datos (por ejemplo, ventas, costo de envío, beneficio, categoría de productos).

   - **Limpieza de datos**: Maneja valores faltantes, elimina duplicados y identifica y trata *outliers*.

   - **Transformaciones**: Normaliza variables numéricas y codifica variables categóricas si es necesario.

2. **Clustering**:

   - **Elección de variables**: Selecciona atributos clave para agrupar a los tipos de ventas que hacemos como empresa (por ejemplo, `Sales`, `Profit`, `Discount`, `Shipping Cost`).

   - **Escalado**: Normaliza las variables para evitar que algunas dominen sobre otras.

   - **Método de clustering**: Aplica algoritmos como K-means, clustering jerárquico o DBSCAN.

   - **Evaluación**: Determina el número óptimo de clusters usando técnicas como el método del codo o el coeficiente de silueta.

   - **Interpretación**: Analiza los clusters resultantes e interpreta su significado en términos de comportamiento del negocio.


3. **Modelos de Regresión por Clusters**:

   - **Variable objetivo**: Define una métrica clave para predecir (por ejemplo, `Sales`).

   - **Segmentación**: Ajusta un modelo de regresión para cada cluster, utilizando las variables disponibles.

   - **Evaluación**: Evalúa el desempeño de los modelos usando métricas como R², MAE o RMSE.

   - **Comparación entre clusters**: Identifica diferencias en los factores clave que impactan el beneficio en cada grupo.

4. **Entrega de Insights**:

   - Responde preguntas del negocio basándote en los resultados del clustering y los modelos de regresión.

   - Propón recomendaciones accionables para la empresa.


## Como Entregar el Proyecto

La entrega del proyecto se realizará a través de una **issue en GitHub**, trabajando en un repositorio propio en tu cuenta personal. Los pasos que deberás seguir para hacer la entrega del proyecto son:


- **Crear un nuevo repositorio en tu cuenta de GitHub:**

   - Crea un nuevo repositorio llamado `Proyecto9-NombreProyecto`. Este nombre es obligatorio, no podremos llamarlo de otra forma. 

   - Configuralo como público. 


- **Desarrolla el proyecto:**

   - Implementa el código para la resolución del problema.

   - Recuerda hacer commits regulares mientras avanzas en el desarrollo:

     ```bash
     git add .
     git commit -m "Descripción del avance"
     git push
     ```


- **Crear una issue en el repositorio original del curso:**

   - Ve al repositorio original del curso y dirígete a la pestaña de **Issues**.

- **Abrir una nueva issue para tu entrega:**

   - Haz clic en **New Issue** y llena los siguientes campos:

     - **Título:** Usa el formato "Entrega Proyecto: ProyectoXXXX - [Tu Nombre]".

     - **Descripción:** En la descripción, incluye:

       - Una breve explicación de tu proyecto.

       - Instrucciones para ejecutar tu código (si aplica).

       - Un enlace a tu repositorio personal donde está alojado el proyecto.


## 🚀 Entrega del Proyecto 🚀

**Fecha y hora límite:**

🗓️ **Lunes a las 9:00 AM.**


**Nota importante:**

⚠️ **Todos los proyectos que sean entregados o modificados después de la hora límite (lunes a las 9:00 AM) se considerarán como no entregados.** Por favor, asegúrate de completar y enviar tu trabajo a tiempo para evitar problemas.


# 🎤 Presentación de Proyectos 🎤

El lunes tendremos las **presentaciones de los proyectos**. La dinámica será la siguiente:

- De forma **aleatoria**, seleccionaremos entre **3 y 5 alumnos** para presentar su proyecto.

- Cada alumno tendrá **5 minutos** para explicar su proyecto y hacer una demo en vivo. Durante este tiempo podrán mostrar cómo funciona su juego y resaltar las características principales.

**Detalles importantes:**

- Es importante que lleguéis puntuales, ya que comenzaremos las presentaciones de inmediato.

- Asegúrate de que tu código esté listo y funcional para la demo.

- Todos debemos estar preparados para presentar, ya que la selección será completamente aleatoria.