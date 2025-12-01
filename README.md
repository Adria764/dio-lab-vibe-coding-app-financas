# 💸 App de controle de Financeiro com Vibe Coding

PRD revisado no copilot web:

´´´´ markdown

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

> Interações com o lovable

> Crie um App de Finanças Pessoais com base no seguinte PRD: (Documento de Requisitos de Produto) {PRD}
> Tentei criar uma meta chamada Reserva de Emergencia mas ela não apareceu no componente. A impressão de tive foi que apenas o Assistente Financeiro a reconheceu, poderia verificar?

> Resultado final no lovable
> https://lovable.dev/projects

> <img width="914" height="587" alt="image" src="https://github.com/user-attachments/assets/c615baac-a466-45bd-b892-0241fbc23db4" />

# 📱 Minhas Finanças – MVP

## 🎯 Objetivo
Criar um aplicativo de **Organização de Finanças Pessoais** que funcione por meio de **conversas naturais** com o usuário.  
A proposta é simplificar o controle financeiro, eliminando formulários e planilhas complexas.

---

## ❗ Problema
A maioria dos apps de finanças exige **muita entrada manual** e oferece **pouca personalização**, o que desmotiva os usuários iniciantes.  
Este projeto busca resolver isso com uma **experiência conversacional** e **recomendações automáticas** de economia.

---

## 👥 Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma **prática e sem complicação**, especialmente **iniciantes**.

---

## 🔑 Funcionalidades-Chave
1. Registrar gastos via **chat em linguagem natural**.
2. **Classificação automática** das transações.
3. Definir e acompanhar **metas financeiras**.
4. Receber **dicas de economia** do “Agente Financeiro”.
5. Visualizar **relatórios simples e personalizados**.

---

## 🛠️ Plano de MVP

### 📱 Telas Principais

| Tela                     | Descrição                                                                 |
|--------------------------|---------------------------------------------------------------------------|
| **Boas-Vindas**          | Apresenta o propósito do app e convida o usuário a iniciar uma conversa. |
| **Chat Financeiro**      | Interface principal para registrar gastos, metas e receber dicas.         |
| **Resumo Financeiro**    | Mostra receitas, despesas e saldo atual de forma visual e simples.        |
| **Transações**           | Lista de gastos e ganhos com classificação automática.                    |
| **Metas Financeiras**    | Permite criar metas e acompanhar o progresso.                             |
| **Relatórios Personalizados** | Gráficos e insights gerados com base nas conversas e hábitos.     |

---

### ⚙️ Recursos Essenciais

- **PLN (Processamento de Linguagem Natural):** Para entender frases como “gastei 50 reais com mercado”.
- **Classificação Inteligente:** Categoriza automaticamente os gastos.
- **Motor de Metas:** Acompanha objetivos como “economizar R$ 500 até o fim do mês”.
- **Agente Financeiro com IA:** Envia dicas personalizadas com base no comportamento do usuário.
- **Sistema de Relatórios:** Gera visualizações simples com base nas transações registradas.

---

## ✅ Validação Inicial

**Objetivo:** Verificar se usuários iniciantes conseguem usar o app sem tutoriais complexos.

**Etapas:**
- Teste com 10 a 20 usuários iniciantes.
- Métricas observadas:
  - Facilidade de registrar gastos via chat.
  - Clareza dos relatórios.
  - Engajamento com metas e dicas.
- Feedback qualitativo:
  - O que foi intuitivo?
  
   **Reflexão:
  
  - O que funcionou bem?
  - O Refinamento do PRD previamente feito no copilot ajudou muito, pois os créditos no lovable acabaram em apenas duas interações.
 
  - O que não funcionou como o esperado?
  - Na interação eu pedi para que o App tivesse a funcionalidade de Metas (que ele criasse as metas), mas devido a pouca quantidade de créditos eu não consegui interagir para corrigir essa funcionalidade.
    
  - O que aprendeu sobre conversar com IAs?
  - Aprendi que é basicamente como conversar com uma pessoa, quanto mais detalhes você dá melhor será a interação. Gostei bastante na interação com a IA.


