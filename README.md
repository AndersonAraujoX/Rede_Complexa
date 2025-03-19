# Análise de Redes Complexas

Este repositório contém a implementação de diversas métricas e algoritmos para análise de redes complexas, incluindo:

* **Métricas Clássicas:**
   * Vulnerabilidade 
   * Coeficiente Cíclico 
   * Coeficiente de Rich-Club 
   * Distribuição de Graus e Correlações 
   * Graus de Bipartividade 
   * Informações de Busca, Entropia de Estrada e Entropia de Saída
   * Espectro da Matriz de Adjacência 
   * Centralidade de Intermediação 
   * Maximização da Modularidade 
* **Subgrafos e Motivos em Redes Ponderadas:**
   * Intensidade de um Subgrafo 
   * Coerência 
* **Coeficiente Médio de Agrupamento e Coeficiente Médio de Agrupamento Hierárquico de Segundo Nível** 
* **Análise de Variáveis Canônicas** 
* **Análise do Componente Principal** 
* **Reciprocidade de Borda** 
* **Análise de Correlação** 
* **Classificação:**
   * Bayesiano 
   * DeepWalk 
   * WalkSCAN 
* **Caminhada Deterministica:**
   * Entropia de Shannon 
   * Entropia de Palavras 
* **Autômato de Rede Vida-Semelhante (LLNA)** 

## Grafos Utilizados

* **Strogatz-Watt:** Modelo de grafo aleatório com propriedades de pequeno mundo
* **Erdos-Renyis:** Modelo para gerar grafos aleatórios.
* **Barabasi-Albert:** Algoritmo para gerar redes sem escala
* **Karate Club:** Biblioteca de aprendizado de máquina não supervisionada para NetworkX
* **GrafoBrasilCovid:** Rede onde cada nó representa uma cidade e as arestas representam vias de locomoção

## Resultados

O repositório apresenta resultados para diversas métricas e algoritmos, incluindo:

* Vulnerabilidade de diferentes tipos de grafos
* Coeficiente Cíclico para diferentes tipos de grafos
* Coeficiente de Rich-Club para grafos complexos
* Relação entre coeficiente de agrupamento e coeficiente de agrupamento hierárquico
* Transformação de grafos utilizando Análise de Variáveis Canônicas
* Classificação de nós utilizando DeepWalk
* Detecção de comunidades utilizando WalkSCAN.
* Comparação entre Pagerank e Caminhada Aleatória.
* Análise de Entropia de Shannon e Entropia de Palavras em diferentes tipos de grafos
* Classificação de redes utilizando diferentes métricas e algoritmos

## Visualizações

O repositório também inclui visualizações de grafos e resultados de análises, como:

* Exemplos de grafos gerados (Strogatz-Watt, Erdos-Renyis, Barabasi-Albert, Karate Club)
* Gráfico da média do grau dos nós
* Grafo bipartido
* Gráficos de entropia de entrada e saída
* Gráfico dos autovalores da matriz de adjacência
* Matrizes de confusão para diferentes classificadores
* Scatter plots para visualização de resultados de classificação e análise de componentes principais
