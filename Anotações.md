**Introdução a inteligência artificial**
--------------------------------------





**Como a Inteligência artificial Nasceu.**

\--------------------------------------

Livro: Androides conseguem sonhar com ovelhas elétricas?



Filme: Blade Runner - HER



1966 - Criado primeiro Chat bot Eliza no MIT



Processamento em Linguagem natural, conversação normalmente com a nossa linguagem.



Machine Learning = A Maquina ia aprendendo de conforme ia sendo utilizada.



1972 - Parry - Era um psiquiatra IA



Modelo de linguagem - Termo muito usado na area.



2010 - IBM Watson - 



PLN - Processamento de linguagem Natural



2018 - ChatGPT



\--------------------------------------





**Como uma inteligência artificial é treinada e o que são LLMs**

\--------------------------------------



Parâmetros de reconhecimento - São informações que a IA armazena sobre o que foi passado para ela aprender.


Parâmetros são guardado em formatos de TOKENS

Reforço Positivo - Informação que valida possível reposta da IA.



Grande modelo de linguagem - Large Language Model - LLMs

SLMs - Small Language Model - São vocabulários mais focados.

--------------------------------------





**Entendendo Deep Learning**
--------------------------------------



Conexões Neurais - 

Inferência é um processo de raciocínio no qual se chega a uma conclusão, ou seja, a um conhecimento desconhecido, a partir de premissas ou observações que são consideradas verdadeiras.



São Multimodal - Ela pode criar modelo de voz, criar imagem, ela não só responde mais aprende e cria tbm.


\--------------------------------------



**A Era das IAs Generativas**

\--------------------------------------



Generativa: Algo que tenha propriedade de gerar ou criar algo novo.



A IA esta em uma época multimodal.

A IA Agora começou a criar as coisas

Vibe Coding



Engenheiro de Prompt - Profissão nova criada pelas IAs.

Toda criação abre discussão para ETICA



Cibersegurança + IA



\--------------------------------------


**Como Você Vai Dominar Fundamentos de Modelos de Linguagem de Grande Escala**

\--------------------------------------

**Introdução aos Fundamentos de Modelos de Linguagem de Grande Escala**

\--------------------------------------

**Principais Características dos LLMs**

\--------------------------------------

Transformers criado pela google em 2017

\--------------------------------------

**Desafios no Desenvolvimento de LLMs**

\--------------------------------------

**Exemplos e Aplicações de LLMs**

\--------------------------------------

**Impacto dos LLMs na Sociedade**

\--------------------------------------

**Introdução à engenharia de Prompts**

\--------------------------------------

Por que aprender engenharia de prompts?

\--------------------------------------

Sempre ser especifico na criação do prompt.
Ser claro.
Objetivo
e informações que validem o que necessário é
\--------------------------------------

Elementos Essenciais de um Bom Prompt

\--------------------------------------

Introdução
Contexto adequado
Exemplo
Dados de Entrada
Formato da saída

\--------------------------------------

**Aplicações Práticas da Engenharia de Prompts**

\--------------------------------------

Cuidados na aplicação de prompts

\--------------------------------------

Tomar cuidado no momento de escrever o prompt, para que não direcione para um erro já visualizado.

\--------------------------------------

Materiais de Apoio

Os materiais complementares e de apoio que oferecemos têm como objetivo fornecer informações para facilitar e enriquecer a sua jornada de aprendizado no curso "Introdução à Engenharia de Prompts". Aqui você encontrará links úteis, como slides, repositórios e páginas oficiais, além de dicas sobre como se destacar na DIO e no mercado de trabalho 😉
Recursos Adicionais

Durante este conteúdo, compreendemos os fundamentos da engenharia de prompts. Para ajudá-lo a aprofundar o conhecimento, disponibilizamos a seguir o material complementar contendo os conteúdos e links apresentados no curso:

    Transcrição das Aulas e Links Úteis - Introdução à Engenharia de Prompts: Acesse o link Introdução à Engenharia de Prompts para conferir a transcrição e o material apresentado no curso. É necessário estar logado na plataforma para conseguir acessar o link.

Dicas e Links Úteis

Para se desenvolver ainda mais e se destacar na DIO e no mercado de trabalho, sugerimos os seguintes recursos:

    Artigos e Fórum da DIO: Compartilhe seus conhecimentos e dúvidas através dos artigos (visíveis globalmente na plataforma da DIO) e nos fóruns específicos para cada experiência educacional, como nossos Bootcamps.
    Rooms: Participe do Rooms, uma ferramenta de bate-papo em tempo real onde você pode interagir com outros participantes dos nossos Bootcamps, compartilhando dúvidas, dicas e snippets de código.
    Exploração na Web: Utilize motores de busca para aprofundar seu conhecimento sobre temas específicos. Páginas como o StackOverflow são recursos valiosos para encontrar soluções e expandir seu entendimento.

