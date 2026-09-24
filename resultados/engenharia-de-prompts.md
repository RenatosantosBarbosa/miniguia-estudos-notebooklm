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



        ## Experimento 03 — Investigação das lacunas

### Objetivo

Investigar de forma específica os conceitos de juros e inflação após o segundo experimento indicar que esses temas não estavam suficientemente detalhados nas fontes selecionadas.

### Prompt utilizado

> Analise especificamente os conceitos de juros e inflação presentes nas fontes fornecidas.
>
> Para JUROS:
>
> 1. Explique o que são juros.
> 2. Diferencie juros simples e juros compostos, caso as fontes apresentem essa diferença.
> 3. Mostre um exemplo numérico encontrado nas fontes.
> 4. Explique como os juros podem afetar tanto investimentos quanto dívidas.
> 5. Indique quais fontes sustentam cada informação.
>
> Para INFLAÇÃO:
>
> 1. Explique o que é inflação, caso o conceito esteja presente nas fontes.
> 2. Explique como a inflação afeta o poder de compra.
> 3. Explique qual relação as fontes apresentam entre inflação e investimentos.
> 4. Indique quais fontes sustentam cada informação.
>
> IMPORTANTE:
> Utilize exclusivamente as fontes fornecidas.
> Não complete lacunas com conhecimento externo.
> Se uma informação não estiver presente nas fontes, escreva claramente: "A informação não foi encontrada nas fontes fornecidas."
>
> Ao final, faça uma seção chamada "O que aprendemos com este experimento", explicando se as fontes são suficientes para estudar esses dois conceitos.

### Resultado

O experimento confirmou que as fontes selecionadas não eram suficientes para estudar juros e inflação de maneira teórica e detalhada.

Em relação aos juros, as fontes apresentaram principalmente informações relacionadas a dívidas e negociação de taxas, mas não forneceram uma definição técnica adequada nem explicações sobre juros simples e compostos.

Em relação à inflação, o NotebookLM não encontrou informações suficientes para explicar o conceito, seu impacto sobre o poder de compra ou sua relação com investimentos.

### Problemas identificados

- Ausência de uma definição adequada de juros;
- Ausência de explicação sobre juros simples e compostos;
- Ausência de exemplos numéricos de juros;
- Ausência de uma explicação sobre inflação;
- Ausência de informações sobre o impacto da inflação no poder de compra.

### Aprendizado

O experimento demonstrou a importância da curadoria das fontes. Antes de tentar obter uma resposta mais detalhada da IA, é necessário verificar se os documentos fornecidos realmente contêm informações suficientes para responder à pergunta.

A partir desse resultado, foi identificada a necessidade de adicionar uma quinta fonte específica sobre juros e inflação.



        ## Experimento 04 — Testando a nova fonte

### Objetivo

Verificar se a inclusão de uma quinta fonte, específica sobre inflação e juros, resolveria as lacunas identificadas no Experimento 03.

### Prompt utilizado

> Com base exclusivamente nas cinco fontes fornecidas, analise os conceitos de juros e inflação.
>
> Para JUROS:
>
> 1. Explique de forma simples o que são juros.
> 2. Diferencie juros simples e juros compostos, caso as fontes apresentem essa diferença.
> 3. Apresente um exemplo numérico, caso exista nas fontes.
> 4. Explique como os juros podem afetar dívidas e investimentos.
> 5. Explique a relação entre juros e inflação, caso seja apresentada pelas fontes.
> 6. Indique quais fontes sustentam cada informação.
>
> Para INFLAÇÃO:
>
> 1. Explique de forma simples o que é inflação.
> 2. Explique como a inflação afeta o poder de compra.
> 3. Explique a relação entre inflação e juros.
> 4. Explique como a inflação pode afetar investimentos.
> 5. Indique quais fontes sustentam cada informação.
>
> IMPORTANTE:
> Utilize exclusivamente as fontes fornecidas.
> Não complete lacunas com conhecimento externo.
> Quando uma informação não estiver presente nas fontes, escreva claramente:
> "A informação não foi encontrada nas fontes fornecidas."
>
> Ao final, faça uma seção chamada "Comparação com o Experimento 03", explicando quais lacunas identificadas anteriormente foram resolvidas pela nova fonte e quais continuam existindo.

### Resultado

A inclusão da nova fonte melhorou significativamente a cobertura dos conceitos de juros e inflação.

O NotebookLM conseguiu apresentar uma definição de juros como custo de emprestar dinheiro ou remuneração pelo dinheiro emprestado, além de relacionar a taxa Selic aos contratos e investimentos.

Também foi apresentada a diferença entre juros nominais e juros reais, utilizando um exemplo de uma aplicação com rendimento nominal de 10% ao ano e inflação de 6%, resultando em um ganho real aproximado de 4%.

