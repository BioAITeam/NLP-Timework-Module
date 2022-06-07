# NLP-Timework-Module
El módulo NLP en Timework es un software para la clasificación de tickets de servicio, es decir, requerimientos, solicitudes e incidencias presentadas por clientes al área de soporte técnico de SIGMA Ingeniería S.A. Este SW permite la clasificación automática de los tickets de servicio a partir de la técnica de Aprendizaje Automático (ML); Máquina de vectores de Soporte (SVM) y técnicas de procesamiento de lenguaje Natural (NLP) aplicadas a las bases de datos con las que cuenta la empresa, esta clasificación brinda la categoría perteneciente del ticket de servicio junto con su protocolo de solución a la incidencia presentada para que de esta manera el área de soporte y servicio al cliente brinde una solución al ticket de servicio de una manera más rápida, confiable y segura. Este software está desarrollado en Python con librerías de Sklearn, NLTK, spaCy, TfidfVectorizer que permite tomar el modelo entrenado y guardado y hacer la clasificación automática de texto sobre tickets de servicio presentados en la empresa.
## Citing

Si utiliza nuestro proyecto para su investigación o si encuentra este documento y el repositorio útiles, por favor considere citar el trabajo.

Cite el repositorio: [![DOI](https://zenodo.org/badge/500692485.svg)](https://zenodo.org/badge/latestdoi/500692485)
 

## Carpetas

- **Data** carpeta que contiene las bases de datos entregadas por SIGMA Ingeniería S.A que pertenecen a los datos almacenados en Timework por el área de soporte y servicio al cliente de la empresa.
- **Notebook** carpeta que contiene el algoritmos de SVM aplicados a las bases de datos de Timework.
Este código tiene como entrada la descripición del ticket de servicio o requerimento a registrar en la plataforma.Como salida tiene la categoría sugerida junto con el protocolo de solución del ticket ingresado.

## Pre-requisitos
Este repositorio requiere las siguientes librerías:

- NumPy
- Pandas
- string
- Seaborn
- openpyxl
- scikit-learn
- TfidfVectorizer
- NLTK
- spaCy
- imbalanced-learn
- Matplotlib
- Yellowbrick
- Time

Este SW fue desarrollado en el lenguaje de programación Python 3 (3.8).

## Instalación

Si no usa Google Colab, le recomendamos que use e instale packages de Python dentro de un entorno de Anaconda. Para crear, ejecute el siguiente comando:
```
conda create --name TCC python=3.8
```
y actívelo con el siguiente comando:
```
conda activate TCC
```
Ahora, proceder a instalar los packages
```
pip install ipykernel
```
y visualice el entorno en jupyter
```
python -m ipykernel install --user --name TCC --display-name "TCC"
```
Finalmente, instale las librerías:
```
conda install -c conda-forge matplotlib
```
```
conda install -c anaconda seaborn
```
```
conda install -c anaconda scikit-learn
```
```
conda install -c districtdatalabs yellowbrick
```
```
conda install -c anaconda nltk
```
```
conda install -c conda-forge imbalanced-learn
```
```
conda install -c conda-forge spacy
```
```
python -m spacy download es_core_news_sm
```
```
python -m spacy download en_core_web_sm
```
```
conda install openpyxl
```
```
conda install xlrd
```

## Ejecución
Después de instalar todos los requisitos, debe clonar el repositorio usando:
```
git clone https://github.com/BioAITeam/NLP-Timework-Module.git
```
Si se va a usar colab, cargue la carpeta clonada en la unidad, luego abra la carpeta y ejecute el notebook.

Si se va a usar la computadora, instale:
```
conda install jupyter 
```
Ingrese a la carpeta clonada, luego ingrese a la carpeta y ejecute el notebook.
