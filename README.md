# Sistema SOA para Análise de Tendência de Nomes no Brasil

Este é um sistema orientado a serviços (SOA) desenvolvido para consultar a API de nomes do IBGE e realizar análises de tendências de nomes próprios no Brasil, desde a década de 1930 até os dias atuais. O projeto foi desenvolvido utilizando HTML, CSS e JavaScript puros, com separação clara de responsabilidades entre interface e lógica de negócio, respeitando os princípios de arquitetura SOA.

## Objetivo

Permitir que usuários explorem a evolução de nomes no Brasil, comparem a popularidade entre nomes e visualizem os nomes mais comuns por estado (UF), utilizando dados da API oficial do IBGE.

## Funcionalidades

### 1. Evolução do ranking de um nome

* O usuário informa um nome e define um intervalo de décadas (ex: 1970 a 2000).
* O sistema exibe, em um gráfico de linha (Chart.js), a evolução da frequência do nome ao longo do período.

### 2. Top 3 nomes por localidade (UF)

* O usuário seleciona uma unidade federativa (UF).
* O sistema mostra os três nomes mais frequentes em forma de tabela.

### 3. Comparativo entre dois nomes (nacional)

* O usuário informa dois nomes.
* O sistema exibe, em um gráfico de linha, a comparação da frequência entre os dois nomes desde 1930.

## Requisitos Técnicos

* HTML, CSS e JavaScript (vanilla)
* Uso da API de nomes do IBGE via requisições REST (fetch)
* Gráficos interativos com [Chart.js](https://www.chartjs.org/)
* Estrutura modularizada e separada em arquivos:

  * `index.html` (interface)
  * `style.css` (estilo)
  * `script.js` (lógica de negócio)

## Execução do Projeto

- Acesse o Link: https://eduvoltatone.github.io/Atividade-Arquitetura-de-Software-13-05/

## Documentação da API do IBGE

[https://servicodados.ibge.gov.br/api/docs/nomes](https://servicodados.ibge.gov.br/api/docs/nomes)

## Licença

Este projeto é de uso educacional e está licenciado sob a Licença MIT.

---

Desenvolvido para atividade prática de Sistemas Orientados a Serviços (SOA).
