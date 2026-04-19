# 🔍 Tratamento de Dados e Imputação com k-NN

## Objetivo
Pipeline completo de análise de dados aplicado a um dataset de corrupção
e fraude económica — desde a limpeza e tratamento inicial até à imputação
de valores omissos com o algoritmo k-NN e avaliação do seu desempenho.

## Ferramentas e tecnologias
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook

## Dataset
Dataset simulado de casos de corrupção e fraude económica, construído
intencionalmente com erros, inconsistências e falhas de formatação
para fins de análise e limpeza de dados.

## Estrutura do projeto

### Parte 1 — Tratamento e limpeza de dados
- Inspeção inicial do dataset
- Correção de formatos e tipos de variáveis
- Identificação e tratamento de inconsistências
- Análise da qualidade dos dados por dimensão

### Parte 2 — Imputação com k-NN
- Seleção manual de variáveis adequadas ao algoritmo
- Geração artificial de valores omissos (10%, 20%, 30%)
- Testagem de múltiplos valores de k (3, 5, 7, 10, 15, 20)
- Avaliação do desempenho com MAE e RMSE

## Resultados
- Valor ótimo encontrado: **k=5**
- k=5 mostrou o melhor equilíbrio entre precisão e generalização
- Avaliação consistente nos três cenários de omissão testados

## Autores
Projeto desenvolvido em grupo no âmbito do Mestrado em Análise de Dados.
- Joana Tomé
- Gonçalo Conceição
- Pedro Cebolo