Com esses materiais complementares, você estará bem equipado para explorar todo o potencial dos modelos de linguagem e se destacar em suas iniciativas de IA. Continue aproveitando as oportunidades de aprendizado, e não hesite em buscar mais conhecimento e compartilhar suas descobertas com a comunidade!


\--------------------------------------

**Técnicas de Engenharia de prompt**
\--------------------------------------

Componentes de prompt

\--------------------------------------
Instruções: 
Orientam o modelo sobre a tarefa a ser realizada, especificando o que fazer.

Exemplos (Few-shot learning): 
Apresentam pares de entrada e saida esperadas, mostrando ao modelo o comportamento ou formato ideal para a tarefa definida.

Tarefa: Classificar o sentimento de um texto.
Modelo de Exemplo: 
"Eu não gostei do produto!" . - > Negativo
"Eu adorei o produto!" - > Positivo
"Foi uma experiencia média." - > Neutro

Classifique o sentimento do seguinte texto: "Eu adoro essa praia!"

Contexto ou Configuração:
Define o papel do modelo e o cenário, como "voce é um assisten de IA que simplifica explicações técnicas para iniciantes em tecnologia."

Restrições ou limitações:
Limitam a resposta em termos de externsão ou escopo, como "Responda em até 50 Palavras, sem incluir opiniões ou dados ficticios."

Conteúdo Principal:
Texto central para processamento, como um paragrafo, tabela ou documento, que o modelo deve analisar, traduzir ou resumir.

Indicações:
Guiam o modelo para gerar saidas especificas, usando estimulos como ""listem pontos principais:" ou "Responda como um paragrafo unico."
EX: Resuma o Email Abaixo em formato de lista:
           (Corpo do Email)

Formato de Saida:
Especifica a forma da resposta, como "Apresente no formato JSON" ou "Liste os resultado como uma sequencia de topicos claros"

*Pedir tom da saida* : "Me explique o que é logica de programa como se eu fosse uma criança"

Conteúdo de suporte:
Dados extras que ajudam a tarefa, como datas ou preferências, por exemplo: "Use o contexto atual de dezembro de 2024 nas respostas."


**Técnicas de Engenharia de prompt**

Processo estratégico.

*Aplicando instruções  e repetição*

Instruções Clara:
Técnica que organiza o prompt para
que as orientações sejam objetivas,
detalhadas e colocadas no início
para maior clareza.

Exemplo: "Crie um endpoint POST
em Express.js que recebe um JSON
com um nome e retorna 'Olá,
<nome>!' em resposta."

Repetir Instruções no Final:
Reforça as orientações no final do
prompt para garantir que o modelo
compreenda e siga a tarefa proposta
sem desvios.

Entendendo a Guardrails:
Técnicas para limitar respostas,
evitando conteúdos prejudiciais,
irrelevantes ou incorretos, alinhando o
modelo a padrões éticos.

Exemplo: "Crie uma rota em
Express.js que valide o JSON
recebido e só aceite se o nome for
uma string com mais de 3
caracteres."

Preparando nosa Saída:
Define palavras ou frases no final do
prompt que ajudam a moldar o
formato da resposta, tornando-a mais
estruturada e clara.

Exemplo: "Crie um código para
configurar uma rota /status que
retorna {'status': 'ok'} no formato
JSON."

Solicitação de Cadeia de Pensamento:

Instrução para que o modelo
responda passo a passo, explicando
o raciocínio até chegar à conclusão
final.

Exemplo: "Explique passo a passo
como configurar uma API REST com
rotas GET e POST e como iniciar o
servidor."

Especificar Estrutura de Saída:

Indica o formato exato da resposta,
como JSON ou listas, ajudando a
obter resultados organizados e úteis.

Exemplo: "Liste o código para criar
uma API com um endpoint /hello que
retorna {'message': 'Hello, API!'} no
formato JSON.""

Dividir a Tarefa:

Quebra uma tarefa complexa em
várias etapas menores, facilitando
para o modelo responder de forma
lógica e organizada.

Exemplo: 

    Etapa 1: Explique como instalar o
    Express.js usando npm.

    Etapa 2: Crie um código inicial
    para configurar o servidor.

Adicionar Sintaxe Clara:

Organiza o prompt com formatações
como listas, títulos ou tabelas,
tornando as instruções mais visuais e
compreensíveis.

