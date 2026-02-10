# 📌 PRD – App de Finanças Pessoais Conversacional com Vibe Coding

## Visão Geral
-  Objetivo: criar um aplicativo de finanças pessoais simples e prático.  
- **Proposta de valor:** ajudar os usuários a organizar gastos e metas de forma rápida e natural.  

## Problema
- Aplicativos atuais exigem muita entrada manual.  
- Pouca personalização e experiência engessada.  
- Usuários iniciantes desistem por falta de praticidade.  

## Público-Alvo
- Pessoas que querem começar a organizar suas finanças sem complicação.  
- Usuários iniciantes que buscam uma solução rápida e acessível.  

## Funcionalidades-Chave
- Registrar gastos via chat em linguagem natural.  
- Classificar automaticamente as transações.  
- Definir e acompanhar metas financeiras.  
- Receber dicas de economia do **Agente Financeiro**.  
- Visualizar relatórios simples e personalizados.  

---

## 🖼️ Imagens das Interações



### Simulação em HTML/CSS

https://copilot.microsoft.com/th/id/BCO.fd16c0fe-8199-4253-b5f5-26873f6779c2.png




## 🚀 Roadmap – App de Finanças Pessoais

### Fase 1 – MVP
- Chat em linguagem natural.  
- Classificação automática de gastos.  
- Tela de resumo semanal.  

### Fase 2 – Metas Financeiras
- Definição de metas.  
- Acompanhamento com notificações.  

### Fase 3 – Relatórios e Dicas
- Relatórios simples e gráficos básicos.  
- Recomendações personalizadas do Agente Financeiro.  

### Fase 4 – Expansão
- Integração com bancos e Pix.  
- Personalização avançada de relatórios.  
- Recursos de comunidade.  

---

## 💻 Código da Tela (Simulação do Chat)

A tela abaixo foi construída com HTML e CSS e simula a interação com o **Agente Financeiro**:

![Tela do Chat](attachments/simulacao.png)

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Agente Financeiro</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f9;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .chat-container {
      width: 400px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .chat-header {
      background: #4CAF50;
      color: #fff;
      padding: 10px;
      border-radius: 8px 8px 0 0;
      text-align: center;
      font-weight: bold;
    }
    .chat-box {
      padding: 15px;
      height: 300px;
      overflow-y: auto;
    }
    .message {
      margin: 10px 0;
      padding: 8px;
      border-radius: 5px;
      max-width: 80%;
    }
    .message.bot {
      background: #e0f7e9;
      align-self: flex-start;
    }
    .message.user {
      background: #d0e7ff;
      align-self: flex-end;
      text-align: right;
    }
    .chat-input {
      display: flex;
      border-top: 1px solid #ddd;
    }
    .chat-input input {
      flex: 1;
      padding: 10px;
      border: none;
      border-radius: 0 0 0 8px;
    }
    .chat-input button {
      padding: 10px;
      border: none;
      background: #4CAF50;
      color: #fff;
      border-radius: 0 0 8px 0;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="chat-container">
    <div class="chat-header">💬 Agente Financeiro</div>
    <div class="chat-box">
      <div class="message bot">Olá! Sou seu agente financeiro. Deseja registrar um gasto?</div>
      <div class="message user">Sim, comprei um café por R$ 8,00.</div>
      <div class="message bot">Gasto registrado na categoria: Alimentação ☕</div>
    </div>
    <div class="chat-input">
      <input type="text" placeholder="Digite sua mensagem...">
      <button>Enviar</button>
    </div>
  </div>


# 📌 PRD – App de Finanças Pessoais Conversacional

## Visão Geral
- **Objetivo:** criar um aplicativo de finanças pessoais simples e prático.  
- **Proposta de valor:** ajudar os usuários a organizar gastos e metas de forma rápida e natural.  

## Problema
- Aplicativos atuais exigem muita entrada manual.  
- Pouca personalização e experiência engessada.  
- Usuários iniciantes desistem por falta de praticidade.  

## Público-Alvo
- Pessoas que querem começar a organizar suas finanças sem complicação.  
- Usuários iniciantes que buscam uma solução rápida e acessível.  

## Funcionalidades-Chave
- Registrar gastos via chat em linguagem natural.  
- Classificar automaticamente as transações.  
- Definir e acompanhar metas financeiras.  
- Receber dicas de economia do **Agente Financeiro**.  
- Visualizar relatórios simples e personalizados.  

---

## 🖼️ Imagens das Interações

### Interação com Copilot
![Interação com Copilot](attachments/copilot.png)

### Simulação em HTML/CSS
![Simulação de Tela](attachments/simulacao.png)

---

## 🚀 Roadmap – App de Finanças Pessoais

### Fase 1 – MVP
- Chat em linguagem natural.  
- Classificação automática de gastos.  
- Tela de resumo semanal.  

### Fase 2 – Metas Financeiras
- Definição de metas.  
- Acompanhamento com notificações.  

### Fase 3 – Relatórios e Dicas
- Relatórios simples e gráficos básicos.  
- Recomendações personalizadas do Agente Financeiro.  

### Fase 4 – Expansão
- Integração com bancos e Pix.  
- Personalização avançada de relatórios.  
- Recursos de comunidade.  

---

## 💻 Código da Tela (Simulação do Chat)

A tela abaixo foi construída com HTML e CSS e simula a interação com o **Agente Financeiro**:

![Tela do Chat](attachments/simulacao.png)

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Agente Financeiro</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f9;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .chat-container {
      width: 400px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .chat-header {
      background: #4CAF50;
      color: #fff;
      padding: 10px;
      border-radius: 8px 8px 0 0;
      text-align: center;
      font-weight: bold;
    }
    .chat-box {
      padding: 15px;
      height: 300px;
      overflow-y: auto;
    }
    .message {
      margin: 10px 0;
      padding: 8px;
      border-radius: 5px;
      max-width: 80%;
    }
    .message.bot {
      background: #e0f7e9;
      align-self: flex-start;
    }
    .message.user {
      background: #d0e7ff;
      align-self: flex-end;
      text-align: right;
    }
    .chat-input {
      display: flex;
      border-top: 1px solid #ddd;
    }
    .chat-input input {
      flex: 1;
      padding: 10px;
      border: none;
      border-radius: 0 0 0 8px;
    }
    .chat-input button {
      padding: 10px;
      border: none;
      background: #4CAF50;
      color: #fff;
      border-radius: 0 0 8px 0;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="chat-container">
    <div class="chat-header">💬 Agente Financeiro</div>
    <div class="chat-box">
      <div class="message bot">Olá! Sou seu agente financeiro. Deseja registrar um gasto?</div>
      <div class="message user">Sim, comprei um café por R$ 8,00.</div>
      <div class="message bot">Gasto registrado na categoria: Alimentação ☕</div>
    </div>
    <div class="chat-input">
      <input type="text" placeholder="Digite sua mensagem...">
      <button>Enviar</button>
    </div>
  </div>
</body>
</html>

## Através do código a interação das telas, fica mais fácil através do copilot


Reflexão e Aprendizado com IA
Funcionou bem: estrutura clara do PRD, uso de linguagem natural, inclusão de acessibilidade.

Não funcionou como esperado: métricas de sucesso difíceis de definir, termos técnicos precisaram ser simplificados.

Aprendizado: conversar com IA ajuda a organizar ideias, mas é essencial dar contexto claro e ajustar pedidos para refinar resultados.

O que aprendi sobre conversar com IAs
Aprendi que devemos detalhar praticamente tudo para que a IA entregue o resultado pronto.
Se não houver interação, a IA também não entende exatamente o que queremos para nossos projetos.


