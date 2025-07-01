# Proyecto-clustering
## “¿Existen perfiles similares de bienestar subjetivo que comparten los países de la OCDE?”
Valentina Flores | Ignacio Maluenda | Constanza Muñoz

## Descripción del proyecto
El concepto de bienestar subjetivo, entendido como la percepción individual sobre la calidad de vida, ha ganado relevancia en las últimas décadas como un indicador clave del desarrollo social, complementario a las métricas económicas tradicionales como el Producto Interno Bruto per cárpita (PIB) . En este estudio, se aplican técnicas de Machine Learning bajo un contexto de aprendizaje no supervisado para evaluar si es posible encontrar relaciones entre los países según el nivel de bienestar utilizando el "Better Life Index"  de la OCDE, este recopila indicadores objetivos por país —como ingreso, salud, educación, empleo, vivienda y seguridad — con lo que se construye una medida subjetiva de satisfacción de vida. Esto podría aportarnos información valiosa para la formulación de políticas públicas y el análisis comparado del desarrollo social.

## Resumen:
- Área(s) de aplicación: Economía (Desarrollo económico y economía del bienestar), políticas públicas  .
- Tipo de aprendizaje: No supervisado.
- Tipo de problema: Clustering.
- Fuente principal: OCDE Better Life Index (2024). https://www.oecdregionalwellbeing.org/ 
- Variable objetivo: No aplica. 
- Atributos explicativos principales: ingresos, empleo, educación, salud, balance vida-trabajo, medio ambiente, seguridad, compromiso cívico, conexiones sociales.
- Número estimado de observaciones totales: 38 países y sus regiones (miembros OCDE y asociados). En total son 6248 observaciones.

## Abstract: 
El presente estudio explora la segmentación de países de la OCDE a partir de indicadores objetivos del Better Life Index, utilizando técnicas de machine learning
no supervisado. En particular, se aplican los algoritmos K-Means y Gaussian Mixture Models (GMM) para identificar grupos de países con perfiles estructurales similares
en dimensiones como educación, salud, ingresos, seguridad, entre otras, y comparar la agrupación obtenida con la variable auto-reportada Life Satisfaction. Se incorpora
además un análisis de componentes principales (PCA) para reducir la dimensionalidad y se consideran aspectos geográficos para enriquecer la interpretación de resultados
con posibles patrones regionales. Los resultados muestran que ambos modelos logran diferenciar grupos con patrones significativos de desarrollo social, aunque K-Means presenta una mejor cohesión interna según el Silhouette Score. Finalmente, al comparar las agrupaciones obtenidas, se revela que los clusters con mayor bienestar estructural tienden a reportar mayores niveles de satisfacción subjetiva. Este análisis contribuye a una comprensión empírica multivariada del bienestar, y ofrece herramientas exploratorias para apoyar el diseño de políticas públicas orientadas a mejorar la calidad de vida.
