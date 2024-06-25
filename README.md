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