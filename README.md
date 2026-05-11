# seminario-fisica-computacional

Notebooks y scripts del **Seminario de Física Computacional** — una colección de ejercicios que va desde métodos numéricos clásicos hasta redes neuronales aplicadas a problemas de física y de datos.

## Contenido

### Métodos numéricos

| Notebook | Tema |
|---|---|
| [`biseccion.ipynb`](./biseccion.ipynb) | Búsqueda de raíces por bisección. |
| [`Eulerparacaidista.ipynb`](./Eulerparacaidista.ipynb) | Caída de un paracaidista con arrastre cuadrático, resuelta por el método de Euler. |
| [`Taylor Esfera.ipynb`](./Taylor%20Esfera.ipynb) | Aproximaciones de Taylor en geometría esférica. |
| [`GD.ipynb`](./GD.ipynb) | Descenso de gradiente desde cero. |

### Redes neuronales

| Notebook / script | Tema |
|---|---|
| [`Copy of perceptron.ipynb`](./Copy%20of%20perceptron.ipynb) | Perceptrón simple — clasificador lineal entrenado a mano. |
| [`Perceptron Doble.ipynb`](./Perceptron%20Doble.ipynb) | Perceptrón multicapa, backpropagation desde cero. |
| [`cnn_mnist_fotos.py`](./cnn_mnist_fotos.py) | CNN sobre MNIST con Keras/TensorFlow. |
| [`cifar10.py`](./cifar10.py) | CNN sobre CIFAR-10. |

### Aplicaciones

| Notebook | Tema |
|---|---|
| [`CreditCardFraud.ipynb`](./CreditCardFraud.ipynb) | Detección de fraude en tarjetas de crédito sobre dataset desbalanceado. |
| [`Prediccion_Masa_Invariante.ipynb`](./Prediccion_Masa_Invariante.ipynb) | Predicción de la masa invariante de un sistema de dos partículas a partir de variables cinemáticas. |

## Stack

- `numpy`, `matplotlib`, `pandas`, `scikit-learn`
- `tensorflow` / `keras` para los modelos profundos
- Notebooks ejecutables en JupyterLab

## Cómo correrlo

```bash
pip install numpy matplotlib pandas scikit-learn tensorflow jupyterlab
jupyter lab
```
