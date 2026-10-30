# Custom Models, Layers, and Loss Functions with TensorFlow

Hands-on notebooks for building custom models, layers, loss functions, and callbacks with TensorFlow and Keras. The material follows the [Custom Models, Layers, and Loss Functions with TensorFlow course](https://www.coursera.org/learn/custom-models-layers-loss-functions-with-tensorflow).

## Course outline

| Week | Topic | Notebooks |
| --- | --- | --- |
| 1 | Functional API and multi-output models | [Assignment](week1/w1_assignment.ipynb) · [Functional API](week1/w1_lab1.ipynb) · [Multi-output model](week1/w1_lab2.ipynb) · [Siamese network](week1/w1_lab3.ipynb) |
| 2 | Custom loss functions | [Assignment](week2/w2_assignment.ipynb) · [Huber loss](week2/w2_lab1.ipynb) · [Loss hyperparameters and classes](week2/w2_lab2.ipynb) · [Siamese network](week2/w2_lab3.ipynb) |
| 3 | Custom layers | [Assignment: quadratic layer](week3/w3_assignment.ipynb) · [Lambda layer](week3/w3_lab1.ipynb) · [Custom dense layer](week3/w3_lab2.ipynb) · [Custom activation](week3/w3_lab3.ipynb) |
| 4 | Custom models | [Assignment: VGG network](week4/w4_assignment.ipynb) · [Wide and Deep model](week4/w4_lab1.ipynb) · [ResNet example](week4/w4_lab2.ipynb) |
| 5 | Callbacks | [Callback introduction](week5/w5_lab1.ipynb) · [Custom callbacks](week5/w5_lab2.ipynb) |

## Getting started

1. Clone or download this repository.
2. Open a notebook in JupyterLab, VS Code with the Jupyter extension, or Google Colab. GitHub can preview notebooks in the browser.
3. Install the Python packages used by the notebook you want to run, then execute its cells from top to bottom.

The notebooks use TensorFlow/Keras and, depending on the exercise, packages such as NumPy, pandas, scikit-learn, Matplotlib, and TensorFlow Datasets. This repository does not pin package versions, so an existing course environment may be needed for older notebook APIs.

## Course assignment notes

Assignment notebooks are coursework exercises and contain `TODO` sections. Some assignments import a course-provided `utils.py` file for grading helpers, and some expect datasets to already be available in the notebook environment. Those helper files and datasets are not included here; use the resources supplied with the course when needed.

## Repository structure

```text
week1/  Functional API and multi-output models
week2/  Custom loss functions
week3/  Custom layers
week4/  Custom models
week5/  Callbacks
```

## Credits

Course material by Laurence Moroney, Andrew Ng, and Eddy Shyu. See the [course page](https://www.coursera.org/learn/custom-models-layers-loss-functions-with-tensorflow) for the original course.
