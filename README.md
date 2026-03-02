# Tech Challenge – Fase 04 | Predição de Obesidade

## Visão Geral

Este projeto foi desenvolvido como parte do Tech Challenge – Fase 04 da Pós-Tech em Data Analytics.

O objetivo é construir um modelo de Machine Learning capaz de predizer o nível de obesidade de um paciente com base em variáveis físicas, comportamentais e histórico familiar, auxiliando a equipe médica na tomada de decisão clínica.

A solução contempla todas as etapas da pipeline de dados:

Análise exploratória

Tratamento e engenharia de features

Treinamento e avaliação do modelo

Deploy de aplicação preditiva com Streamlit

Geração de insights analíticos

O modelo atingiu acurácia superior a 75%, atendendo ao requisito mínimo estabelecido no desafio.

## Problema de Negócio

A obesidade é uma condição multifatorial associada a fatores genéticos, comportamentais e ambientais.

A proposta deste projeto é fornecer um sistema preditivo que permita:

Apoiar diagnósticos médicos

Identificar padrões de risco

Contribuir para estratégias preventivas

Apoiar decisões clínicas com base em dados

## Pipeline de Machine Learning

A solução seguiu as seguintes etapas:

Importação e análise da base de dados (obesity.csv)

Tratamento de valores e padronização de variáveis categóricas

Aplicação de One-Hot Encoding

Separação treino/teste (80/20)

Treinamento utilizando Random Forest Classifier

Avaliação por acurácia e análise de desempenho por classe

Serialização do modelo para deploy

## Tecnologias Utilizadas

Python 3.11

Pandas

NumPy

Scikit-learn

Streamlit

Pickle (serialização do modelo)

Git & GitHub

## Aplicação Preditiva (Streamlit)

A aplicação web permite:

Inserção interativa dos dados do paciente

Predição automática do nível de obesidade

Exibição das probabilidades por classe

Apoio visual para interpretação clínica
 
 Link da aplicação:
[https://tech-challenge-fase-04-obesity-jx2aeprbahjhygk9hpszpc.streamlit.app/](https://techchallenge4-qpkzvfz3hxax4qg9wwyika.streamlit.app/)

## Insights Analíticos

A análise exploratória identificou padrões relevantes, como:

Influência do histórico familiar na probabilidade de obesidade

Relação entre baixa atividade física e maior incidência de obesidade tipo II e III

Impacto do consumo frequente de alimentos altamente calóricos

Esses insights podem auxiliar a equipe médica na definição de estratégias preventivas e acompanhamento clínico.

## Estrutura do Repositório
app.py
modelo.pkl.gz
colunas.pkl
Obesity.csv
requirements.txt

## Resultado

O projeto entrega uma solução completa de Data Analytics aplicada à saúde, unindo modelagem preditiva, visualização e deploy em ambiente web.
