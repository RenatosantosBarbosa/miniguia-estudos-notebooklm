# Prompts Reutilizáveis — NotebookLM

Este arquivo reúne prompts que podem ser reutilizados para estudar diferentes assuntos no NotebookLM.

## 1. Resumo estruturado

```text
Com base exclusivamente nas fontes fornecidas, explique o tema [TEMA] para uma pessoa que está começando a estudar o assunto.

Organize a resposta nos seguintes tópicos:

1. Conceito principal
2. Por que é importante
3. Principais características
4. Exemplos práticos
5. Pontos importantes para revisão

Para cada informação, indique a fonte utilizada.

Se uma informação não estiver presente nas fontes, deixe isso explícito em vez de utilizar conhecimento externo.




Analise o tema [TEMA] utilizando exclusivamente as fontes fornecidas.

Identifique:

1. Quais informações sobre o tema estão presentes;
2. Quais informações estão incompletas;
3. Quais informações não foram encontradas;
4. Quais fontes apresentam informações sobre o tema.

Não utilize conhecimento externo para preencher as lacunas.

Ao final, crie uma seção chamada "Lacunas das fontes" indicando quais informações ainda precisam de fontes complementares.




Compare como as fontes fornecidas abordam o tema [TEMA].

Para cada fonte:

- Identifique os principais pontos apresentados;
- Explique quais aspectos são semelhantes;
- Explique quais aspectos são diferentes;
- Indique quais informações aparecem em apenas uma das fontes.

Utilize exclusivamente as fontes fornecidas e indique a fonte de cada informação.




Explique o tema [TEMA] utilizando exclusivamente as fontes fornecidas.

Use uma linguagem simples, adequada para alguém que está estudando o assunto pela primeira vez.

Apresente:

- Definição;
- Explicação passo a passo;
- Exemplo prático;
- Principais conceitos;
- Erros ou confusões comuns, caso estejam presentes nas fontes.

Não utilize informações externas às fontes.




Com base exclusivamente nas fontes fornecidas, crie 10 perguntas para revisar o tema [TEMA].

Misture:

- Perguntas de definição;
- Perguntas de compreensão;
- Perguntas de aplicação;
- Perguntas de comparação.

Depois das perguntas, apresente um gabarito com respostas curtas e indique a fonte utilizada para cada resposta.

Não utilize informações que não estejam presentes nas fontes.




Analise a qualidade das informações disponíveis nas fontes sobre o tema [TEMA].

Identifique:

- O que as fontes explicam bem;
- O que é explicado apenas superficialmente;
- O que não é abordado;
- Quais conceitos importantes ficaram sem explicação.

Não complete as lacunas com conhecimento externo.

Ao final, explique quais tipos de fontes complementares seriam necessários para aprofundar o estudo.




Aprendizado

Os experimentos realizados neste projeto mostraram que a qualidade de uma resposta no NotebookLM depende de dois fatores principais:

A qualidade e a cobertura das fontes utilizadas;
A clareza e a estrutura do prompt.

Prompts mais específicos ajudaram a identificar lacunas nas fontes e evitaram que informações ausentes fossem apresentadas como se estivessem nos documentos.

Por isso, esses modelos podem ser adaptados para diferentes assuntos e projetos de estudo.
