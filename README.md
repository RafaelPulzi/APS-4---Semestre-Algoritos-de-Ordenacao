# APS 4 - Semestre Algoritos de Ordenação

 Baicamente estamos gerando um programa que vai ler os dados de satélites que estão catalogados na pasta dados e logo depois eles vão medir o potencial de cada algoritmo baseando-se no número de comparações feitas e no número de arrays acessados 

---

# 🛰️ Análise de Algoritmos de Ordenação com Dados de Satélite

[![GitHub repo size](https://img.shields.io/github/repo-size/RafaelPulzi/OrdenacaoDadosDeSatelite?style=flat-square)](https://github.com/RafaelPulzi/OrdenacaoDadosDeSatelite)
[![GitHub last commit](https://img.shields.io/github/last-commit/RafaelPulzi/OrdenacaoDadosDeSatelite?style=flat-square)](https://github.com/RafaelPulzi/OrdenacaoDadosDeSatelite/commits)
[![GitHub license](https://img.shields.io/github/license/RafaelPulzi/SistemaSolarJS?style=flat-square&color=blue)](https://github.com/RafaelPulzi/SistemaSolarJS/blob/main/LICENSE)
[![Language](https://img.shields.io/badge/Language-C%2B%2B-blue?style=flat-square&logo=cplusplus)](https://isocpp.org/)
[![Status](https://img.shields.io/badge/Status-Academic%20Project-brightgreen?style=flat-square)]()

---

## 📖 Sobre o Projeto

Este projeto tem como objetivo **avaliar e comparar o desempenho de diferentes algoritmos de ordenação** aplicados a um conjunto de dados reais: um catálogo de satélites. A análise se baseia em duas métricas fundamentais para medir a eficiência de cada algoritmo:

- **Número de Comparações** entre elementos
- **Número de Acessos ao Array** (leituras e escritas)

A aplicação lê os dados de satélites armazenados na pasta `0dados`, aplica os algoritmos de ordenação e quantifica o esforço computacional de cada um, permitindo uma comparação prática entre diferentes estratégias de ordenação.

---

## 🎯 Objetivos Acadêmicos

- Implementar e analisar algoritmos clássicos de ordenação
- Comparar a eficiência teórica com resultados empíricos
- Utilizar dados reais (catálogo de satélites) como base de teste
- Gerar métricas quantitativas (comparações e acessos) para cada algoritmo
- Documentar o comportamento de cada método em um cenário prático

---

## 🧠 Algoritmos Implementados

O repositório contém os seguintes algoritmos de ordenação:

| Algoritmo | Pasta | Descrição |
|-----------|-------|-----------|
| **Bubble Sort** | `bubbleSort/` | Algoritmo simples de ordenação por trocas sucessivas. |
| **Heap Sort** | `heapSort/` | Utiliza uma estrutura de heap para ordenar os dados. |
| **Quick Sort** | `quickSort/` | Algoritmo de divisão e conquista com pivô. |

> Cada algoritmo foi implementado em C++ e instrumentado para contar o número de comparações e acessos ao array.

---

## 📁 Estrutura do Repositório
