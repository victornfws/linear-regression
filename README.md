# Aplicación de Regresión Lineal

Este proyecto es una aplicación de Streamlit que implementa un modelo de regresión lineal. Permite a los usuarios subir archivos CSV con datos, que luego se pueden usar para entrenar el modelo y hacer predicciones.

## Características

- Subir archivos CSV para ingresar datos.
- Entrenar un modelo de regresión lineal con los datos subidos.
- Hacer predicciones basadas en el modelo entrenado.
- Restaurar valores de datos previamente subidos.

## Estructura del Proyecto

- `src/app.py`: Punto de entrada de la aplicación.
- `src/models/linear_regression.py`: Contiene la clase `LinearRegressionModel`.
- `src/utils/data_loader.py`: Función para cargar datos desde archivos CSV.
- `src/utils/preprocessing.py`: Funciones para el preprocesamiento de datos.
- `src/config/settings.py`: Configuraciones de la aplicación.
- `data/.gitkeep`: Mantiene el directorio de datos en el control de versiones.
- `tests/test_model.py`: Pruebas unitarias para el modelo de regresión lineal.
- `requirements.txt`: Lista las dependencias del proyecto.

## Requisitos

Para ejecutar esta aplicación, necesitas instalar las dependencias requeridas. Puedes hacerlo ejecutando:

```
pip install -r requirements.txt
```

## Ejecutando la Aplicación

Para iniciar la aplicación, ejecuta el siguiente comando:

```
streamlit run src/app.py
```

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.