![Universidad Nacional de Córdoba](https://webs.uab.cat/incasi/wp-content/uploads/sites/308/2016/05/UNC.png)

![Facultad de Ciencias Exactas, Físicas y Naturales](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3ggWMV5Tb5imJp3a_IgIdVzaeAru_7qLSBCFKPubxfkt3OFsupXSuzUF9Wdh9qdr1SQ&usqp=CAU)

# DESARROLLO/EVALUACIÓN DE MODELO PREDICTIVO PARA ESTIMAR CONCENTRACIÓN DE AEROSOLES EN ATMOSFERAS DE ZONAS URBANAS

* Author: Rodriguez Nuñez Martin
* Directora: Hebe Alejandra Carreras
* Codirectora: Monica Balzarini
* Título: 'Doctor en Ciencias de la Ingenieria'

	La Organización Mundial de la Salud (OMS) estima que nueve de cada diez personas respira aire con altos niveles de contaminante y como resultado siete millones mueren cada año en el mundo por causas relacionadas. El material particulado fino, partículas con un diámetro menor o igual a 2.5 micrómetros (PM~2.5~), es considerado uno de los contaminantes atmosféricos de mayor nocividad dada su capacidad de penetrar la barrera pulmonar y pasar al torrente sanguíneo, causando enfermedades cardiovasculares, respiratorias y cáncer. El monitoreo de la concentración de PM~2.5~ a través de sensores de referencia se ve limitado en países subdesarrollados dado a sus elevados costes de adquisición y mantenimiento, motivo por el cual se hace necesario recurrir a métodos alternativos para lograr monitorear su concentración y gestionar la calidad del aire. Como consecuencia esta tesis aborda el desarrollo de un sistema de alerta ante condiciones adversas de calidad de aire de bajo costo, centrando su estudio en el desarrollo de sensores de monitoreo de bajo costo de concentración de PM~2.5~, su variabilidad espacio temporal, su covariabilidad con variables satelitales y la predicción futura de su concentración. A pesar de los numerosos estudios que han investigado la variabilidad de las concentraciones de PM~2.5~ con respecto a las condiciones atmosféricas, la predicción precisa de valores futuros sigue siendo un desafío. La variabilidad de la serie temporal de concentración de PM~2.5~ depende de numerosas variables relativas a la condición atmosférica, el uso del suelo y al momento del tiempo en que se tomo el dato, siendo varias de ellas de público acceso en la nube. Sin embargo, el desarrollo de modelos predictivos tanto lineales como no lineales es limitado. La disponibilidad de un modelo de alto alcance predictivo permitiría construir un sistema de alerta temprana ante eventos nocivos de calidad de aire. De esta forma, el objeto principal de esta tesis es evaluar y comparar la capacidad predictiva de variables satelitales de público y fácil acceso en la nube y múltiples algoritmos de inteligencia artificial para pronosticar las concentraciones de PM~2.5~ en una ciudad urbana, como lo es Córdoba, Argentina. Además, se busca evaluar la utilidad de sensores de bajo costo para el monitoreo de la concentración de PM~2.5~, describir su variación espacio temporal y analizar la influencia y contribución de variables satelitales en los patrones de variación temporal de la concentración de PM~2.5~ en el área de estudio. En primera instancia fue necesario el diseño y desarrollo de sensores de bajo costo que permitiesen recopilar datos del contaminante. Para garantizar la integridad de las mediciones realizadas, debió llevarse a cabo un estudio de la estabilidad entre sensores y otro de validación con respecto a una estación de referencia. Se dispusieron sensores en diez sitios con diferentes usos de suelo (urbano, industrial y agrícola/área verde) ubicados dentro del área metropolitana de la provincia de Córdoba. Se obtuvieron series temporales de frecuencia horaria a lo largo de periodos de al menos un año. Posteriormente, se descargaron 164 variables de la plataforma ERA5, y 14 citadas en la literatura relacionada a PM~2.5~, desde los satélites MODIS, MERRA-2 y VIIRS. Se ajustaron, para cada uso de suelo, modelos de regresión lineal múltiple, máquinas de vectores de soporte, k vecinos más cercanos, bosques aleatorios, máquinas de aumento de gradiente y redes neuronales recurrentes, para predecir la concentración de PM~2.5~. Además, los modelos predictivos se ajustaron implementando distintas estrategias de selección de variables, base de datos original (completa) y reducida por la combinación de múltiples algoritmos de selección de características, entre los cuales se encuentra el algoritmo featurewiz y Boruta. El consenso entre los distintos sensores de bajo costo se reflejó en coeficientes de correlación calculados de a pares de sensores siempre mayores a 0.99, además el mayor error absoluto medio entre pares de sensores fue de 2.66 $\frac{\mu g}{m^3}$. Las concentraciones de PM~2.5~ registradas variaron desde 0.53 $\frac{\mu g}{m^3}$ hasta 150.28 $\frac{\mu g}{m^3}$, con una concentración promedio horaria de 10.65 $\frac{\mu g}{m^3}$. Se observó que condiciones adversas de calidad de aire ocurrieron principalmente durante la noche y las primeras horas de la mañana en la temporada de invierno. A pesar de los aumentos estacionales en los niveles de PM~2.5~ debido a inversiones térmicas, los niveles promedio observados en Córdoba fueron menores en comparación con otras ciudades del mundo. Los modelos de mayor capacidad predictiva para cada uno de los usos de suelo obtuvieron un error de predicción de 3.441 $\frac{\mu g}{m^3}$, 2.596 $\frac{\mu g}{m^3}$ y 6.171 $\frac{\mu g}{m^3}$ para el uso de suelo urbano, agrícola/área verde e industrial respectivamente. La serie de concentración de PM~2.5~ en el uso de suelo agrícola/área verde tuvo menos variabilidad, destacó menor cantidad de variables de relevancia para la predicción y el menor error de predicción se obtuvo con el modelo de bosques aleatorios. Por el contrario, la serie urbana e industrial, demostraron mayor variabilidad, destacando el algoritmo de redes neuronales recurrentes como el de mayor capacidad predictiva. Las predicciones horarias de concentración de PM~2.5~ esperadas en un horizonte futuro de cinco días mostraron un error de predicción menor al 23%. Estos hallazgos sugieren que la integración de datos satelitales y algoritmos de aprendizaje automático y profundo pueden ser una herramienta valiosa para predecir las concentraciones de PM~2.5~ en áreas con capacidades limitadas de monitoreo, proporcionando información esencial para alertar a la población ante condiciones desfavorables de calidad del aire.  

**Palabras claves:** contaminación atmosférica, monitoreo de calidad del aire, variables satelitales, sensores de bajo costo, aprendizaje automático, aprendizaje profundo, selección de características. 