Exemplo: 

“SEÇÃO: Instalação  

npm install express  

SEÇÃO: Código Inicial  

const express = require('express');
const app = express();  

app.listen(3000, () =>
console.log('Servidor rodando'));”


Desafio:
Treinando uma IA de aprendizagem: Explore o poder do notebookLM

/////////////////////////////////////////////////////////////////////////////////////////
Introdução ao Excel 365
/////////////////////////////////////////////////////////////////////////////////////////

Pasta de trabalho - Workbook > Arquivo de Excel...
Planilhas - Worksheet/Sheets > Planilhas do Excel(Abas dentro do arquivo Excel)
Células - Cells > 
Intervalos - Ragers > Conjunto de celulas selecionadas
D6:G6 (Seleção do intervalo)
D6;G6 (Celulas especificas)
D5:G5;D6:G6 (Combinação de intervalos)

Congelamento de valor da celular (=SOMA ($D$4:)) "$ - CONGELAMENTO DE COLUNA OU LINHA"


**Trabalhando com Microsoft Copilot**
"Não usaras IA para fabricar Dados"

"Evite fabricar dados, sempre pedir para analisar os dados."

"Ferramenta de produtividade e não é ferramenta para fazer para você"

Biblioteca PANDA "Python"

Sempre forneça a base de conhecimento a knowledge base

Cuidado ao manipular dados, para não manibular dados sensiveis

**materiais de apoio DIO**

"Materiais de Apoio

Os materiais complementares e de apoio que oferecemos têm como objetivo fornecer informações para facilitar e enriquecer a sua jornada de aprendizado no curso "Trabalhando com Microsoft Copilot". Aqui você encontrará links úteis, como slides, repositórios e páginas oficiais, além de dicas sobre como se destacar na DIO e no mercado de trabalho 😉
Recursos Adicionais

Durante este conteúdo, compreendemos como trabalhar com o Microsoft Copilot. Para ajudá-lo a aprofundar o conhecimento, disponibilizamos a seguir o material complementar contendo links úteis:

    Microsoft Copilot: https://www.microsoft.com/pt-br/microsoft-copilot/personal-ai-assistant

Dicas e Links Úteis

Para se desenvolver ainda mais e se destacar na DIO e no mercado de trabalho, sugerimos os seguintes recursos:

    Artigos e Fórum da DIO: Compartilhe seus conhecimentos e dúvidas através dos artigos (visíveis globalmente na plataforma da DIO) e nos fóruns específicos para cada experiência educacional, como nossos Bootcamps.
    Rooms: Participe do Rooms, uma ferramenta de bate-papo em tempo real onde você pode interagir com outros participantes dos nossos Bootcamps, compartilhando dúvidas, dicas e snippets de código.
    Exploração na Web: Utilize motores de busca para aprofundar seu conhecimento sobre temas específicos. Páginas como o StackOverflow são recursos valiosos para encontrar soluções e expandir seu entendimento.

Com esses materiais complementares, você estará bem equipado para explorar todo o potencial do Microsoft Copilot. Continue aproveitando as oportunidades de aprendizado, e não hesite em buscar mais conhecimento e compartilhar suas descobertas com a comunidade!"

**Introdução aos Bancos de dados Relacionais**

https://github.com/Ewertonfontebasso/dio-bd-relacional

**Utilizando microsoft copilot para escrever consultas SQL**

**Criando um processo de ETL com Excel e power query**

Varios tratamentos no power query
Não consegui fazer devido ao fato de não ter o excel corporativo...


Quero que a IA analise avaliações de clientes sobre produtos vendidos em uma loja virtual para identificar problemas recorrentes, pontos positivos e oportunidades de melhoria.

O resultado será usado pela equipe de qualidade e pelo setor comercial para apoiar decisões sobre fornecedores e produtos.

A entrega deve conter um resumo executivo, uma tabela com os principais temas, exemplos de avaliações e recomendações de ações.

O resultado será considerado bom se for claro, organizado, objetivo e útil para melhorar a satisfação dos clientes.

Contexto: Estou trabalhando com avaliações e comentários de clientes relacionados a produtos vendidos em uma loja virtual de e-commerce.

Dados disponíveis: A base contém o nome do produto, categoria, nota da avaliação (1 a 5 estrelas), comentário do cliente, data da avaliação e status da compra (entregue, em transporte ou devolvida).

Critérios de análise: A IA deve classificar os feedbacks por temas (qualidade do produto, entrega, atendimento, preço e embalagem), sentimento (positivo, neutro ou negativo), nível de urgência e categoria do produto.