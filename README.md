# Estrutura de Dados 1

Este repositório contém materiais, códigos e projetos desenvolvidos na disciplina de Estrutura de Dados 1.

## 🎯 Objetivo Geral

Capacitar os alunos a compreender, projetar e implementar algoritmos e estruturas de dados lineares fundamentais, com foco na análise de complexidade, na aplicação de diferentes métodos de ordenação e na manipulação de listas, pilhas e filas.
  
**Habilidades Desenvolvidas:**

- Análise de algoritmos e avaliação de desempenho (Notação Big O, análise de casos);
- Implementação e comparação de algoritmos de ordenação (*Selection*, *Insertion*, *Bubble*, *Merge* e *Quick*);
- Construção e manipulação de estruturas de dados lineares (listas encadeadas, pilhas, filas e deques);
- Aplicação de estruturas de dados na resolução de problemas computacionais básicos.

## 📚 Metodologia

- **Aulas Expositivas e Discussões Teóricas:** Aprofundamento dos principais conceitos de estruturas de dados e algoritmos.
- **Atividades Práticas:** Implementação dos algoritmos e estruturas em linguagens como Python ou Java, com ênfase em exercícios de análise de complexidade e comparação de desempenho.
- **Projetos Práticos:** Desenvolvimento de soluções integradas utilizando as estruturas estudadas, aplicadas em problemas reais.
- **Seminários:** Apresentações e debates sobre temas atuais e casos de uso práticos (ex: comparação entre algoritmos de ordenação e aplicações de listas encadeadas).

## 🗓️ Estrutura do Curso

A disciplina é dividida em 20 semanas, com aulas semanais, distribuídas conforme a seguinte programação:

