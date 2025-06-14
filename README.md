# TOWARDS SCALABLE GEOMETRIC OPTIMIZATION

Este repositorio forma parte de una propuesta de investigación cuyo objetivo no es únicamente presentar un nuevo algoritmo de optimización, sino ofrecer un marco conceptual basado en estructuras geométricas, proporciones relativas y retroalimentación funcional como guías para la mejora. 

El enfoque propuesto parte de una idea simple pero poderosa: **comprender el espacio de búsqueda desde una sola solución** y explorar su estructura mediante distancias (L1), pesos relativos y vectores de dirección aleatoria, sin depender de información previa del problema.

## 🧠 Motivación

Muchos algoritmos actuales ofrecen mejoras en rendimiento, pero pocas veces se cuestiona o expone con claridad el fundamento teórico detrás de sus decisiones estructurales. Este proyecto apuesta por construir *desde lo más simple* (una sola solución) y observar cómo pequeñas ideas, inspiradas en conceptos como series geométricas, medias armónicas o proporciones, pueden guiar procesos robustos de optimización incluso en alta dimensionalidad.

## 📂 Contenido del repositorio

- 📊 **Datos experimentales en formato `.npy`**  
  Resultados obtenidos de distintas funciones benchmark (Sphere, Qing, Schwefel, etc.) bajo diferentes estrategias de desplazamiento (fijo vs. adaptativo).
  
- 📈 **Scripts de visualización (Jupyter Notebooks)**  
  Permiten observar y comparar gráficamente las curvas de convergencia. Incluye visualización en escala lineal y logarítmica.

- 📌 **Referencias a funciones benchmark**  
  Se utiliza `Mealpy` y `Opfunu` como herramientas open source para garantizar la reproducibilidad.

## 📌 Filosofía del proyecto

Este repositorio apuesta por la ciencia abierta. No pretende competir en rendimiento numérico con algoritmos tradicionales, sino abrir nuevos caminos teóricos y experimentales que puedan ser explorados por la comunidad científica.

## 🔁 Reproducibilidad

Todos los datos y scripts serán compartidos progresivamente a medida que se completan las pruebas. Si deseas contribuir o replicar resultados, encontrarás instrucciones básicas para cargar y visualizar los archivos `.npy`.

## 📬 Contacto

Este trabajo es parte de una investigación independiente. Si te interesa colaborar, analizar los datos, o apoyar este esfuerzo mediante crowdfunding, puedes escribir a:

> 📧 misa.hdez97@gmail.com
