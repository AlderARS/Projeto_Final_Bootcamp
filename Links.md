# 📊 Apresentação e Fluxo do Projeto

## 🎯 Apresentação do Projeto

Os slides utilizados na apresentação do projeto foram desenvolvidos utilizando o Gamma:

🔗 **Slides da Apresentação:**
https://gamma.app/docs/Fince-Seu-Mentor-Financeiro-Inteligente-ccnebyepfbnf8bd

---

## 📚 Base de Conhecimento

A base de conhecimento utilizada pelo agente foi construída e organizada no NotebookLM, servindo como fonte de contexto para respostas e recomendações financeiras.

🔗 **Acessar Base de Conhecimento:**
https://notebooklm.google.com/notebook/bbbd5c4a-6356-4855-842a-d4628cbb44f2

---

## ⚙️ Workflow no n8n

O fluxo abaixo representa a arquitetura de automação do projeto, responsável por integrar o usuário, o Telegram, o agente de IA e os demais componentes da solução.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3851b97d-cd79-4314-9a0e-7fe67ae4f884" alt="Workflow n8n do Projeto Fince" width="100%">
</p>

### Fluxo Geral

1. O usuário interage com o sistema através do Telegram.
2. O n8n recebe e processa a solicitação.
3. O agente Fince interpreta a intenção do usuário.
4. As informações necessárias são consultadas na base de conhecimento.
5. O sistema gera uma resposta personalizada.
6. O resultado é enviado de volta ao usuário.

---

> O Fince combina educação financeira, definição de metas, acompanhamento de gastos e inteligência artificial para auxiliar usuários na construção de hábitos financeiros mais saudáveis.
