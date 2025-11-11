# Prática de Python para Data Science e Arrays em JavaScript

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

</div>

Este repositório reúne materiais de estudo em duas frentes:

- **Notebooks em Python** com exercícios introdutórios de ciência de dados e exploração de dados com Pandas.
- **Scripts em JavaScript** que praticam manipulação de arrays, funções e outras construções básicas da linguagem.

A organização facilita revisar os conceitos separadamente, mas ambos os conjuntos de arquivos seguem a mesma temática de praticar estruturas de dados, funções e fluxo de controle.

## Estrutura do repositório

| Caminho | Descrição |
|--------|-----------|
| `Aula_01_Python_para_Data_Science.ipynb` | Notebook em português que introduz bibliotecas Python para ciência de dados, funções, estruturas de repetição e tratamento de exceções. Cada seção intercala explicações teóricas com células de código para prática guiada. |
| `Pandas.ipynb` | Notebook focado em exploração de dados usando a biblioteca Pandas. Mostra como carregar conjuntos de dados remotos, inspecionar colunas, tipos e estatísticas e preparar dados para análise. |
| `array/` | Conjunto de scripts JavaScript demonstrando conceitos como criação e iteração de arrays, `map`, `forEach`, `slice`, condicionais, funções arrow e templates de string. Cada arquivo é independente e pode ser executado isoladamente com Node.js. |

## Como executar os notebooks

1. Garanta que você tem o [Jupyter Lab](https://jupyter.org/) ou o Google Colab disponível.
2. Abra o notebook desejado (`Aula_01_Python_para_Data_Science.ipynb` ou `Pandas.ipynb`).
3. Execute as células sequencialmente para acompanhar as explicações e realizar os exercícios sugeridos.

As células incluem exemplos de instalação de bibliotecas com `pip`, visualizações com Matplotlib, seleção aleatória com `random.choice`, criação de funções com docstrings e tratamento de exceções usando `try`, `except`, `else` e `finally`.

No notebook `Pandas.ipynb`, os exemplos utilizam dados públicos hospedados em repositórios da Alura para demonstrar leitura de CSV, inspeção de `DataFrame`, amostragem de registros e preparação para uma análise exploratória.

## Como executar os exemplos em JavaScript

1. Instale o [Node.js](https://nodejs.org) (versão LTS recomendada).
2. No terminal, acesse a pasta `array/`.
3. Execute um dos arquivos com `node`, por exemplo:

   ```bash
   node mediaForEach.js
   ```

Cada script ilustra um conceito específico. Alguns exemplos:

- `arrays.js`, `mediaFor.js` e `MediaForOf.js` calculam médias a partir de listas de notas usando diferentes estruturas de repetição.
- `callBack.js`, `mediaForEach.js` e `desafioMap.js` mostram como usar funções de alta ordem como `forEach` e `map`.
- `lista-duas-dimensoes.js`, `divirSala.js` e `juntadoSalas.js` trabalham com arrays multidimensionais e particionamento de turmas.
- `arrowFunction.js`, `tenario.js` e `templade Strings.js` reforçam sintaxe moderna da linguagem com arrow functions, operadores ternários e template strings.
- `removendoNotas.js` e `exercicio.js` exemplificam inserção, remoção e busca em listas por meio de métodos como `push`, `splice` e `includes`.

## Próximos passos sugeridos

- Completar as células em branco dos notebooks para praticar os exercícios propostos.
- Adaptar os scripts JavaScript para cenários próprios (por exemplo, outras listas de alunos ou notas) para fixar os conceitos.
- Consolidar os aprendizados criando um pequeno projeto que combine análise de dados em Python com uma apresentação dos resultados em JavaScript.

Bom estudo!
