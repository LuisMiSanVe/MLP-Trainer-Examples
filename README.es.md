> [Ver en ingles/See in english](https://github.com/LuisMiSanVe/MLP-Trainer-Examples/blob/main/README.md)
# 🧠 Ejemplos de Entrenador de MLP
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![image](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)](https://code.visualstudio.com/)
[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

Un Jupyter Notebook con tres Scripts de Python que entrenan Modelos de MLP con diferentes tipos de datos, funciones y resultados.

## 📋 Prerequisitos
Antes que nada, necesitas poder abrir/ejecutar estos scripts, para ello, puedes o bien usar la consola o un IDE como [Visual Studio Code](https://code.visualstudio.com/). Estos son los pasos para hacerlo de ambas maneras.
- **Consola**:
  Instala la ultima version de [Python](https://www.python.org/).
  Entonces, abre un terminal e instala Jupyter Notebook con el siguiente comando:
  ```
  pip install jupyter
  ```
  Si falla o tienes una version diferente de Python:
  ```
  py -m pip install jupyter
  ```
- **VS Code**:
  Ve al Marketplace e instala las extensiones de [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) y [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter).

Para ejecutar los scripts, tanto en consola como en un IDE, **debes** instalar las siguientes dependencias en una terminal:
```
pip install torch matplotlib numpy
```
Si falla o tienes una version diferente de Python:
```
py -m pip install torch matplotlib numpy
```

## 🛠️ Instalación
Abre el Jupyter Notebook con VS Code o con su aplicación web ejecutando este comando:
```
jupyter notebook
```
Si falla o tienes una version diferente de Python:
```
py -m jupyter notebook
```
Entonces, la app se abrirá sola en tu navegador por defecto.

## 🚀 Explicación de uso del proyecto
Sigue la guía y ejecuta las Células de Código Python en el Jupyter Notebook para entrenar y ver los resultados de los Modelos MLP.

Los tres scripts generan un Modelo MLP cada uno con sus funcionalidades y tipos de datos.

Para probar a cambiar los resultados, ajusta los parametros del Modelo y los ajustes del entrenamiento (marcado en los comentarios).

Su funcionalidad está explicada en cada Script de Python.

## 💻 Tecnologías usadas
- Lenguaje de programación: [Python](https://www.python.org/) (3.13.2)
- Librerías:
  - [torch](https://pypi.org/project/torch/) (2.6.0)
  - [numpy](https://numpy.org/) (2.2.0)
  - [matplotlib](https://matplotlib.org/) (3.10)
- Otros:
  - [Jupyter](https://jupyter.org/)
  - [VS Code Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
  - [VS Code Jupyter Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- IDE Recomendado: [VS Code](https://code.visualstudio.com/)