| Semana | Tópico & Descrição | Objetivos | Material de Apoio |
| :----: | ------------------ | --------- | ----------------- |
| **1** | **Complexidade Algorítmica** <br> Introdução à análise de algoritmos, notação Big O, e medição de tempo e espaço para avaliar a eficiência de soluções. | - Definir Big O e sua importância; <br> - Diferenciar as complexidades; <br> - Complexidade de algoritmos. | [Aula](Semana_01_(ED1).ipynb) <br> [Exercícios](Semana_01_(ED1).pdf) |
| **2** | **Bubble Sort** <br> Algoritmo simples que compara pares adjacentes e os troca de lugar se estiverem na ordem errada. | - Definir o que são algoritmos de ordenação; <br> - Explicar o *Bubble Sort*; <br> - Analisar sua complexidade (O(n²) e O(n)); <br> - Listar suas vantagens e desvantagens. | [Aula](Semana_02_(ED1).ipynb) <br> Exercícios |
| **3** | **Insertion Sort** <br> Análise do algoritmo de ordenação por inserção, eficiente para conjuntos de dados pequenos ou parcialmente ordenados. | - Explicar o *Insertion Sort*; <br> - Analisar sua complexidade (O(n²) e O(n)); <br> - Listar suas vantagens e desvantagens. | [Aula](Semana_03_(ED1).ipynb) <br> [Vídeo](https://youtu.be/lwr8e5QP5Zg) <br> Exercícios |
| **4** | **Selection Sort** <br> Algoritmo que busca repetidamente o menor elemento e o posiciona corretamente. | - Explicar o *Selection Sort*; <br> - Analisar sua complexidade O(n²); <br> - Listar suas vantagens e desvantagens. | [Aula](Semana_04_(ED1).ipynb)  <br> Exercícios |
| **5** | **Prova 1** <br> Prova teórica e prática sobre os conteúdos das semanas 1 a 4. | - Avaliar o domínio dos conceitos de complexidade e a implementação de algoritmos de ordenação simples. | [Pré-Teste 25.2](Pre-Teste_01_(ED1).pdf) [Pré-Teste 26.1](Pre-Teste_01_(ED1).pdf) |
| **6** | **Merge Sort** <br> Apresentação do paradigma "dividir para conquistar" com o Merge Sort, um algoritmo de ordenação recursivo e eficiente. | - Entender a lógica de divisão, conquista e combinação.<br>- Implementar o Merge Sort e analisar sua complexidade O(n log n).<br>- Comparar seu uso de memória com outros métodos. | [Apoio](Apoio_01_(ED1).ipynb) <br> [Aula](Semana_06_(ED1).ipynb) <br> Exercícios |
| **7** | **Quick Sort** <br> Estudo do Quick Sort, outro algoritmo de "dividir para conquistar" que se destaca pela sua velocidade na prática. | - Compreender a estratégia de particionamento e a escolha do pivô.<br>- Implementar o Quick Sort.<br>- Analisar seu desempenho no caso médio e pior caso. | [Aula](Semana_07_(ED1).ipynb) <br> Exercícios |
| **8** | **Prova 2** <br> Prova teórica e prática sobre os conteúdos das semanas 6 e 7. | - Avaliar o domínio dos conceitos de complexidade e a implementação de algoritmos de ordenação eficientes. | [Pré-Teste](Pre-Teste_02_(ED1).pdf) |
| **9** | **Seminários 1** <br> Apresentações em grupo sobre a aplicação e comparação de algoritmos de ordenação em cenários reais. | - Analisar algoritmos de ordenação eficientes; <br> - Comparar a complexidade e seus *trade-offs*; <br> - Compreender algoritmos híbridos. | [Orientações](Semana_09_(ED1).pdf) |
| **10** | **Projeto 1** <br> Desenvolvimento de um projeto prático para aplicar e comparar o desempenho dos algoritmos de ordenação estudados. | - Comparar métodos de extração de características; <br> - Medir tempo e custo computacional de ordenação; <br> - Avaliar a qualidade da ordenação. | [Orientações](Projeto_01_(ED1).pdf) |
| **11** | **Listas Simplesmente Encadeadas** <br> Introdução à estrutura de dados de lista encadeada, seus nós e operações básicas (inserção, remoção, busca). | - Compreender a alocação dinâmica de memória.<br>- Implementar uma lista encadeada do zero.<br>- Analisar vantagens e desvantagens em relação a arrays. | [Aula](Semana_11_(ED1).ipynb) <br> Exercícios |
| **12** | **Listas Duplamente Encadeadas** <br> Expansão do conceito com nós que possuem referência para o elemento anterior e o próximo, facilitando a navegação. | - Implementar uma lista duplamente encadeada.<br>- Realizar operações de inserção e remoção de forma mais eficiente.<br>- Analisar casos de uso como "desfazer/refazer". | [Aula](Semana_12_(ED1).ipynb) <br> Exercícios |
| **13** | **Listas Circulares** <br> Estudo de listas onde o último nó aponta para o primeiro, criando um ciclo. Útil em buffers e escalonamento. | - Implementar listas circulares (simples e duplas).<br>- Compreender cenários de aplicação como o algoritmo Round-Robin. | [Aula](Semana_13_(ED1).ipynb) <br> Exercícios |
| **14** | **Prova 3** <br> Prova teórica e prática sobre os conteúdos das semanas 11 a 13. | - Avaliar o domínio das estruturas de dados listas encadeadas (simples, dupla e circular). |  [Pré-Teste](Pre-Teste_03_(ED1).pdf) |
| **15** | **Pilhas (Stacks)** <br> Estudo da estrutura de dados LIFO (Last-In, First-Out), com suas operações `push`, `pop` e `peek`. | - Implementar uma pilha usando arrays e listas encadeadas.<br>- Entender suas aplicações (ex: chamadas de função, validação de parênteses). | Aula <br> Exercícios |
| **16** | **Filas (Queues)** <br> Estudo da estrutura de dados FIFO (First-In, First-Out), com operações de `enqueue` e `dequeue`. | - Implementar uma fila usando arrays e listas encadeadas.<br>- Compreender suas aplicações (ex: gerenciamento de tarefas, buffers de impressão). | Aula <br> Exercícios |
| **17** | **Deques (Double-Ended Queues)** <br> Apresentação do deque, uma estrutura de dados generalizada que permite inserção e remoção em ambas as extremidades. | - Implementar um deque.<br>- Entender como um deque pode funcionar como pilha e como fila.<br>- Analisar sua flexibilidade em algoritmos. | Aula <br> Exercícios |
| **18** | **Prova 4** <br> Prova teórica e prática sobre os conteúdos das semanas 15 a 17. | - Avaliar o domínio das estruturas de dados pilhas, filas e deques. | [Pré-Teste]() |
| **19** | **Seminários 2** <br> Apresentações em grupo sobre o uso de listas, pilhas e filas em software e sistemas computacionais. | - Pesquisar e apresentar aplicações reais das estruturas de dados estudadas.<br>- Debater sobre otimizações e desafios de implementação. | [Orientações]() |
| **20** | **Projeto 2** <br> Desenvolvimento de um projeto final que integre diferentes estruturas de dados lineares para resolver um problema complexo. | - Integrar listas, pilhas e/ou filas em uma única solução.<br>- Demonstrar a capacidade de escolher a estrutura de dados correta para cada tarefa. | [Orientações]() |
