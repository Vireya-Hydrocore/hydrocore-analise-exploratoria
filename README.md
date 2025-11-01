📊 Análise Exploratória de Dados – Comportamento de Usuários
📋 Descrição do Projeto

Este notebook tem como objetivo realizar uma análise exploratória de dados (ETA) para compreender padrões de comportamento dos usuários em um aplicativo móvel.
A análise busca identificar tendências, anomalias e relações entre variáveis, apoiando decisões baseadas em dados e promovendo melhorias em UX, produto e engajamento.

Durante a exploração, são abordados tópicos como:

Distribuição e qualidade dos dados

Comportamento e frequência de uso do app

Correlação entre variáveis

Identificação de outliers e inconsistências

🎯 Objetivo

O principal objetivo é explorar os dados coletados e gerar insights descritivos e visuais sobre o publico alvo respondendo perguntas como:

Quais são as variáveis mais relevantes para o comportamento do usuário?

Existem padrões sazonais ou horários de maior atividade?

Há diferenças de comportamento entre grupos de usuários (ex: dispositivos, regiões)?

Existem outliers ou inconsistências que influenciam as métricas principais?

🧠 Contexto e Coleta de Dados

Os dados analisados foram extraídos do site: https://dados.gov.br/dados/conjuntos-dados/sisagua-tratamento-de-agua?utm_sourc

Os dados passaram por etapas de limpeza, tratamento de valores ausentes, padronização e geração de novas variáveis derivadas.

🧩 Estrutura do Notebook

O notebook analise.ipynb está estruturado da seguinte forma:

Importação das bibliotecas

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns


Carregamento dos dados

df = pd.read_csv("dados_site.csv")
df.head()


Análise inicial e limpeza

Verificação de valores nulos e duplicados

Padronização de tipos de dados

Criação de novas colunas (ex: hora, dia da semana, mês)

Análise descritiva

Médias, medianas, moda, desvio padrão

Distribuições de frequência

Agrupamentos e contagens por categoria

Visualizações

Histogramas e boxplots

Gráficos de barras e pizza

Mapas de calor de correlação

Séries temporais (uso ao longo do tempo)

Insights e conclusões principais

⚙️ Requisitos

Antes de executar, instale as bibliotecas necessárias:

pip install pandas numpy matplotlib seaborn jupyter

▶️ Como Executar

Abra o arquivo analise.ipynb no Jupyter Notebook ou no VSCode com a extensão Jupyter.

Execute as células em sequência.

As tabelas, gráficos e insights aparecerão diretamente nas saídas das células.

📈 Interpretação dos Resultados

A análise exploratória permite identificar:

Padrões de comportamento de usuários;

Anomalias que indicam problemas de coleta ou inconsistências;

Correlação entre variáveis relevantes;

Tendências temporais e sazonais.

Essas descobertas servem como base para hipóteses em etapas futuras de modelagem estatística ou machine learning.

🧾 Conclusão

O notebook fornece uma visão ampla e detalhada do conjunto de dados, permitindo compreensão profunda do comportamento do usuário.
A partir dessa análise, é possível embasar decisões estratégicas de design, marketing e produto com evidências quantitativas e visuais.

📚 Tecnologias Utilizadas

🐍 Python 3.x

📘 Pandas

🔢 NumPy

📊 Matplotlib

🌈 Seaborn

📓 Jupyter Notebook

✍️ Autor

Guilherme Trindade
🎓 Estudante do Instituto Germinare Tech
📅 2025
