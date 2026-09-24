# Engenharia de Prompts

        ## Experimento 01 — Resumo inicial

### Objetivo

Obter uma visão geral dos principais conceitos de educação financeira presentes nas fontes selecionadas.

### Prompt utilizado

> Com base nas fontes fornecidas, explique os principais conceitos de educação financeira apresentados nos materiais.
>
> Organize a resposta nos seguintes tópicos:
>
> 1. Orçamento pessoal
> 2. Juros
> 3. Inflação
> 4. Reserva financeira
> 5. Investimentos
>
> Utilize uma linguagem adequada para uma pessoa que está começando a estudar educação financeira.
>
> Sempre que possível, indique qual fonte foi utilizada para cada informação.

### Resultado

O NotebookLM conseguiu apresentar informações sobre orçamento pessoal, juros, reserva financeira e investimentos.

Entretanto, a resposta identificou que as fontes disponíveis não apresentavam uma explicação direta sobre inflação nos trechos utilizados.

### Problemas identificados

* O conceito de juros foi apresentado principalmente relacionado a dívidas, sem uma explicação mais ampla;
* O conceito de inflação não foi encontrado de forma suficientemente detalhada nas fontes;
* Alguns conceitos poderiam receber exemplos práticos;
* A resposta poderia apresentar uma separação mais clara entre definição, importância e aplicação de cada conceito.

### Aprendizado

O primeiro teste mostrou que um prompt genérico consegue produzir um resumo inicial, mas instruções mais específicas podem ajudar a obter respostas mais completas e organizadas.

Também foi observado que a IA pode identificar quando uma informação não está suficientemente presente nas fontes, evitando apresentar uma explicação sem fundamentação.




        ## Experimento 02 — Prompt estruturado

### Objetivo

Melhorar o primeiro resultado, solicitando uma estrutura padronizada para cada conceito e exigindo que o NotebookLM identificasse explicitamente as limitações das fontes.

### Prompt utilizado

> Com base exclusivamente nas fontes fornecidas, explique os cinco conceitos abaixo para uma pessoa que está começando a estudar educação financeira:
>
> 1. Orçamento pessoal
> 2. Juros
> 3. Inflação
> 4. Reserva financeira
> 5. Investimentos
>
> Para cada conceito, apresente obrigatoriamente:
>
> * Definição simples;
> * Por que o conceito é importante;
> * Um exemplo prático baseado nas informações das fontes;
> * Principais pontos apresentados pelas fontes;
> * Fonte ou fontes utilizadas.
>
> Se as fontes não apresentarem informações suficientes sobre determinado conceito, deixe isso explícito em vez de completar a resposta com informações externas.
>
> Ao final, faça uma seção chamada "Lacunas das fontes", indicando quais conceitos não foram suficientemente abordados pelos materiais.

### Resultado

O segundo prompt produziu uma resposta mais estruturada e detalhada. O NotebookLM passou a separar definição, importância, exemplos, pontos principais e fontes utilizadas.

Também identificou de forma explícita as limitações do conjunto de fontes.

### Melhorias observadas

Em comparação com o primeiro experimento:

* A resposta ficou mais organizada;
* Os conceitos receberam definições individuais;
* Foram apresentados exemplos práticos;
* As fontes utilizadas ficaram mais claras;
* As lacunas dos materiais foram identificadas de maneira explícita;
* O modelo foi orientado a não completar informações ausentes utilizando conhecimento externo.

### Nova descoberta

O experimento revelou que o conjunto de fontes possui uma cobertura limitada sobre **inflação** e sobre a definição técnica de **juros**.

As fontes apresentam juros principalmente no contexto de dívidas e negociação, mas não explicam adequadamente conceitos como juros simples e compostos.

Isso indica que uma etapa posterior do projeto poderá exigir uma fonte complementar caso esses conceitos sejam mantidos como objetivos de estudo.
