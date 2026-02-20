# Análise Comparativa de Redes Neurais para Previsão Diária de Demanda Elétrica no Sistema Interligado Nacional

Este repositório contém os códigos desenvolvidos para a dissertação de mestrado cujo objetivo é comparar diferentes arquiteturas de Redes Neurais Artificiais (RNAs) aplicadas à previsão multihorária (24 horas do dia à frente) da demanda elétrica no Sistema Interligado Nacional (SIN).

## Objetivo do Trabalho

Avaliar e comparar o desempenho das seguintes arquiteturas:

- MLP (Multi-Layer Perceptron)
- Conv1D (Convolutional Neural Network)
- LSTM (Long Short-Term Memory)
- ESN (Echo State Network)

A comparação foi realizada sob condições experimentais controladas, garantindo:

- Mesmo conjunto de dados
- Mesmo horizonte de previsão
- Mesma estratégia de divisão treino/teste
- Métricas de avaliação padronizadas

O foco é identificar diferenças de desempenho, robustez e custo computacional entre as arquiteturas, além de analisar entradas e hiperparâmetros que impactam positivamente o desempenho dessas redes.

## Estrutura do Repositório

├── N/

│   ├── Dados/

│   ├── Preprocessamento/

│   ├── Treinamento/

│   └── Teste/

│

├── NE/

│   ├── Dados/

│   ├── Preprocessamento/

│   ├── Treinamento/

│   └── Teste/

│

├── S/

│   ├── Dados/

│   ├── Preprocessamento/

│   ├── Treinamento/

│   └── Teste/

│

├── SECO/

│   ├── Dados/

│   ├── Preprocessamento/

│   ├── Treinamento/

│   └── Teste/

├── requirements.txt

└── README.md


## Requisitos

Python 3.12.3

Bibliotecas principais:
- matplotlib               3.10.6
- numpy                    2.1.2
- pandas                   2.3.3
- pytorch-esn              1.2.5
- scikit-learn             1.8.0
- scipy                    1.16.3
- seaborn                  0.13.2
- torch                    2.8.0+cu126
- torchvision              0.23.0+cu126

Instale as dependencia utilizando:
pip install -r requirements.txt

## Dados

A base de dados utilizada é disponibilizada pelo Operado Nacional do Sistema Elétrico, por meio da plataforma SINtegre:
https://sintegre.ons.org.br

Os dados são utilizados como entrada para o modelo PrevCargaDESSEM

## 📚 Referência

Se este repositório for utilizado em pesquisas acadêmicas, por favor cite:

Em breve
