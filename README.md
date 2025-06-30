# Network Attack Prediction Model

Este repositório contém o código e os modelos para predição de ataques em redes usando aprendizado de máquina. O modelo é treinado e avaliado com o conjunto de dados **UNSW-NB15**, que inclui uma variedade de tráfego de rede rotulado como normal ou ataque.

## Objetivo

O objetivo deste projeto é desenvolver um modelo de aprendizado de máquina que possa prever a ocorrência de ataques em redes com base em características do tráfego de rede. O modelo é projetado para classificar entradas como "Ataque" ou "Normal", facilitando a detecção precoce de ameaças à segurança.

## Conjunto de Dados

O projeto utiliza o conjunto de dados **UNSW-NB15**, um conjunto de dados popular para a detecção de intrusões em redes. Ele contém dados relacionados ao tráfego de rede com características que incluem:

- Tamanho do pacote
- Tipo de protocolo
- Tempo de resposta
- Número de bytes transmitidos
- E muito mais

O conjunto de dados está disponível no formato CSV e contém vários arquivos com diferentes características de tráfego.

### Estrutura dos Dados

O conjunto de dados contém as seguintes colunas principais:
- **Label**: Indica se o tráfego é normal ou se é um ataque (variados tipos de ataques).
- **Features**: Várias colunas numéricas que descrevem o tráfego da rede (ex: tamanho do pacote, protocolo, etc.).

## Tecnologias Utilizadas

- **Python**: A linguagem principal usada para o desenvolvimento do modelo.
- **Pandas**: Para manipulação de dados.
- **Scikit-learn**: Para treinamento e avaliação do modelo.
- **XGBoost / Random Forest / SVM**: Algoritmos utilizados para modelagem.
- **Matplotlib / Seaborn**: Para visualização de dados e análise de desempenho.

## Instruções para Execução

### Pré-requisitos

- Python 3.x
- Instalar as dependências:

```bash
pip install -r requirements.txt
