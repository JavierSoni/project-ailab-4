# Clasificación de Células Sanguíneas

## 🎯 Objetivo
Regresion de la temperatura en funcion de la energia que se consume y las condiciones.

## 🧬 Dataset
- **Etiquetas**: Archivo `powerconsumption.csv` que contiene la temperatura y otras variables de aires acondicionados y la energia que estan consumiendo

## 🧠 Arquitectura del Modelo
 es un modelo de LSTM

## 🧪 Métricas de Evaluación
- MAE
- MSE
- RMSE

## 📈 Resultados
MSE: 0.0097
MAE: 0.0799
RMSE: 0.0984

## 📂 Estructura del Proyecto
- `notebooks/`: Contiene los notebooks para preprocesamiento, entrenamiento y evaluación.
- `data/`: Contiene las informacion.
- `artifacts/`: Almacena el modelo entrenado.
- `mlruns/`: Directorio generado por MLflow para el seguimiento de experimentos.

## 🛠️ Requisitos
Ver `requirements.txt` para las dependencias necesarias.
