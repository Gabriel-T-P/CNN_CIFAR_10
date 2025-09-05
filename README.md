# 🖼️ Classificação de Imagens com Transfer Learning (CIFAR-10)

Este repositório contém um notebook em Python desenvolvido em **Jupyter
Notebook** para treinar e avaliar um modelo de **Deep Learning**
utilizando **Transfer Learning**.\
Foi empregado o modelo **MobileNetV2 pré-treinado no ImageNet**,
adaptado e ajustado para classificar imagens do dataset **CIFAR-10**.

## 📌 Conteúdo

-   Carregamento e exploração do dataset **CIFAR-10** via *TensorFlow
    Datasets*\
-   Construção de pipeline de dados:
    -   Pré-processamento (resize, normalização)
    -   *Data Augmentation* (flip, rotação, zoom)\
-   Definição do modelo:
    -   Uso do **MobileNetV2** pré-treinado (feature extraction)\
    -   Fine-tuning das camadas finais da rede\
-   Treinamento, validação e avaliação no conjunto de teste\
-   Visualização de resultados:
    -   Acurácia obtida no conjunto de teste

## 🚀 Executar no Google Colab

Clique no botão abaixo para abrir o notebook no Google Colab e rodar
diretamente na nuvem:

[![Open In
Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gabriel-T-P/CNN_CIFAR_10/blob/master/CNN_CIFAR_10.ipynb)

## 📊 Dataset

-   **Nome:** CIFAR-10\
-   **Descrição:** 60.000 imagens coloridas (32x32 pixels), distribuídas
    em 10 classes (avião, automóvel, pássaro, gato, veado, cachorro,
    sapo, cavalo, navio e caminhão).\
-   **Fonte:** Disponível via
    [`tensorflow_datasets`](https://www.tensorflow.org/datasets/catalog/cifar10).

## 🛠️ Tecnologias Utilizadas

-   [Python 3](https://www.python.org/)\
-   [TensorFlow 2 / Keras](https://www.tensorflow.org/)\
-   [TensorFlow Datasets](https://www.tensorflow.org/datasets)\

## 📈 Resultados Obtidos

-   **Feature extraction:** acurácia aproximada entre **80--85%** no
    conjunto de teste\
-   **Fine-tuning:** acurácia aproximada entre **88--90%** no conjunto
    de teste

## 🎯 Objetivo

Este projeto tem como objetivo demonstrar o uso de **redes neurais
pré-treinadas** em tarefas de visão computacional, explorando o poder do
**Transfer Learning** para acelerar o desenvolvimento de modelos e
melhorar o desempenho em datasets de tamanho moderado.