Em relação às dívidas, as fontes permitiram identificar que juros mais altos podem aumentar o custo de financiamentos e do crédito. Nos investimentos, foi apresentada a relação entre juros, rentabilidade e inflação.

A inflação passou a ser explicada como um aumento sustentado e generalizado dos preços, com impacto direto sobre o poder de compra. Também foi identificada a relação entre inflação e juros, incluindo o uso da taxa de juros como instrumento para controlar a inflação.

### Lacunas que foram resolvidas

- Definição de juros;
- Definição de inflação;
- Relação entre juros e inflação;
- Impacto da inflação sobre o poder de compra;
- Relação entre juros, inflação, dívidas e investimentos;
- Diferença entre juros nominais e juros reais;
- Exemplo numérico relacionado ao ganho real de um investimento.

### Lacunas que continuam existindo

Mesmo após a inclusão da quinta fonte, as fontes ainda não apresentam uma explicação adequada sobre a diferença entre **juros simples e juros compostos**.

Esse resultado demonstra que adicionar uma fonte pode resolver algumas lacunas, mas também pode revelar a necessidade de uma fonte ainda mais específica para determinado conceito.

### Aprendizado

O experimento demonstrou a importância de testar novamente os prompts após modificar o conjunto de fontes.

A nova fonte ampliou significativamente a capacidade do NotebookLM de responder sobre juros e inflação, mostrando que a qualidade da resposta depende não apenas da formulação do prompt, mas também da qualidade e da cobertura das fontes utilizadas.

Ao mesmo tempo, o experimento mostrou que ainda existe uma lacuna específica sobre juros simples e compostos, que poderá ser investigada em uma próxima etapa.



        ## Experimento 05 — Investigação de juros simples e compostos

### Objetivo

Investigar se as cinco fontes selecionadas eram suficientes para estudar os conceitos de juros simples e juros compostos, incluindo suas definições, cálculos, exemplos e aplicações.

### Prompt utilizado

> Com base exclusivamente nas cinco fontes fornecidas, investigue especificamente os conceitos de juros simples e juros compostos.
>
> Responda aos seguintes pontos:
>
> 1. As fontes apresentam uma definição de juros simples?
> 2. As fontes apresentam uma definição de juros compostos?
> 3. Existe alguma comparação entre juros simples e juros compostos?
> 4. As fontes apresentam fórmulas para calcular esses dois tipos de juros?
> 5. Existe algum exemplo numérico de juros simples?
> 6. Existe algum exemplo numérico de juros compostos?
> 7. As fontes explicam em quais situações os juros simples ou compostos podem ser utilizados?
> 8. Existe alguma relação entre juros compostos, investimentos e crescimento do dinheiro ao longo do tempo?
>
> Para cada resposta:
>
> - Indique claramente se a informação foi encontrada ou não;
> - Explique de forma simples;
> - Indique a fonte utilizada.
>
> IMPORTANTE:
> Utilize exclusivamente as cinco fontes fornecidas.
> Não utilize conhecimento externo para completar as respostas.
> Se uma informação não estiver presente nas fontes, escreva:
> "A informação não foi encontrada nas fontes fornecidas."
>
> Ao final, faça uma seção chamada "Conclusão do experimento", indicando se as cinco fontes são suficientes para estudar juros simples e juros compostos de forma adequada.

### Resultado

O experimento confirmou que as cinco fontes não são suficientes para estudar juros simples e juros compostos de forma adequada.

Embora as fontes apresentem uma definição geral de juros e abordem seus efeitos sobre dívidas e investimentos, os termos "juros simples" e "juros compostos" não foram encontrados nos materiais analisados.

Também não foram encontradas fórmulas, exemplos numéricos ou comparações entre os dois tipos de juros.

### Lacunas identificadas

- Ausência de definição de juros simples;
- Ausência de definição de juros compostos;
- Ausência de comparação entre os dois conceitos;
- Ausência de fórmulas matemáticas;
- Ausência de exemplos numéricos;
- Ausência de explicação sobre as aplicações de cada modalidade;
- Ausência de explicação sobre o efeito dos juros compostos no crescimento de investimentos ao longo do tempo.

### Aprendizado

O experimento mostrou que as fontes selecionadas são adequadas para uma introdução à educação financeira, especialmente em temas como orçamento, inflação, reserva financeira, investimentos e relação entre juros e economia.

Porém, elas não possuem profundidade matemática suficiente para estudar juros simples e compostos.

Isso reforça a importância de analisar não apenas a quantidade de fontes utilizadas, mas também a cobertura e a profundidade de cada fonte em relação aos objetivos de estudo.

### Conclusão

As cinco fontes são suficientes para uma introdução aos conceitos financeiros investigados, mas não para um estudo matemático completo de juros simples e compostos.

O experimento também mostrou que uma boa estratégia de pesquisa com IA não consiste apenas em obter respostas, mas em identificar explicitamente o que as fontes conseguem ou não responder.
