
<div style="text-align: center;">
  <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/logo.png" alt="logo" />
</div>

# Proyecto Clustering y Modelos de Regresión

En este proyecto, asumirás el rol de **cientifico de datos en una empresa de comercio global**. La compañía busca comprender mejor su base de clientes, productos y operaciones para tomar decisiones informadas que maximicen el beneficio y optimicen sus procesos. 

## Tratamiento de datos

1. **Columnas eliminadas por no aportar valor:**
   'Row ID','Postal Code','Customer ID','Customer Name','Ship Date','Order Date','Order ID'
2.  **Estandarizacion de datos con StandardScaler**
3.  **Los Outliers se han dejado como estaban, consideramos que son datos correctos**

## Objetivo del Proyecto

1. **¿Cómo podemos agrupar a los clientes o productos de manera significativa?**
   **Clustering kmeans**
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/02.png" alt="logo" />
   </div>

3. **¿Qué factores son más relevantes para predecir el beneficio o las ventas dentro de cada grupo?**

   - Dado el grafico anterior, los datos que mas aportan son Sales, Quantity, Discount, Profit, Shipping Cost.

4. **¿Cómo podemos utilizar estos *insights* para tomar decisiones estratégicas?**

   - los clientes del cluster 2 deberian de tener algun tipo de beneficio o programa de fidelizacion para gastos de envio o descuentos, ya que son los que mas compran y se obtiene el mayor beneficio.

**Clustering elegido kmeans, ya que es el que mejor me ha segmentado**:: 

1. **Regresión por Segmentos Cluster 0 (35603 registros)**:
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/04.png" alt="logo" />
   </div>
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/05.png" alt="logo" />
   </div>

 2. **Regresión por Segmentos Cluster 1 (13799 registros)**:
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/06.png" alt="logo" />
   </div>
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/07.png" alt="logo" />
   </div>
   
 3. **Regresión por Segmentos Cluster 2 (1888 registros)**:
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/08.png" alt="logo" />
   </div>
   <div style="text-align: center;">
     <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/09.png" alt="logo" />
   </div>

## Estructura del Proyecto

Este proyecto está dividido en varias etapas las cuales son: 

<div style="text-align: center;">
  <img src="https://github.com/santiagorodriguez-dev/Proyecto9-Clustering/blob/main/images/01.PNG" alt="logo" />
</div>

## Conclusiones
Recomendacion de fidelizar al segmento de clientes que dan mayor beneficio, aplicando descuentos ya sea en el valor del producto o en los gastos de envio
siempre vigilando el beneficio.
Tambien podemos deducir que el clustering no resuelve todos los problemas y depende de la naturaleza de los datos.

#### Propuestas de Mejora:
   - Realizar modelo web predictivo.
  
## Construido con 🛠️

* [Pyhton](https://www.python.org/) - Lenguaje utilizado
* [Numpy](https://numpy.org/doc/stable/) - Numpy
* [seaborn](https://seaborn.pydata.org/tutorial.html) - Seaborn
* [matplotlib](https://matplotlib.org/stable/users/index) - matplotlib
* [pandas](https://pandas.pydata.org/docs/) - pandas
* [scikit-learn](https://scikit-learn.org/stable/user_guide.html) - scikit-learn
* [Visual Studio Code](https://code.visualstudio.com/) - IDE desarrollo
  
## Autores ✒️

* **Santiago Rodriguez** - [santiagorodriguez-dev](https://github.com/santiagorodriguez-dev)
