# IMT2200 Introducción a la Ciencia de Datos

## Grupo 24: ¿Cómo influye la modalidad de trabajo (remoto o presencial) en la salud mental de los trabajadores y cómo se relaciona esta con su nivel de productividad?

Profesor: Rodrigo A. Carrasco

Miembros:

*  Valentina Valdivia

*  Diego Fernández

*  Gabriel Fuentes

*  Natalia Vallejos

## 1. Contexto y Motivación

En las últimas décadas, la salud mental se ha vuelto un tema prioritario a nivel mundial, siendo uno de los mayores desafíos de salud pública. Según la Organización Mundial de la Salud (OMS), los casos de trastornos mentales han aumentado considerablemente, afectando tanto a jóvenes como a adultos en edad laboral.

El entorno laboral es uno de los principales factores que puede influir en el bienestar psicológico, ya que suele generar situaciones de estrés, exceso de trabajo e inseguridad laboral. Tras la pandemia, surgieron nuevas modalidades como el trabajo remoto e híbrido, que ofrecen ventajas —como mayor flexibilidad y equilibrio entre la vida personal y laboral—, pero también desventajas, como dificultades para desconectarse del trabajo o aislamiento social (Int. J. Environ. Res. Salud Pública 2022).

Por ello, este proyecto busca estudiar cómo la modalidad de trabajo influye en el bienestar de los trabajadores, utilizando diversos datasets de Kaggle. Además, se analizarán factores como la productividad y el rendimiento, con el fin de identificar patrones y tendencias que permitan promover entornos laborales más saludables y sostenibles.

## 2. Preguntas Objetivo 

### Pregunta principal: 
¿Cómo influye la modalidad de trabajo (remoto o presencial) en la salud mental de los trabajadores y cómo se relaciona esta con su nivel de productividad?

### Preguntas específicas: 
-¿Existen diferencias significativas en los niveles de estrés en trabajadores remotos y presenciales?

-¿La modalidad de trabajo (remoto o presencial) influye en los niveles de satisfacción laboral y bienestar emocional?

-¿Los trabajadores remotos reportan mayor o menor equilibrio entre vida personal y laboral en comparación con los presenciales, y cómo impacta esto en su rendimiento?

-¿Se observa una correlación entre salud mental y productividad dentro de cada modalidad de trabajo?

-¿Qué factores pueden influir en el resultado de los datos estudiados?

## 3. Estructura del Repositorio

**`info.pdf`** - Contiene la información del equipo de trabajo, incluyendo los nombres y perfiles de GitHub de cada integrante.

### Notebooks (`/notebooks`)

En esta carpeta se encuentran los notebooks principales del proyecto:

**`IMT2200_Proyecto_EDA_Grupo24.ipynb`** - Este es el notebook principal del proyecto, donde se presenta el análisis completo incluyendo:
- Un resumen del proyecto con una breve introducción que conecta con lo entregado previamente
- El análisis de datos, donde se describen y documentan todos los métodos computacionales y estadísticos aplicados al modelamiento. Aquí se justifican las decisiones tomadas (selección de variables, configuración de algoritmos, normalizaciones, validaciones) y se evalúan los resultados mediante métricas apropiadas como error cuadrático, intervalos de confiabilidad, precisión, recall, F1, matrices de confusión, entre otras
- Un resumen narrativo y visual de los resultados, explicando cómo estos responden a la pregunta de investigación original
- Una sección crítica sobre las posibles limitaciones y sesgos de los datos o análisis, identificando qué problemas podrían generarse a partir de la solución o las decisiones recomendadas

### Datos (`/data`)

Esta carpeta almacena todos los datasets utilizados en el análisis. Los archivos incluyen distintas fuentes de datos relacionadas con trabajo remoto, salud mental y productividad.

### Tests (`/tests`)

En esta carpeta se encuentran los notebooks de prueba y exploración individual desarrollados durante el proceso de análisis:
- `diego_limpieza.ipynb`
- `impact.ipynb`
- `mental.ipynb` 
- `productivity.ipynb` 
- `surveyjune.ipynb` 
