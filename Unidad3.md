# Unidad 3: Estadística No Paramétrica y Modelado de Regresión

En esta sección guardamos todas las prácticas, los laboratorios, la nota del examen y la defensa del trabajo autónomo. Básicamente, es todo lo que hicimos sobre pruebas no paramétricas, análisis de correlación y construcción de modelos de regresión aplicados al proyecto.

### Registro de Actividades Prácticas (APEs)

Aquí está el repositorio con todos los laboratorios. Solo dale clic al título de cada práctica para ver el código directamente en GitHub:

* **[APE 11: Pruebas de Bondad de Ajuste y Normalidad](./APE11.ipynb)**  
  Aplicación de pruebas como Chi-cuadrado y Shapiro-Wilk para comprobar formalmente si nuestros datos siguen una distribución normal.

* **[APE 12: Pruebas de Hipótesis No Paramétricas](./APE12.ipynb)**  
  Uso de Mann-Whitney, Wilcoxon y Kruskal-Wallis para comparar grupos cuando los datos no cumplen con los supuestos de normalidad.

* **[APE 13: Análisis de Correlación Lineal y No Lineal](./APE13.ipynb)**  
  Cálculo e interpretación de matrices con los coeficientes de Pearson y Spearman para descubrir qué tanto se relacionan las variables entre sí.

* **[APE 14: Regresión Lineal Simple y Diagnóstico](./APE14.ipynb)**  
  Creación de modelos predictivos de una sola variable, calculando el $R^2$ y revisando que los residuales se comporten bien.

* **[APE 15: Regresión Lineal Múltiple y Selección de Variables](./APE15.ipynb)**  
  Ajuste de modelos complejos con varios predictores a la vez utilizando `statsmodels` y `scikit-learn`, controlando la multicolinealidad.

---

* **[Dataset Fuente: Datos de Loja](./enemdu_vivienda_hogar_2026_02.csv)**  
  El archivo original con los datos de Loja que seguimos utilizando para entrenar los modelos y correr las simulaciones en Python.

### Bitácora de Aprendizaje y Autoevaluación (Componente 3)

**1. Lo que me llevo de la Unidad de Modelado:**  
En esta unidad el gran salto fue pasar de comparar grupos a predecir comportamientos y encontrar relaciones reales entre variables. Lo mejor fue entender que no siempre podemos usar estadísticas paramétricas y aprender a defender un modelo cuando los datos no son normales. También me quedó súper claro cómo interpretar las pendientes de regresión, el $R^2$ ajustado y por qué no podemos meter variables a lo loco sin revisar la multicolinealidad.

**2. Los dolores de cabeza con el código:**  
Lo más pesado fue lidiar con el diagnóstico de los residuales en la regresión múltiple y armar los gráficos de dispersión con líneas de tendencia sin que se rompa `seaborn` o `matplotlib`. Además, entender e interpretar las tablas de resumen de `statsmodels.api` (con tanta métrica junta como el F-statistic, AIC y BIC) al principio abrumaba bastante, pero armando funciones para extraer justo lo necesario quedó mucho más ordenado.

---

### Competencias Consolidadas

* **Modelado estadístico y predictivo:** Capacidad para construir, evaluar y validar modelos de regresión lineal simple y múltiple interpretando sus coeficientes y métricas de error.
* **Análisis no paramétrico y correlacional:** Habilidad para aplicar alternativas robustas de inferencia cuando los datos no cumplen supuestos teóricos y para mapear relaciones multivariables.
