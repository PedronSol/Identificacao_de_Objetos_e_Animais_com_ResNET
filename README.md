# Classificação e Identificação de Objetos e Animais via Deep Learning

Autor: Pedro Nelson Nóbrega Monteiro Leite Fonseca

Projeto desenvolvido para a **Lista II** da disciplina **DCA0133 - Aprendizagem de Máquina e Mineração de Dados** do curso de Engenharia de Computação da Universidade Federal do Rio Grande do Norte (UFRN), sob orientação do Prof. Adrião Duarte Dória Neto.

## Visão Geral do Projeto

Este projeto aborda o problema de identificação e classificação automática de objetos e animais em imagens digitais. Foi utilizada a abordagem da Aprendizagem Profunda (Deep Learning) junto com Transfer Learning com ajustes de hiperparâmetros para otimização da acurácia multiclasse

## Tecnologias e Bibliotecas

- **Linguagem:** Python 3.10+
- **Deep Learning Framework:** PyTorch / torchvision
- **Processamento de Imagem:** OpenCV, Pillow, Albumentations
- **Machine Learning & Métricas:** Scikit-Learn, NumPy
- **Visualização:** Matplotlib, Seaborn

## Dataset e Categorias

- **Dataset:** *CIFAR-10 / Custom Animal-Object Dataset*
- **Classes de Animais:** Pássaro, Gato, Cervo, Cão, Sapo, Cavalo.
- **Classes de Objetos:** Avião, Automóvel, Navio, Caminhão.
- **Dimensões das Imagens:** Redimensionamento padronizado para $224 \times 224$ pixels (ou $32 \times 32$ nativo dependendo do experimento).

## Como Executar o Projeto

### 1. Inicializar o Ambiente Virtual
```bash
python3 -m venv .venv

source .venv/bin/activate # No Windows venv\Source\activate
```

### 2. Clonar o Repositório e Instalar Dependências

```bash
git clone [https://github.com/seu-usuario/object-animal-classification-ml.git](https://github.com/seu-usuario/object-animal-classification-ml.git)

cd object-animal-classification-ml

pip install -r requirements.txt
```