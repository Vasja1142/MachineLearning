# 🤖 Deep Learning Playground with PyTorch 🧪

Этот репозиторий представляет собой коллекцию Jupyter-ноутбуков, документирующих мой путь изучения глубокого обучения с использованием **PyTorch**. Проекты охватывают широкий спектр тем: от основ градиентного спуска до реализации сверточных сетей (CNN) для классификации изображений и использования современных архитектур, таких как ResNet.

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.12%2B-orange.svg)](https://pytorch.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-blueviolet.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-green.svg)](https://matplotlib.org/)

---

## 🌟 Ключевые моменты и изученные концепции

*   **Основы нейронных сетей:**
    *   Реализация и визуализация **градиентного спуска** с нуля.
    *   Построение простых полносвязных сетей для задач регрессии (`sin_prediction`) и классификации (`wine_prediction`).
*   **Сверточные нейронные сети (CNN) для компьютерного зрения:**
    *   Построение классической архитектуры **LeNet-5** для классификации рукописных цифр на датасете **MNIST**.
    *   Применение CNN к более сложному датасету **CIFAR-10**.
*   **Глубокие эксперименты с архитектурой и компонентами:**
    *   Сравнение различных **функций активации** (ReLU vs Tanh).
    *   Анализ влияния **типов пулинга** (Max Pooling vs Average Pooling).
    *   Оценка значительного прироста производительности при использовании **Batch Normalization**.
*   **Применение современных архитектур:**
    *   Реализация и обучение кастомной глубокой CNN (`CIFARNet`) с несколькими сверточными и полносвязными слоями.
    *   Использование и оценка производительности стандартной архитектуры **ResNet-18** на задаче CIFAR-10, что демонстрирует понимание state-of-the-art подходов.
*   **Визуализация результатов:**
    *   Построение графиков точности (Accuracy) и потерь (Loss) для наглядного сравнения результатов различных экспериментов.


---

## 📂 Структура репозитория (Основные ноутбуки)

Этот репозиторий организован как серия модулей, каждый из которых посвящен отдельной теме.

*   `module01_basics.ipynb`: Введение в PyTorch, работа с тензорами.
*   `module02_gradient_descent.ipynb`: Реализация градиентного спуска с нуля.
*   `module03_...ipynb`: Простые нейросетевые модели для регрессии и классификации.
*   `module04_mnist_fc.ipynb`: Решение задачи MNIST с помощью полносвязных сетей.
*   `module05_mnist_conv.ipynb`: Первое применение CNN (архитектура LeNet-5) для MNIST.
*   `module06_mnist_batchnorm.ipynb`: **Ключевой ноутбук!** Проведение экспериментов с активациями, пулингом и Batch Normalization.
*   `module06_cifar.ipynb`: Применение CNN к более сложному датасету CIFAR-10 и сравнение с ResNet-18.
*   `resnet20.ipynb`: Детальное исследование архитектуры ResNet.

---

## 🚀 Начало работы

### Требования
*   Python 3.8+
*   Jupyter Notebook или JupyterLab
*   Основные библиотеки (PyTorch, NumPy, Matplotlib)

### Установка и запуск

1.  **Клонируйте репозиторий:**
    ```bash
    git clone https://github.com/Vasja1142/MachineLearning.git
    cd MachineLearning
    ```

2.  **Создайте виртуальное окружение (рекомендуется):**
    ```bash
    python -m venv venv
    # Windows: venv\Scripts\activate | macOS/Linux: source venv/bin/activate
    ```

3.  **Установите зависимости:**
    ```bash
    pip install torch torchvision numpy matplotlib jupyter
    ```

4.  **Запустите Jupyter:**
    ```bash
    jupyter notebook
    ```
    Или `jupyter lab`. После этого откройте в браузере любой из `.ipynb` файлов и запускайте ячейки.

---

## ✍️ Автор

*   **Vasja1142** ([GitHub профиль](https://github.com/Vasja1142))
