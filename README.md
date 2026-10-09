# Math for ML

Notebooks de Jupyter con las matemáticas que sostienen el Machine Learning y el Deep Learning: álgebra lineal, sistemas de ecuaciones, cálculo vectorial y estadística.

## Enfoque

Cada notebook combina la teoría con su notación formal, implementaciones en NumPy y SymPy, y visualizaciones en 2D y 3D. Además, conecta cada concepto con su uso concreto en Machine Learning.

Las notebooks se guardan con sus resultados ejecutados, así que se pueden leer directamente en GitHub.

## Notebooks

Las notebooks están numeradas en el orden sugerido de estudio. Álgebra lineal y sistemas de ecuaciones se complementan; estadística se puede leer de forma independiente.

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [Álgebra Lineal](notebooks/01-algebra-lineal.ipynb) | Vectores, matrices, sistemas de ecuaciones, espacios vectoriales, rango y nulidad, valores y vectores propios, descomposiciones matriciales, matrices especiales, tensores y aplicaciones directas en ML/DL |
| 02 | [Sistemas de Ecuaciones Lineales](notebooks/02-sistemas-ecuaciones-lineales.ipynb) | Interpretación geométrica en 2D y 3D, teorema de Rouché-Capelli, espacio nulo, determinante, Gauss-Jordan, Cramer, inversión de matrices, análisis nodal de circuitos y mínimos cuadrados para regresión lineal |
| 03 | [Cálculo Vectorial](notebooks/03-calculo-vectorial.ipynb) | Funciones escalares, campos vectoriales, curvas y superficies paramétricas, gradiente, divergencia, rotacional, laplaciano, integrales de línea, superficie y volumen, y los teoremas de Green, Stokes y Gauss |
| 04 | [Estadística Fundamental](notebooks/04-estadistica-fundamental.ipynb) | Tendencia central, dispersión, asimetría y curtosis, distribuciones, covarianza y correlación, ley de los grandes números, teorema del límite central, intervalos de confianza, pruebas de hipótesis, bootstrap y paradoja de Simpson |

## Estructura

```
.
├── notebooks/
├── requirements.txt
└── README.md
```

## Cómo usar

Requisitos: Python 3.10 o superior.

```bash
git clone https://github.com/astorress/math-for-ml.git
cd math-for-ml

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt

jupyter notebook
```

Abre cualquier notebook de la carpeta `notebooks/` y ejecuta las celdas en orden.

También puedes abrir cualquier notebook en [Google Colab](https://colab.research.google.com): *File → Open notebook → GitHub* y pega la URL del repositorio.

### Notas

- **Visualización interactiva (02):** usa `ipywidgets`, así que solo funciona al ejecutar la notebook en Jupyter o Colab, no en la vista previa de GitHub.

## Repositorios relacionados

- [algoritmos-from-scratch](https://github.com/astorress/algoritmos-from-scratch): complejidad, búsqueda, ordenamiento, grafos, optimización y computación cuántica desde cero.
- [ml-from-scratch](https://github.com/astorress/ml-from-scratch): Machine Learning, Deep Learning y Reinforcement Learning implementados desde cero.
- [data-science-lab](https://github.com/astorress/data-science-lab): casos prácticos de data science aplicado con librerías.
