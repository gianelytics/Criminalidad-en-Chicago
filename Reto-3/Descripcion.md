
# **Proyecto de Análisis de Datos de Criminalidad en Chicago**

## **FASE 3: Análisis de Variables para Modelar los Índices de Criminalidad en Áreas Comunitarias de Chicago**

### **Objetivo Principal**
En esta fase, se nos han proporcionado los datos relativos a las diferentes áreas comunitarias de la ciudad de Chicago. Con el fin de explicar y modelar las posibles razones detrás de los índices de criminalidad, se nos ha solicitado estudiar las distintas variables disponibles para determinar si tienen influencia en la criminalidad de la ciudad.

### **Variables disponibles**
Las variables disponibles en el dataset son las siguientes:
* **Community Area:** Número entero que identifica al área comunitaria.
* **Name:** Nombre del área comunitaria.
* **Population:** Número de habitantes en ese área comunitaria.
* **Latinos:** Índice de personas latinas residentes en el área comunitaria.
* **Blacks:** Índice de personas negras residentes en el área comunitaria.
* **White:** Índice de personas blancas residentes en el área comunitaria.
* **Asian:** Índice de personas asiáticas residentes en el área comunitaria.
* **Other:** Índice de personas de otras razas residentes en el área comunitaria.
* **NUM_AFFORD_RENTAL_HOUSES:** Número de proyectos de casas asequibles en el área comunitaria.
* **NUM_HOSPITALES:** Número de hospitales en el área comunitaria.
* **NUM_SCHOOLS:** Número de colegios en el área comunitaria.
* **Ingresos:** Nivel de ingresos medios per cápita de los residentes de dicho área comunitaria.
* **Criminalidad_100000:** Índice de criminalidad calculado por cada 100.000 personas en ese área comunitaria.
* **Consumo_electrico:** Nivel de consumo eléctrico medio del área comunitaria.

### **Tareas Clave**
En esta fase, nos enfocaremos en las siguientes tareas cruciales:

* **Cargar los datos de `estadisticas_community_areas.csv`.**
    * Se debe realizar una correcta exploración y limpieza de los datos, siguiendo todos los pasos vistos en clase.
    
       * ¿Tiene sentido cambiar el tipo de dato de alguna variable?
       * ¿Existen filas duplicadas?
       * ¿Hay filas que no estén correctas y que deban eliminarse?
       * ¿Se observa algo atípico al graficar las variables?

* **Plantear un modelo predictivo que prediga el índice de criminalidad en la ciudad de Chicago.**
    * Identificar el tipo de problema analítico que se presenta.
    * Antes de ejecutar el algoritmo, estudiar la correlación entre las variables.
      
       * ¿Se extrae alguna conclusión relevante a partir de la correlación?
       * ¿Qué selección de variables se ha considerado?
       * Validar el modelo utilizando distintas métricas de error

* **Cargar el fichero `Delitos_Chicago.csv`.**
    * Plantear un modelo predictivo que prediga si un delito es doméstico o no doméstico. Para ello, considerar la variable Domestic como variable objetivo.

       * Identificar el tipo de modelo predictivo al que se enfrentan.
       * Determinar qué variables son útiles para alcanzar este objetivo y cuáles no lo son, justificando la selección.
       * Evaluar el modelo predictivo
       * Evaluar el error cometido tras el desarrollo del modelo utilizando las métricas adecuadas.   

* **Plantear una segmentación analítica de delitos atendiendo a sus características.**
       * ¿Cuántos segmentos tiene la solución planteada?
       * ¿Qué características tienen los delitos de cada segmento?
