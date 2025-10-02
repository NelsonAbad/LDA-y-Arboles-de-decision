# LDA-y-Arboles-de-decision

Este proyecto compara Linear Discriminant Analysis (LDA) y Árboles de decisión podados para predecir si un hongo es venenoso (1) o comestible (0) usando el dataset clásico de UCI Mushroom.

## Objetivo
- Predecir la variable binaria class_num (0=comestible, 1=venenoso).
- Visualizar la función discriminante de LDA y la partición del árbol en un plano 2D usando dos variables.
- Seleccionar el mejor ccp_alpha para poda mediante LOOCV y evaluar ambos modelos con las métricas vistas en clase.

## Dataset
El conjunto de datos proviene del [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/mushroom).  
Cada observación corresponde a un hongo descrito por atributos categóricos (color, forma, olor, etc.).  

Después de aplicar **One-Hot Encoding**, cada categoría se convirtió en una variable booleana (`0` o `1`).

- **Variable objetivo**: `class_num`  
- **Número de muestras**: 8124  
- **Número de variables después de one-hot**: 138  


[Base de datos](https://github.com/NelsonAbad/LDA-y-Arboles-de-decision/blob/a378dcfd47f17d781af4be3931851f2ea729dd47/mushroom_clean_onehot.csv)

[Reporte en .ipynb](https://github.com/NelsonAbad/LDA-y-Arboles-de-decision/blob/a378dcfd47f17d781af4be3931851f2ea729dd47/A2.2%20LDA%20y%20Arboles%20de%20Decision.ipynb)

[Reporte en HTML](A2.2%20LDA%20y%20Arboles%20de%20Decision.html)
