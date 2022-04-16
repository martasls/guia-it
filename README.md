###### **v1.0.0**
<p align="center">
  <img src="https://i.gifer.com/4lKv.gif" alt="rosa"/>
</p>

## 💻 O que é o IT

Neste momento, a questão que se coloca é… o que é que não é IT?

### 🏞️ Waterfall vs 🌡️ Agile

Waterfall tem fases bem definidas sendo que o início de uma fase apenas se dá quando a anterior está terminada. As fases são:

1. Levantamento de requisitos – qual o propósito do produto e que funcionalidades deve ter.

2. Desenho do sistema – desenho das especificações do sistema e interação entre os diferentes componentes.

3. Implementação – desenvolvimento do produto em si.

4. Testes – testes ao produto de maneira a encontrar potenciais erros.

5. Entrega – entrega do produto ao cliente.

6. Manutenção – depois do produto estar em produção pode ser necessário alterar funcionalidades, etc.

Por outro lado, numa abordagem agile, como o nome indica, o desenvolvimento de um produto é mais flexível, pois é feita por iterações e o que é um requisito hoje pode não ser amanhã.

#### Metodologias Agile:

Kanban – nesta abordagem as coisas não estão tão definidas. Há um desenvolvimento continuo sendo que as prioridades do projeto podem sofrer bastantes alterações. Parece um bocado que o projeto decorre ao sabor do vento.

Scrum – há roles bem estabelecidos e o desenvolvimento acontece em sprints (por exemplo duas semanas). Um sprint inicia-se com o sprint planning e termina com o sprint review. Há vários momentos nesta abordagem explicados de seguida:

#### 🤝 Os vários momentos do Scrum

Sprint planning – sessão para definir o(s) objetivo(s) do(s) sprint, respetivas user stories e tarefas/bugs.

Daily Standup – reunião em que cada membro da equipa faz um ponto de situação relativo ao seu trabalho.

Backlog refinement – tem como objetivo reorganizar o backlog, estimar esforço para as user stories em backlog e estabelecer prioridades.

Sprint review – acontece no final do sprint e serve para perceber se o objetivo do sprint foi cumprido e que user stories é que não foram fechadas e que vão ter de passar para o sprint seguinte.

Sprint retrospective – reflexão sobre pontos positivos e negativos relativos à forma como a equipa trabalhou durante o sprint. Definição de pontos de ação para melhorias no sprint seguinte.

OKRs planning – planeamento de OKRs (Objective Key Results) em que basicamente se definem objetivos gerais e sub objetivos para cada um destes com um valor de target que se espera atingir. Acontece no início de cada trimestre.

OKRs review + retrospective – No final de cada trimestre revêem-se os objetivos gerais e se estes foram atingidos. Reflete-se sobre o que correu bem durante o trimestre e pontos que podem ser melhorados no trimestre seguinte.

#### 🌍 Ambientes no desenvolvimento do produto  

No decorrer da implementação de um produto há, normalmente, vários ambientes como os definidos abaixo:

* Desenvolvimento: Como o nome indica este ambiente está sempre sob desenvolvimento. Sofre muitas alterações e como tal não é indicado para fazer testes pois novas modificações podem levar a que algo deixe de funcionar.

* Non production (disclaimer: isto pode ter outros nomes, mas é o nome que usamos no nosso projeto): Está entre o ambiente de desenvolvimento e de produção. Mais estável que o ambiente de desenvolvimento pois não sofre tantas alterações. É onde a maior parte da fase de testes ocorre.

* Production: Ambiente final, previamente testado, usado pelos utilizadores finais.

### 👩‍💻 Palavras e expressões chave

Deployment: significa que estamos a disponibilizar algo (uma aplicação por exemplo) para ser utilizado por alguém.

Release: quando se disponibiliza oficialmente o produto. Normalmente associa-se uma versão (1.0.0) para saber que funcionalidades e/ou melhorias estão sob a alçada desta.

Promover a aplicação para outro ambiente diferente daquele em que está: significa que a aplicação foi testada e tem luz verde para passar para o ambiente seguinte.

Testes de integração: testes que garantem que as várias componentes de uma aplicação, testadas previamente unitariamente, estão coesas e funcionam em conjunto.

Testes de regressão: testes que são feitos para assegurar que o que outrora funcionou continua a funcionar mesmo que tenha sofrido alterações.

Fazer commit (push de um commit): passar o código local para o repositório remoto (que é a ground truth do projeto).

Sandbox: um ambiente isolado dos outros para testar funcionalidades sem quebrar o que está deployed nos outros.


##### ℹ️ Fonte: vozes da minha cabeça