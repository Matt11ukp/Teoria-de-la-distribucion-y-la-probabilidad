# Unidad 2: Distribuciones Continuas e Inferencia Estadística

En esta sección guardamos todas las prácticas, los laboratorios, la nota del examen y la defensa del trabajo autónomo. Básicamente, es todo lo que hicimos sobre distribuciones, estimación de parámetros y pruebas de hipótesis aplicadas al proyecto.

### Registro de Actividades Prácticas (APEs)

Aquí está el repositorio con todos los laboratorios. Solo dale clic al título de cada práctica para ver el código directamente en GitHub:

* **[APE 06: Distribuciones Continuas Notables](./APE06.ipynb)**  
  Creación y uso de funciones de densidad continuas aplicadas a casos estadísticos.

* **[APE 07: Distribuciones Muestrales y TLC](./APE07.ipynb)**  
  Comprobación del Teorema del Límite Central haciendo simulaciones estocásticas.

* **[APE 08: Inferencia Estadística - Intervalos de Confianza](./APE08.ipynb)**  
  Cálculo de parámetros y rangos de confianza usando las distribuciones Z y T de Student.

* **[APE 09: Pruebas de Hipótesis Paramétricas](./APE09.ipynb)**  
  Aplicación de pruebas Z y T, y cómo interpretar el famoso valor-p.

* **[APE 10: Inferencia Estadística Multigrupo](./APE10.ipynb)**  
  Uso de ANOVA de 1 factor y pruebas de Tukey para comparar varios grupos entre sí.

---

### Evaluación Sumativa y Base de Datos

* **[Evaluación Sumativa II: Examen Práctico](./Examen_UnidadII_Matias_Romero.ipynb)**  
  Resolución de problemas reales aplicando todo lo que aprendimos de inferencia y modelos estadísticos.

* **[Dataset Fuente: Datos de Loja](./enemdu_vivienda_hogar_2026_02.csv)**  
  El archivo original con los datos de Loja que usamos para correr todas las simulaciones en Python.

---

### Componente 2: (Defensa en Video)

* **[Video de Defensa - Componente 2](https://drive.google.com/file/d/1IuH6-SREl6r1NkJoXJtFIlHAy-vx2Pou/view?usp=drive_link)**  
  Un video corto donde explico por qué usamos pruebas paramétricas (después de pasar el test de Shapiro-Wilk), muestro cómo funciona el código en Jupyter y analizo el valor-p para tomar decisiones estadísticas.

---

### Bitácora de Aprendizaje y Autoevaluación (Componente 3)

**1. Lo que me llevo de la Unidad de Inferencia:**  
En esta unidad por fin pasamos de solo describir datos a hacer inferencia de verdad. Lo mejor fue aprender a automatizar en Python las pruebas previas antes de lanzarme a hacer pruebas paramétricas. También logré entender bien qué significa realmente el valor-p y cómo nos ayuda a decidir, con un 95% de confianza, si rechazamos o no una hipótesis cuando comparamos varios grupos con ANOVA.

**2. Los dolores de cabeza con el código:**  
Lo más difícil fue acomodar bien los *DataFrames* con los datos de Loja y limpiar los valores vacíos (`NaN`) sin quedarme sin datos suficientes para la muestra. Además, cuadrar bien los grados de libertad en las pruebas T de Student y entender los resultados de las matrices de Tukey me costó un poco de trabajo mental, pero lo pude resolver usando las funciones vectorizadas de `scipy.stats`.

---

### Competencias Consolidadas

* **Inferencia y estimación:** Capacidad para validar hipótesis y calcular parámetros poblacionales sin perder el rigor matemático.
* **Modelos estocásticos:** Habilidad para simular escenarios y analizar diferencias entre grupos usando ANOVA.
