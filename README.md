# 💸 FinanZen AI — Organização de Finanças Pessoais com IA

## 📌 Resumo do Projeto

O **FinanZen AI** é o conceito de um aplicativo de organização de finanças pessoais que utiliza inteligência artificial para tornar o registro financeiro mais simples e natural.

Em vez de depender de planilhas ou diversos formulários, o usuário pode conversar com um assistente financeiro e registrar informações usando frases como:

> "Gastei R$ 45 no supermercado."

A aplicação interpreta a mensagem, identifica o valor, sugere uma categoria e registra a transação.

O MVP foi pensado principalmente para pessoas iniciantes em organização financeira e possui como foco o registro de receitas e despesas, classificação automática, criação de metas e visualização de resumos simples.

---

# 🤖 Prompt Final — PRD

## 1. Contexto

Quero criar um aplicativo mobile/web de organização de finanças pessoais que permita ao usuário gerenciar suas finanças por meio de uma conversa em linguagem natural com um assistente de IA.

A ideia é facilitar o registro de receitas, despesas e metas sem exigir planilhas complexas ou muitos campos manuais.

## 2. Problema

Usuários iniciantes podem encontrar dificuldades para organizar gastos e receitas porque:

- precisam registrar informações manualmente;
- podem ter dificuldade para categorizar transações;
- ferramentas financeiras podem apresentar informações de maneira complexa.

O **FinanZen AI** pretende reduzir esse atrito utilizando uma experiência baseada em conversa.

## 3. Público-Alvo

- Pessoas iniciantes em organização financeira;
- usuários que procuram uma experiência simples;
- pessoas que não querem utilizar planilhas complexas;
- usuários que preferem conversar em vez de preencher vários campos estruturados.

## 4. Funcionalidades-Chave do MVP

1. **Registrar despesas via chat**  
   O usuário pode escrever mensagens como:

   > "Gastei R$ 45 no supermercado."

2. **Registrar receitas via chat**  
   Exemplo:

   > "Recebi R$ 2.000 de salário."

3. **Classificação automática de transações**  
   O assistente sugere categorias como alimentação, transporte, lazer ou salário com base na mensagem.

4. **Metas financeiras**  
   Permitir criar, editar e acompanhar metas.

   Exemplo:

   > "Quero guardar R$ 500 em três meses."

5. **Resumos simples**  
   Exibir rapidamente entradas, saídas e o progresso das metas.

## 5. Comportamento do Assistente Financeiro

O assistente deverá:

- utilizar um tom amigável e educativo;
- responder de forma simples e direta;
- confirmar valor, data e categoria ao registrar uma transação;
- permitir que o usuário corrija informações identificadas incorretamente;
- ajudar na compreensão dos dados financeiros registrados.

O assistente não deverá se apresentar como consultor financeiro profissional.

## 6. Fluxo Principal

### Tela de Boas-vindas

Apresenta o aplicativo e possui o botão:

**Começar**

↓

### Chat

Principal interface do aplicativo.

O usuário registra receitas ou despesas por meio de mensagens em linguagem natural.

↓

A partir do Chat, o usuário pode acessar:

**Metas**

ou

**Resumo**

### Metas

Permite criar e acompanhar metas financeiras.

Após utilizar essa área, o usuário pode retornar ao Chat.

### Resumo

Apresenta uma visão simples de:

- receitas;
- despesas;
- progresso das metas.

Depois, o usuário retorna ao Chat.

### Fluxo resumido

Boas-vindas → Chat ↔ Metas  
               ↕  
             Resumo

## 7. Entregável Esperado da IA

Com base neste PRD, a IA deve:

- sugerir um plano para o MVP;
- definir o fluxo das telas;
- descrever o comportamento do assistente financeiro;
- propor a lógica de classificação das transações;
- identificar possíveis pontos de fricção;
- sugerir uma validação inicial simples.

A IA não deve escrever código nem aumentar o escopo definido para o MVP.

---

# 📸 Interações com IA

Durante o desenvolvimento do conceito, utilizei o **Google Antigravity** para organizar e refinar o MVP e o fluxo do FinanZen AI.

## 1. Definição do MVP

Nesta interação, a IA ajudou a organizar as principais funcionalidades do MVP e separar funcionalidades futuras.

![Definição do MVP](./images/01-mvp.png)

## 2. Refinamento da solução

Após a primeira resposta, foram realizados ajustes para manter o projeto dentro do escopo proposto e melhorar a definição do assistente financeiro.

![Refinamento da solução](./images/02-refinamento.png)

## 3. Fluxo conceitual das telas

A IA também foi utilizada para estruturar o caminho do usuário entre as telas do MVP.

![Fluxo de telas - Parte 1](./images/03-fluxo-parte1.png)

![Fluxo de telas - Parte 2](./images/04-fluxo-parte2.png)

---

# 💭 Reflexão sobre o Processo

## O que funcionou bem?

Dar contexto e definir claramente o que a IA deveria fazer tornou as respostas mais organizadas e úteis.

Também funcionou bem dividir o projeto em partes menores, começando pelo MVP, depois refinando o PRD e finalmente criando o fluxo das telas.

## O que não funcionou como esperado?

Em algumas respostas, a IA sugeriu funcionalidades ou detalhes que estavam além do escopo inicial do MVP.

Foi necessário enviar novas instruções para limitar o projeto e separar funcionalidades principais de ideias para versões futuras.

## O que aprendi sobre conversar com IAs?

Aprendi que a qualidade do resultado depende bastante da clareza do prompt.

Também percebi que não é necessário aceitar a primeira resposta da IA. É possível revisar, pedir ajustes e evoluir a solução em várias interações.

O processo mostrou na prática como o **Vibe Coding** pode ser usado para transformar uma ideia inicial em um conceito de produto mais estruturado por meio da colaboração com inteligência artificial.
