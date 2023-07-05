# Predicción de Comentarios en Publicaciones de Blog

## Descripción del Proyecto

Este repositorio contiene un proyecto de aprendizaje automático que tiene como objetivo predecir el número de comentarios que una publicación de blog recibirá en las próximas 24 horas. Utilizamos un conjunto de datos que proviene de publicaciones de blog, y a partir de la información disponible en el momento de la publicación, intentamos predecir cuántos comentarios recibirá la publicación en un periodo de 24 horas.

El conjunto de datos incluye características como el número total de comentarios antes de un tiempo base, el número de comentarios en las últimas 24 horas antes del tiempo base, la longitud de la publicación, entre otras.

## Dependencias

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib


## Estructura del Proyecto

- `datos/` - Directorio que contiene los archivos CSV del conjunto de datos.
- `prediccion_comentarios_blog.ipynb` - Notebook que contiene el código principal del proyecto.
- `README.md` - Archivo de documentación con información sobre el proyecto.

## Detalles de Implementación

El proyecto incluye la experimentación con varios modelos de regresión para predecir el número de comentarios. Los modelos incluyen:

- Regresión Lineal
- Ridge
- Lasso
- ElasticNet
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor
- Red Neuronal

Se realizó un preprocesamiento de los datos, incluido el escalado de características. Luego, se entrenó cada modelo utilizando el conjunto de entrenamiento y se evaluó su rendimiento utilizando métricas como el error cuadrático medio y el R2 score. Además, se visualizaron los resultados mediante gráficos.

## Contribuciones

Las contribuciones a este proyecto son bienvenidas. Si encuentras algún error o tienes alguna sugerencia de mejora, no dudes en abrir un Issue o enviar un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulte el archivo [LICENSE](LICENSE) para obtener más detalles.
