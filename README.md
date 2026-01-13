# Previsão de Internação de Pacientes com Suspeita de Dengue

Este repositório contém o código e a base de dados para o projeto de previsão da necessidade de internação de pacientes com suspeita de dengue. O modelo utiliza aprendizado supervisionado para classificar se um paciente com suspeita de dengue precisará ser internado ou não, com base em várias características clínicas.

## Descrição do Projeto

O objetivo do projeto é ajudar na antecipação da necessidade de internação de pacientes, contribuindo para uma melhor alocação de recursos hospitalares e atendendo a um problema de saúde pública importante.

A base de dados foi criada a partir de dados públicos do Sistema Único de Saúde (SUS) de 2025 e contém 1000 registros com 17 variáveis, incluindo características demográficas, sintomas e condições médicas pré-existentes dos pacientes.

## Links Importantes

- [Base de Dados SUS (2025)](https://drive.google.com/file/d/1uL2s6hBSBHKLRLoixv3p7Brgc2AQjVJE/view?usp=sharing) - Link para download da base de dados.
- [Vídeo do Projeto no YouTube](https://youtu.be/0lERj_TFsyY) - Link para o vídeo de apresentação do projeto.

## Modelos Utilizados

Foram utilizados dois modelos de aprendizado supervisionado:

1. **Regressão Logística**
2. **Random Forest**

Ambos os modelos foram avaliados em termos de precisão, recall, F1-score e acurácia, com ênfase na análise de dados desbalanceados.

## Bibliotecas Utilizadas

As bibliotecas utilizadas neste projeto são:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`


## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/KellyVasconcellos/previsao-internacao-dengue.git

2. Instale as dependências necessárias:
   Caso não tenha o arquivo requirements.txt, instale as bibliotecas manualmente com o seguinte comando:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   
4. Abra o arquivo Jupyter Notebook no seu ambiente de desenvolvimento:
   ```bash
   jupyter notebook
   
5. Execute as células do notebook para realizar a análise e a previsão.
