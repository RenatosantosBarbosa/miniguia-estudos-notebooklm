# Miniguia de Educação Financeira com NotebookLM

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático da DIO, utilizando o NotebookLM como ferramenta de aprendizagem ativa.

O tema escolhido foi **educação financeira para iniciantes**, com foco em conceitos relacionados à organização financeira, juros, inflação, reserva financeira e investimentos.

A proposta foi utilizar a Inteligência Artificial não apenas para obter respostas, mas também para investigar as limitações das fontes, testar diferentes prompts e avaliar criticamente os resultados.

---

## 🎯 Objetivos

- Compreender como funciona um orçamento pessoal;
- Entender receitas, despesas e planejamento financeiro;
- Compreender conceitos relacionados a juros;
- Entender inflação e seu impacto sobre o poder de compra;
- Compreender a importância de uma reserva financeira;
- Conhecer conceitos básicos de investimentos, riscos e retorno;
- Comparar informações entre diferentes fontes;
- Testar diferentes estratégias de prompting no NotebookLM;
- Identificar limitações das fontes utilizadas;
- Criar materiais de estudo e prompts reutilizáveis.

---

## 📚 Fontes utilizadas

Foram utilizadas cinco fontes abertas relacionadas à educação financeira:

1. **Banco Central do Brasil — Caderno de Educação Financeira**
2. **SUSEP — Orçamento**
3. **CVM — Educação**
4. **CVM — Publicações Educacionais**
5. **InvesteAqui — Inflação e juros: qual a relação**

As fontes foram selecionadas buscando combinar materiais institucionais com uma fonte complementar específica sobre juros e inflação.

---

## 🧪 Experimentos

Durante o projeto foram realizados cinco experimentos no NotebookLM.

### Experimento 01 — Resumo inicial

Foi criado um prompt para obter uma visão geral dos principais conceitos de educação financeira.

**Resultado:** orçamento, reserva financeira e investimentos foram bem abordados, enquanto juros e inflação apresentaram limitações.

### Experimento 02 — Prompt estruturado

O prompt passou a exigir definição, importância, exemplo, principais pontos e fontes utilizadas para cada conceito.

**Resultado:** a resposta ficou mais organizada e as limitações das fontes ficaram mais claras.

### Experimento 03 — Investigação das lacunas

Foi realizada uma investigação específica sobre juros e inflação.

**Resultado:** foi identificada a necessidade de uma fonte complementar sobre esses temas.

### Experimento 04 — Testando a nova fonte

Uma quinta fonte sobre juros e inflação foi adicionada ao NotebookLM.

**Resultado:** a nova fonte resolveu várias lacunas, permitindo abordar definições de juros e inflação, juros nominais e reais e a relação entre juros e inflação.

### Experimento 05 — Juros simples e compostos

Foi investigado se as cinco fontes eram suficientes para estudar juros simples e compostos.

**Resultado:** as fontes continuaram insuficientes para esse estudo matemático específico, não apresentando fórmulas, exemplos ou uma comparação adequada entre os dois conceitos.

---

## 🧠 Principais aprendizados

O projeto demonstrou que a qualidade das respostas de uma ferramenta de IA depende não apenas do prompt utilizado, mas também da qualidade, cobertura e profundidade das fontes fornecidas.

Os experimentos mostraram que prompts mais específicos ajudam a:

- Organizar melhor as respostas;
- Identificar informações ausentes;
- Evitar que lacunas sejam preenchidas com informações externas;
- Comparar diferentes fontes;
- Avaliar criticamente os resultados produzidos pela IA.

Também foi possível perceber que uma fonte pode ser adequada para uma introdução a determinado assunto, mas insuficiente para um estudo mais técnico.

Um exemplo foi o estudo de juros simples e compostos: as fontes apresentaram conceitos gerais sobre juros, mas não forneceram conteúdo matemático suficiente para aprofundar o tema.

---

## 📂 Estrutura do projeto

```text
miniguia-estudos-notebooklm/
│
├── Resultados/
│   ├── engenharia-de-prompts.md
│   ├── resumos.md
│   └── glossario.md
│
├── prompts/
│   └── prompts-reutilizaveis.md
│
├── Fontes/
├── LICENÇA
└── README.md
