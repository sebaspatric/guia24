# 📘 Guía Cálculo 2024

Hola, comparto una guía con gráficos animados para ilustrar el punto de vista geométrico de los ejercicios de cálculo.  

- **Contenido**: ejercicios de Cálculo 
- **Despliegue**: Jupyter Book con GitHub Actions  
- **Librería para gráficos**: Plotly en Python  
- **Ventaja**: los gráficos quedan livianos en HTML  

👉 Sitio web: [tinyurl.com/calculo2024](https://tinyurl.com/calculo2024)

***

## ▶️ Cómo ejecutar

Este proyecto no tiene `main.py`, ya que está estructurado como un **Jupyter Book**.

### 1. Ver online
- **Libro completo (HTML estático)**: [Guía Cálculo 2024](https://tinyurl.com/calculo2024)  
- **Ejecutar notebooks interactivos (Binder)**:  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sebaspatric/guia24/main)

### 2. Abrir notebooks en Binder

Cuando se abre Binder, se carga un **entorno de JupyterLab** en el navegador.  
El aspecto es similar a este ejemplo:  

🔗 `https://hub.2i2c.mybinder.org/user/sebaspatric-guia24-.../lab`  

Allí verás en el panel lateral izquierdo el explorador de archivos del repositorio.  

Los notebooks de esta guía se encuentran con nombres como:  

- `Calculo2024ej1.ipynb`  
- `Calculo2024ej2.ipynb`  
- `Calculo2024ej3.ipynb`  
- ...  

👩‍💻 **Para abrirlos**:  
1. Haz clic en el archivo que quieras (ej. `Calculo2024ej1.ipynb`).  
2. Se abrirá en una pestaña dentro de JupyterLab.  
3. Ejecuta las celdas con **Shift + Enter** o usando el menú `Run ▶`.  

***

### 3. Ejecutar localmente
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

## ⚙️ Requisitos

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
