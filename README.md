### Movilidad urbana y productividad económica en ciudades de LATAM
Análisis de la relación entre la movilidad urbana (niveles de congestión, tiempos de viaje, retrasos) y la productividad económica (PIB per cápita, desempleo) en las principales ciudades latinoamericanas.
Este proyecto se desarrolla en el contexto de un equipo de análisis de datos del Latin American Development Bank, con el objetivo de identificar en qué ciudades invertir en infraestructura de transporte para mejorar la productividad y el bienestar de la población.
Para ello, se usaron dos fuentes reales de datos:
Movilidad urbana: TomTom Traffic Index (datos de tráfico en tiempo real).
Economía urbana: OECD Cities (PIB per cápita, desempleo y población).

La misión fue limpiar, unir y analizar ambas bases para generar insights accionables.

### **Preguntas del negocio**
1. ¿Qué ciudades de América Latina presentan alta congestión y baja productividad económica?
2. ¿Cuáles muestran los mejores indicadores combinados (movilidad eficiente y economía fuerte)?
3. ¿Qué variables parecen tener una relación más fuerte con el desarrollo urbano?

### **Herramientas tenológicas** 
 • Jupyter Notebook
 
 • Python: pandas, numpy, seaborn, matplotlib

### **Dataset del proyecto**
Fuentes principales de información:
1. tomtom_traffic.csv : Datos sobre congestión vehicular y condiciones de tráfico en ciudades del mundo.
2. oecd_city_economy.csv : Indicadores económicos y ambientales por ciudad, recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económico).
   
Ambas tablas se complementan para entender cómo la eficiencia del tráfico urbano se relaciona con el desempeño económico en ciudades latinoamericanas.

## **Dataset 1: tomtom_traffic.csv**

Registra información sobre niveles de tráfico y congestión en tiempo real en distintas ciudades monitoreadas por TomTom, una empresa global de geolocalización.
Cada registro corresponde a una actualización puntual del estado del tráfico en una ciudad.

![Dataset 1](dataset1.png)

## **Dataset 2: oecd_city_economy.csv**

Contiene indicadores anuales sobre economía urbana, empleo, contaminación y población recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económicos).
Cada registro representa una ciudad en un año específico, lo que permite comparar niveles de productividad y desarrollo urbano entre países.


![Dataset 1](estructura_dataset2.png)

### **Plan de acción**

Construir una tabla unificada que combine variables de movilidad urbana (TomTom) con variables económicas (OECD) para ciudades de América Latina en 2024.
El objetivo es generar una base de datos limpia y estandarizada para analizar cómo la movilidad impacta la productividad económica.

### **Metodología**
1. Exploración de datos: Identificación de columnas, tipos de datos y estructura general.
2. Limpieza de datos: Estandarización de nombres de columnas y corrección de tipos de datos.
3. Estandarización y filtrado de fecha: El período más reciente y relevante, el año 2024.
4. Agregación de datos: Cálculo de promedios de tráfico por ciudad.
5. Unión de datasets: Integración de datos de movilidad y economía en una sola tabla.
6. Análisis y visualización: Generación de gráficos para identificar patrones y relaciones entre variables.

### **Resultados clave**
### **Conclusiones**
### **Recomendaciones**
