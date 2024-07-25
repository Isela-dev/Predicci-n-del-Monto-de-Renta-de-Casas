# 📈 Predicción del Monto de Renta de Casas

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![Libraries](https://img.shields.io/badge/Libraries-pandas%20%7C%20scikit--learn%20%7C%20numpy%20%7C%20matplotlib%20%7C%20plotly-brightgreen.svg)



## 📚 Descripción del Proyecto

Este proyecto utiliza técnicas de **regresión lineal** para predecir el monto de renta de casas basándose en sus características. El objetivo es construir un modelo que pueda estimar con precisión cuánto debería costar una casa para alquilar, dado un conjunto de atributos específicos.

## 📊 Datos Utilizados

El conjunto de datos `houses_to_rent.csv` contiene información sobre diferentes casas en alquiler, con las siguientes características:
- **Área (area)**: Tamaño de la casa en metros cuadrados.
- **Número de Habitaciones (rooms)**: Cantidad de habitaciones en la casa.
- **Número de Baños (bathrooms)**: Cantidad de baños en la casa.
- **Espacios de Estacionamiento (parking_spaces)**: Cantidad de espacios disponibles para estacionamiento.
- **Piso (floor)**: El piso en el que se encuentra la casa.
- **Renta (rent_amount)**: El monto de renta mensual en moneda local.

## 🔍 Metodología

1. **Preparación de Datos**:
   - **Carga y Limpieza**: Se carga el conjunto de datos y se eliminan las filas con valores nulos en las características relevantes.
   - **Selección de Características**: Se eligen las características numéricas para el análisis, excluyendo datos no numéricos o irrelevantes.

2. **División del Conjunto de Datos**:
   - Se divide el conjunto de datos en dos partes: un conjunto de entrenamiento (80%) y un conjunto de prueba (20%).

3. **Entrenamiento del Modelo**:
   - Se entrena un modelo de **regresión lineal** utilizando el conjunto de entrenamiento para aprender la relación entre las características de las casas y el monto de renta.

4. **Evaluación del Modelo**:
   - Se realizan predicciones sobre el conjunto de prueba.
   - Se evalúa el rendimiento del modelo mediante métricas como el **Error Cuadrático Medio (MSE)** y el **Coeficiente de Determinación (R^2)**.

5. **Visualización**:
   - Se generan gráficos para visualizar la relación entre los valores reales y las predicciones del modelo.
   - Se utiliza un **mapa de colores** para mostrar el error absoluto en las predicciones y hacer la visualización más informativa.
   - Se ofrece una versión **interactiva** del gráfico utilizando `plotly` para una exploración más profunda.

6. **Testing de QA**:
   - Se implementan pruebas para asegurar la calidad del modelo, incluyendo la verificación de valores nulos, la correcta división de datos, la ausencia de valores negativos en la renta, y la evaluación de la precisión del modelo.

## 🏆 Resultados

- **Error Cuadrático Medio (MSE)**: Indica la diferencia promedio entre los valores reales y las predicciones del modelo. Un valor más bajo sugiere un mejor ajuste del modelo.
- **Coeficiente de Determinación (R^2)**: Mide la proporción de la variabilidad en la variable objetivo que es explicada por el modelo. Un valor más alto indica un mejor rendimiento del modelo.

## 🚀 Cómo Ejecutar el Proyecto

1. **Instalar Dependencias**:
   ```bash
   pip install pandas scikit-learn numpy matplotlib tabulate plotly
Ejecutar el Script:

bash
Copiar código
python nombre_del_script.py
Explorar Resultados:

Los gráficos generados se mostrarán automáticamente.
Revisa el archivo de resultados para la evaluación de los tests de QA.
📄 Documentación Adicional
Para más detalles sobre el proceso y los resultados, revisa los notebooks del proyecto.

📫 Contacto
Si tienes alguna pregunta o comentario sobre el proyecto, no dudes en contactarme en https://www.linkedin.com/in/isela-l-garc%C3%ADa-tech-ia-data-machinelearning/


Memoria actualizada
Claro, aquí tienes un ejemplo de archivo README.md para tu proyecto, con badges y emojis incluidos para hacerlo más atractivo:

markdown
Copiar código
# 📈 Predicción del Monto de Renta de Casas

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![Libraries](https://img.shields.io/badge/Libraries-pandas%20%7C%20scikit--learn%20%7C%20numpy%20%7C%20matplotlib%20%7C%20plotly-brightgreen.svg)

## 📚 Descripción del Proyecto

Este proyecto utiliza técnicas de **regresión lineal** para predecir el monto de renta de casas basándose en sus características. El objetivo es construir un modelo que pueda estimar con precisión cuánto debería costar una casa para alquilar, dado un conjunto de atributos específicos.

## 📊 Datos Utilizados

El conjunto de datos `houses_to_rent.csv` contiene información sobre diferentes casas en alquiler, con las siguientes características:
- **Área (area)**: Tamaño de la casa en metros cuadrados.
- **Número de Habitaciones (rooms)**: Cantidad de habitaciones en la casa.
- **Número de Baños (bathrooms)**: Cantidad de baños en la casa.
- **Espacios de Estacionamiento (parking_spaces)**: Cantidad de espacios disponibles para estacionamiento.
- **Piso (floor)**: El piso en el que se encuentra la casa.
- **Renta (rent_amount)**: El monto de renta mensual en moneda local.

## 🔍 Metodología

1. **Preparación de Datos**:
   - **Carga y Limpieza**: Se carga el conjunto de datos y se eliminan las filas con valores nulos en las características relevantes.
   - **Selección de Características**: Se eligen las características numéricas para el análisis, excluyendo datos no numéricos o irrelevantes.

2. **División del Conjunto de Datos**:
   - Se divide el conjunto de datos en dos partes: un conjunto de entrenamiento (80%) y un conjunto de prueba (20%).

3. **Entrenamiento del Modelo**:
   - Se entrena un modelo de **regresión lineal** utilizando el conjunto de entrenamiento para aprender la relación entre las características de las casas y el monto de renta.

4. **Evaluación del Modelo**:
   - Se realizan predicciones sobre el conjunto de prueba.
   - Se evalúa el rendimiento del modelo mediante métricas como el **Error Cuadrático Medio (MSE)** y el **Coeficiente de Determinación (R^2)**.

5. **Visualización**:
   - Se generan gráficos para visualizar la relación entre los valores reales y las predicciones del modelo.
   - Se utiliza un **mapa de colores** para mostrar el error absoluto en las predicciones y hacer la visualización más informativa.
   - Se ofrece una versión **interactiva** del gráfico utilizando `plotly` para una exploración más profunda.

6. **Testing de QA**:
   - Se implementan pruebas para asegurar la calidad del modelo, incluyendo la verificación de valores nulos, la correcta división de datos, la ausencia de valores negativos en la renta, y la evaluación de la precisión del modelo.

## 🏆 Resultados

- **Error Cuadrático Medio (MSE)**: Indica la diferencia promedio entre los valores reales y las predicciones del modelo. Un valor más bajo sugiere un mejor ajuste del modelo.
- **Coeficiente de Determinación (R^2)**: Mide la proporción de la variabilidad en la variable objetivo que es explicada por el modelo. Un valor más alto indica un mejor rendimiento del modelo.

## 🚀 Cómo Ejecutar el Proyecto

1. **Instalar Dependencias**:
   ```bash
   pip install pandas scikit-learn numpy matplotlib tabulate plotly
Ejecutar el Script:

bash
Copiar código
python nombre_del_script.py
Explorar Resultados:

Los gráficos generados se mostrarán automáticamente.
Revisa el archivo de resultados para la evaluación de los tests de QA.
📄 Documentación Adicional
Para más detalles sobre el proceso y los resultados, revisa los notebooks del proyecto.

📫 Contacto
Si tienes alguna pregunta o comentario sobre el proyecto, no dudes en contactarme en tu-email@example.com.

¡Gracias por revisar el proyecto! 😊


### Explicación de los Componentes:

- **Badges**: Proporcionan información rápida sobre el estado del proyecto, como la versión de Python y las bibliotecas utilizadas.
- **Emojis**: Añaden un toque visual y hacen que el README sea más atractivo.
- **Descripción del Proyecto**: Ofrece una visión general clara del propósito y los datos del proyecto.
- **Metodología**: Describe los pasos que se siguieron para desarrollar el proyecto.
- **Resultados**: Presenta las métricas clave que demuestran el rendimiento del modelo.
- **Cómo Ejecutar el Proyecto**: Proporciona instrucciones para que otros puedan replicar tu trabajo.
- **Documentación Adicional**: Enlaza a otros documentos relevantes o notebooks, si están disponibles.
- **Contacto**: Ofrece una forma de contactarte para preguntas o comentarios.

Puedes ajustar los detalles según tus necesidades y el público al que te diriges. ¡Buena suerte con tu proyecto! 🚀
