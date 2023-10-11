# **Proyecto de Análisis de Datos de Criminalidad en Chicago**

## **FASE 2: Gestión de Datos e Información de Comisarías de Policía**

### **Objetivo Principal**
En esta fase, hemos recibido datos relacionados con la criminalidad en la ciudad de Chicago, así como información sobre la ubicación de las comisarías de policía. Nuestra misión consiste en crear una base de datos para registrar los delitos, información de las comisarías, hospitales y datos relacionados con las áreas comunitarias donde los oficiales realizan sus labores.

### **Tareas Clave**
En esta fase, nos enfocaremos en las siguientes tareas cruciales:


* **Construcción del diagrama Entidad-Relación (ER) representado de forma gráfica.**
  En este caso, el diagrama ER debe mostrar las siguientes entidades:

    * **Delitos:** Representa los delitos cometidos en la ciudad de Chicago.
    * **Comisarías:** Representa las comisarías de policía de la ciudad de Chicago.
    * **Hospitales:** Representa los hospitales de la ciudad de Chicago.
    * **Áreas comunitarias:** Representa las áreas comunitarias donde los oficiales realizan sus labores.

* **Descripción de las tablas resultantes del diagrama ER, incluyendo todos sus atributos.**
* **Creación de las tablas para incorporarlas en el Modelo Relacional.**
* **Creación de querys funcionales y necesarias para la creación de la base de datos, las tablas y sus atributos.**
* **Mantener información sobre 'delincuentes' utilizando MongoDB Atlas.**
  
       * Crear una búsqueda comprendida entre dos fechas de nacimiento.
       * Encontrar los criminales acusados de robo con violencia.
       * Buscar a los criminales con estatura menor a 180 y peso mayor a 75.

Para ello se debe crear la asignada base de datos y la colección ‘criminales’ e implementar al menos 5 registros que tengan los siguientes campos:



```
{
  "_id": 1,
  "nombre": "AARON",
  "apellidos": "WILLIAMS-BANKS",
  "cuadra": "072XX S SOUTH SHORE DR",
  "delitos": [
    "agresión sexual",
    "robo con violencia"
  ],
  "estatura": 185,
  "peso": 80,
  "f_nacimiento": "1976-03-01T08:00:00Z"
}

```

