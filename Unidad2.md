# Unidad 2: Modelos Continuos e Inferencia Estadística

Este apartado recopila todo el material práctico, las evaluaciones y la sustentación del trabajo autónomo de la segunda unidad. Aquí se documenta el análisis de distribuciones teóricas, los métodos de estimación de parámetros y la ejecución de contrastes de hipótesis orientados a nuestro proyecto de investigación.

### Repositorio de Prácticas de Laboratorio (APEs)

A continuación se presenta el catálogo de experimentos computacionales. Para revisar el código fuente directamente en la interfaz de GitHub, basta con seleccionar el enlace de cada cuaderno:

* **[Laboratorio 06: Modelos de Probabilidad Continua](./APE06.ipynb)**  
  Construcción analítica y uso práctico de funciones de densidad de probabilidad continua en diferentes escenarios de estudio.

* **[Laboratorio 07: Simulaciones Estocásticas y TLC](./APE007.ipynb)**  
  Comprobación computacional de los postulados del Teorema del Límite Central a través de experimentación aleatoria.

* **[Laboratorio 08: Estimación y Rangos de Confianza](./APE08.ipynb)**  
  Cálculo de estimadores poblacionales y construcción de rangos de certidumbre empleando los modelos teóricos Z y T de Student.

* **[Laboratorio 09: Contrastes de Hipótesis Paramétricas](./APE09.ipynb)**  
  Diseño y ejecución de validaciones estadísticas (estadísticos Z y T) integrando la interpretación analítica profunda del P-valor.

* **[Laboratorio 10: Inferencia Comparativa Multigrupo](./APE010.ipynb)**  
  Desarrollo de análisis de varianza unifactorial (ANOVA) complementado con contrastes múltiples de Tukey (Post-Hoc) para aislar diferencias específicas.

---

### Examen Práctico y Archivos de Origen

* **[Prueba de Síntesis II: Evaluación Computacional](./ExamenII_ArletteQuezada.ipynb)**  
  Aplicación integral de técnicas inferenciales y modelos matemáticos para dar solución a casos prácticos sobre muestras de datos auténticas.

* **[Conjunto de Datos: Registro Ambiental de Loja](./Dataset_hogares_ambiental_2025.csv)**  
  Archivo crudo de información que sirvió como pilar fundamental para toda la depuración, análisis y modelado algorítmico en el entorno de Python.

---

### Sustentación del Componente Autónomo

* **[Registro Audiovisual de Defensa Técnica](https://drive.google.com/file/d/1IuH6-SREl6r1NkJoXJtFIlHAy-vx2Pou/view?usp=drive_link)**  
  Presentación oral detallada donde se argumenta la selección de métodos paramétricos tras validar la normalidad mediante Shapiro-Wilk. Incluye un recorrido guiado por el código y la lectura crítica del P-valor para fundamentar las conclusiones finales.

---

### Bitácora Reflexiva (Componente 3)

**1. Avances Conceptuales en Inferencia:**  
El hito fundamental de esta fase fue superar el análisis puramente descriptivo para adentrarme en técnicas inferenciales formales. Logré sistematizar, a través de rutinas en Python, la validación de condiciones previas ineludibles, como la comprobación de normalidad vía Shapiro-Wilk. Adicionalmente, interioricé el significado analítico del P-valor como herramienta definitiva para descartar o mantener hipótesis nulas, garantizando un margen de certeza del 95% en los modelos de comparación poblacional (ANOVA).

**2. Obstáculos Computacionales Resueltos:**  
El desafío de programación más complejo consistió en moldear los *DataFrames* que contenían la información de Loja, implementando una limpieza y filtrado de valores ausentes (`NaN`) que no sacrificara el volumen representativo de la muestra. Por otro lado, parametrizar adecuadamente los grados de libertad en los tests T para conjuntos independientes y procesar los resultados matriciales de las pruebas de Tukey demandaron un alto grado de abstracción lógica. Estos escollos se superaron exprimiendo al máximo las capacidades vectoriales de la librería `scipy.stats`.

---

### Habilidades Adquiridas

* **Estimación y Contraste:** Destreza comprobada para proponer, verificar y concluir sobre hipótesis estadísticas, además de calcular métricas poblacionales apoyadas en fundamentos matemáticos sólidos.
* **Análisis de Varianza y Simulación:** Aptitud técnica para recrear escenarios probabilísticos y cuantificar las diferencias significativas entre múltiples grupos utilizando metodologías ANOVA.
