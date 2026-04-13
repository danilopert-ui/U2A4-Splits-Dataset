# U2A4 - Splits reproducibles de un dataset abierto 
 
## Dataset 
- **Nombre:** Iris 
- **Fuente:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris) 
- **Autor original:** R.A. Fisher (1936) 
- **Licencia:** CC BY 4.0 
 
## Parametros de la particion 
- Proporcion: 80/20 (train/test) 
- Semilla: 42 
- Criterio: Estratificada por clase 
 
## Estructura del repositorio 
``` 
U2A4-Splits-Dataset/ 
+-- splits/ 
|   +-- train.csv 
|   +-- test.csv 
+-- splits_iris.ipynb 
+-- .gitignore 
+-- README.md 
``` 
 
## Como reproducir 
1. Crear entorno virtual: `python -m venv venv` 
2. Activar: `venv\Scripts\activate` 
3. Instalar dependencias: `pip install pandas scikit-learn` 
4. Ejecutar: `python splits_iris.ipynb` 
5. Los archivos se generan en la carpeta /splits 
