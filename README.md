Projeto de Classificação de Doença Cardíaca (Regressão Logística)
Visão geral

Neste projeto, usamos uma base de dados clínica para prever a presença de doença cardíaca (cardio_disease: 0 = não, 1 = sim). O objetivo foi construir um pipeline completo, desde o tratamento inicial até a avaliação do modelo, incluindo ajuste de threshold para priorizar recall.

Base de dados

Arquivo: CARDIO_BASE.csv
Variável alvo (target): cardio_disease
Principais variáveis: idade, gênero, altura, peso, colesterol, glicose, hábitos (tabagismo/álcool), atividade física.

ETAPAS DO PROJETO
1) Carregamento e tratamento dos dados;
2) Análise Exploratória (EDA);
3) Correlação entre as variáveis;
4) Preparação Pré-Modelo;
5) Treinamento e avaliação do modelo;
6) Ajuste de threshold com foco em recall

TECNOLOGIAS PRINCIPAIS
* Jupyter Notebook
* Bibliotecas pandas, numpy, matplotlib, seaborn, scikit-learn e imblearn
   
