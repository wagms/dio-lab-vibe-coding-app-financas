# 💸 FinZen — App de Organização de Finanças Pessoais com Vibe Coding

Projeto conceitual criado no desafio **Vibe Coding** da DIO (trilha Riachuelo — Criando Produtos com IA), a partir do repositório-base [dio-lab-vibe-coding-app-financas](https://github.com/digitalinnovationone/dio-lab-vibe-coding-app-financas).

---

## 📌 Resumo do App

**FinZen** é o conceito de um app de organização de finanças pessoais que funciona por conversa: o usuário registra gastos e tira dúvidas sobre suas próprias finanças em linguagem natural, sem preencher planilhas ou formulários longos. Um "Agente Financeiro" categoriza as transações automaticamente, acompanha metas de orçamento e entrega, toda semana, um resumo em texto simples com sugestões de economia — tirando do usuário o trabalho manual que faz a maioria das pessoas desistir de controlar as finanças.

**Funcionalidades-chave do MVP:**

1. Registrar gastos via chat em linguagem natural.
2. Classificar automaticamente as transações por categoria.
3. Definir e acompanhar metas financeiras por categoria.
4. Receber dicas de economia do "Agente Financeiro" (resumo semanal).
5. Visualizar relatórios simples e personalizados (dashboard enxuto).

---

## 🧠 Prompt Final (PRD)

```
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
4. Receber dicas de economia do "Agente Financeiro".
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.
Usar tom educativo e linguagem acessível, em português.
```

---

## 💬 Interações com a IA

> As respostas abaixo foram geradas a partir do prompt acima. Antes de publicar, recomenda-se rodar o mesmo prompt no Copilot Web e/ou no Lovable e substituir por prints/vídeos reais dessas interações (o desafio pede evidência da sua própria conversa com a ferramenta).

### Agente Financeiro (tom de voz)

> "Oi! Sou seu Agente Financeiro. Meu trabalho é entender seus gastos sem te dar trabalho: você me conta o que gastou como conta pra um amigo, e eu organizo tudo. Sem julgamento, sem planilha — só clareza pra você decidir onde quer economizar."

Tom: acolhedor, direto, sem linguagem que gere culpa financeira.

### Fluxo de Telas (conceitual)

1. **Chat principal** — campo único onde o usuário registra gastos ("gastei 45 no mercado") ou faz perguntas ("quanto gastei com transporte esse mês?").
2. **Dashboard** — saldo do mês, entradas x saídas, comparação com o mês anterior.
3. **Metas** — lista de categorias com limite definido pelo usuário e barra de progresso do gasto atual.
4. **Resumo semanal** — tela/notificação com o texto gerado pelo Agente Financeiro, com 1 a 2 sugestões práticas de economia.

### Plano de MVP (resumo)

- **Recursos necessários:** processamento de linguagem natural para extrair valor/categoria da mensagem do usuário; base de regras (ou modelo simples) para categorização automática; armazenamento de transações e metas por usuário.
- **Validação inicial:** protótipo testado com 5 a 10 usuários reais por 2 semanas, medindo se eles continuam registrando gastos sem abandonar (métrica: nº de registros por semana) e se o resumo semanal é lido/considerado útil.

---

## 🔎 Reflexão sobre o Processo

**O que funcionou bem:** escrever o PRD antes de pedir qualquer coisa pra IA mudou o resultado — descrever problema, público e funcionalidades logo de início evitou respostas genéricas e manteve as sugestões (fluxo de telas, tom do agente) alinhadas com a intenção original do app.

**O que não funcionou como o esperado:** pedir tudo de uma vez ("cria o app inteiro") tende a gerar respostas rasas; funcionou melhor quebrar o pedido em partes menores (agente, fluxo de telas, plano de MVP) e pedir uma de cada vez, especialmente pensando no limite de interações do plano gratuito do Lovable.

**O que aprendi sobre conversar com IAs:** o formato da pergunta importa tanto quanto o conteúdo — pedir explicitamente "gere o fluxo de telas" ou "resuma em 5 funcionalidades" produz algo acionável, enquanto pedir só "o que você acha da ideia?" produz opinião solta, sem nada que vire de fato um próximo passo do produto.
