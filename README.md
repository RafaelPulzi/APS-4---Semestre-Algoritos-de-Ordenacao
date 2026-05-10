# APS 4 - Semestre Algoritos de Ordenação

 Basicamente estamos gerando um programa que vai ler os dados de satélites que estão catalogados na pasta dados e logo depois eles vão medir o potencial de cada algoritmo baseando-se no número de comparações feitas e no número de arrays acessados 

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

```
OrdenacaoDadosDeSatelite/
│
├── 0dados/                 # Base de dados com catálogo de satélites
│
├── bubbleSort/             # Implementação do Bubble Sort
├── heapSort/               # Implementação do Heap Sort
├── quickSort/              # Implementação do Quick Sort
│
├── .vscode/                # Configurações do ambiente VS Code
├── .gitattributes
└── README.md
```

---

## 🚀 Como Executar

### Pré-requisitos

- Compilador C++ (g++, clang, etc.)
- Ambiente de desenvolvimento (VS Code, terminal, etc.)

### Passo a passo

1. **Clone o repositório**

```bash
git clone https://github.com/RafaelPulzi/OrdenacaoDadosDeSatelite.git
cd OrdenacaoDadosDeSatelite
```

2. **Acesse a pasta de um algoritmo e compile**

```bash
cd bubbleSort
g++ -o bubbleSort main.cpp   # Ajuste o nome do arquivo conforme necessário
```

3. **Execute o programa**

```bash
./bubbleSort
```

> A saída exibirá o número de comparações e acessos ao array durante a ordenação dos dados de satélite.

### Executando todos os algoritmos

Você pode repetir o processo para cada pasta (`heapSort`, `quickSort`) e comparar os resultados gerados.

---

## 📊 Análise e Resultados Esperados

Os algoritmos serão avaliados com base em:

- **Comparações:** quantas vezes dois elementos são comparados
- **Acessos ao array:** quantas leituras e escritas são realizadas

Espera-se observar que algoritmos como **Quick Sort** e **Heap Sort** apresentem um número significativamente menor de operações em relação ao **Bubble Sort**, especialmente com conjuntos de dados maiores.

---

## 🧪 Base de Dados

A pasta `0dados` contém um arquivo com o catálogo de satélites. Cada registro provavelmente contém informações como nome, país de origem, data de lançamento, órbita, entre outros. O formato exato dos dados pode ser verificado nos arquivos da pasta.

Os algoritmos ordenam esses registros com base em um critério específico (por exemplo, nome ou data), de acordo com a implementação.

---

## 🤝 Contribuições

Este é um projeto acadêmico, mas contribuições são bem-vindas! Se você quiser sugerir melhorias, corrigir bugs ou adicionar novos algoritmos de ordenação:

1. Faça um **fork** do projeto
2. Crie uma **branch** para sua feature (`git checkout -b feature/nova-feature`)
3. **Commit** suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. **Push** para a branch (`git push origin feature/nova-feature`)
5. Abra um **Pull Request**

---

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](https://github.com/RafaelPulzi/SistemaSolarJS/blob/main/LICENSE) para mais informações.

---

## 👨‍💻 Autores

- **Rafael Pulzi** - [GitHub](https://github.com/RafaelPulzi)
- **John Doe** - [GitHub](https://github.com/john0403)



---

*Projeto desenvolvido para a disciplina de Algoritmos e Estruturas de Dados - 4º Semestre* 🚀
