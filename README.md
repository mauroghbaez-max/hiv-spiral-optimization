# hiv-spiral-optimization
Hierarchical Renormalization Framework for HIV cure strategies. Companion code for the paper.
# 🧬 Hierarchical Renormalization Framework for HIV Optimization

Este repositorio contiene la implementación computacional y las simulaciones del marco teórico presentado en el paper:  
**"A Hierarchical Renormalization Framework for Adaptive Optimization in Complex Biological Systems: Application to HIV Cure Strategies"**.

##  Resumen
El proyecto demuestra matemáticamente y computacionalmente cómo un enfoque de **renormalización jerárquica con inicio en caliente (warm-start)** resuelve problemas de optimización NP-difíciles en biología (como la búsqueda de curas para el VIH), evitando la divergencia de errores típica de los métodos tradicionales.

## 📂 Contenido
*   `espiral_convergencia.py`: Script que valida el Teorema de Convergencia del Error (comparación de divergencia vs. estabilización en el piso teórico).
*   `simulacion_vihipharmaco.py`: Script que aplica el marco a un modelo de dinámica viral (Nowak-May) comparando búsqueda aleatoria vs. espiral renormalizada.
*   `convergencia_espiral.png`: Gráfico de validación matemática.
*   `resultado_vihipharmaco.png`: Gráfico de aplicación biológica (reducción de carga viral).

##  Cómo ejecutar
Requisitos: Python 3.x con las librerías `matplotlib` y `numpy`.

```bash
pip install matplotlib numpy
python espiral_convergencia.py
python simulacion_vihipharmaco.py
