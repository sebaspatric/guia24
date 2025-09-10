***


# 📘 Guía Cálculo 2024

Hola, comparto una guía con gráficos animados para ilustrar el punto de vista geométrico de los ejercicios de cálculo.  

- **Contenido**: ejercicios de la integral 2024  
- **Despliegue**: Jupyter Book con GitHub Actions  
- **Librería para gráficos**: Plotly en Python  
- **Ventaja**: los gráficos livianos en HTML  

 Sitio web: [tinyurl.com/calculo2024](https://tinyurl.com/calculo2024)

***

##  Cómo ejecutar

Este proyecto está estructurado como un **Jupyter Book**.

### 1. Ver online
- **Libro completo (HTML)**: [Guía Cálculo 2024](https://tinyurl.com/calculo2024)  
- **Ejecutar notebooks interactivos (Binder)**:  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sebaspatric/guia24/main)

### 2. Ejecutar localmente
Clona el repositorio e instala dependencias:

```bash
git clone https://github.com/sebaspatric/guia24.git
cd guia24
pip install -r requirements.txt
````

Luego puedes:

* Abrir los notebooks:

  ```bash
  jupyter lab
  ```
* Reconstruir el libro en HTML:

  ```bash
  jupyter-book build .
  ```

El resultado se genera en la carpeta `_build/html/`.

***
##  Requisitos

Archivo `requirements.txt` mínimo recomendado:

```
jupyter-book
jupyterlab
notebook
numpy
plotly
ipython
scipy
```

***
## 🛠️ Tecnologías usadas

* [Jupyter Book](https://jupyterbook.org/) → organización y despliegue del libro
* [NumPy](https://numpy.org/) → cálculo numérico y arreglos
* [SciPy](https://scipy.org/) → integración y funciones científicas
* [IPython](https://ipython.org/) → ejecución interactiva en notebooks
* [Plotly](https://plotly.com/python/) → gráficos interactivos y animados



***
