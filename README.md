# Projeto de Análise de Risco de Crédito

Este projeto, conduzido pelo professor Germano C. Vasconcelos do Centro de Informática da UFPE, tem como objetivo realizar uma análise de satisfação de de passageiros de uma compania aérea utilizando redes neurais e outros classificadores e a base de dados fornecida pela American Express. Os classificadores disponíveis incluem Multilayer Perceptron (MLP), Kolmogorov Arnold Networks (KAN), Random Forest e Gradient Boosting. Serão investigadas diferentes topologias de rede e valores de parâmetros, como número de camadas, unidades intermediárias, taxa de aprendizagem, função de ativação e otimizador. O projeto será desenvolvido em Python, utilizando ferramentas como Github, Keras e Scikit-learn.

## Links Úteis
- Base de dados: [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/data)
- Implementação da rede KAN e orientações: [Github - kailanefelix/kan-redes-neurais](https://github.com/kailanefelix/kan-redes-neurais)

Para mais detalhes, consulte o PDF fornecido.

## 📥 Instalação da KAN - Kolmogorov-Arnold Network

Pykan pode ser instalado via PyPI ou diretamente do GitHub.

### Pré-requisitos

- Python 3.9.7 ou superior
- pip

### Instalação via GitHub

1. Crie e ative um ambiente virtual:

    ```sh
    python -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan do GitHub:

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git
    ```

### Instalação via PyPI

1. Crie e ative um ambiente virtual:

    ```sh
    python -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan do PyPI:

    ```sh
    pip install pykan
    ```

### Opcional, mas Recomendado: Criar um Ambiente Virtual para o Projeto

#### Para quem usa Conda

1. Crie e ative um ambiente virtual:

    ```sh
    conda create --name pykan-env python=3.9.7
    conda activate pykan-env
    ```

2. Instale o Pykan:

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git  # Para instalação via GitHub
    # ou
    pip install pykan  # Para instalação via PyPI
    ```

3. Instale os requirements:

    ```sh
    pip install -r requirements.txt
    ```

#### Para quem não usa Conda

1. Crie e ative um ambiente virtual:

    ```sh
    python -m venv pykan-env
    source pykan-env/bin/activate  # No Windows use `pykan-env\Scripts\activate`
    ```

2. Instale o Pykan:

    ```sh
    pip install git+https://github.com/KindXiaoming/pykan.git  # Para instalação via GitHub
    # ou
    pip install pykan  # Para instalação via PyPI
    ```

3. Instale os requirements:

    ```sh
    pip install -r requirements.txt
    ```