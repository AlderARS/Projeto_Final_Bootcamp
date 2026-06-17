## 📁 Dados e Fontes de Conhecimento

### 1. Dados no NotebookLM (Inteligência Financeira)
Os dados de inteligência financeira e base especializada para respostas técnicas do Fince estão centralizados no NotebookLM.
* **Link de acesso à base:** [NotebookLM - Fince](https://notebooklm.google.com/notebook/bbbd5c4a-6356-4855-842a-d4628cbb44f2)

| Arquivo | Formato | Para que serve no Fince |
| :--- | :--- | :--- |
| **Audiobooks** | MP4 | Base especializada contendo audiobooks sobre finanças. |
| **Canais_Youtube** | MP4 | Compilação de 5 mil vídeos sobre finanças para aprofundar o conhecimento. |

#### Canais e Vídeos de Referência Integrados na Base do NotebookLM:
* **Canais de Finanças do YouTube:**
  * [@GustavocerbasiBr](https://www.youtube.com/@GustavocerbasiBr)
  * [@MePoupe](https://www.youtube.com/@MePoupe)
  * [@primorico](https://www.youtube.com/@primorico)
  * [@jovensdenegocios](https://www.youtube.com/@jovensdenegocios)
  * [@brunoperini](https://www.youtube.com/@brunoperini)
  * [@economistasincero](https://www.youtube.com/@economistasincero)
* **Vídeos Audiobooks específicos para consulta:**
  * [Vídeo Audiobook 1](https://www.youtube.com/watch?v=RHblgzezekU)
  * [Vídeo Audiobook 2](https://www.youtube.com/watch?v=4_ULQHN2dLg)
  * [Vídeo Audiobook 3](https://www.youtube.com/watch?v=SHRoWWR4fPY)
  * [Vídeo Audiobook 4](https://www.youtube.com/watch?v=a5_xFbPTJD4)

### 2. Dados teste simulando controle financeiro ideal
Para testar a inteligência do Fince, utilizamos uma massa de dados fictícios locais:

| Arquivo | Formato | Para que serve no Fince |
| :--- | :--- | :--- |
| **fince_dados_teste** | CSV | Testar as funcionalidades de reconhecimento, análise de padrões e recomendações do Fince. |

> [!NOTE]
> O arquivo `fince_dados_teste.csv` contém **1.000 linhas de dados fictícios gerados por I.A.**, seguindo rigorosamente a estrutura de colunas e categorizações definidas neste documento.

---

## 🔄 Estratégia de Integração
* **Tabela de Finanças Pessoais (Local):** Salva localmente pelo agente (na memória do sistema). Se nenhum arquivo compatível for enviado pelo usuário na primeira conversa, o Fince cria uma planilha automaticamente a partir das perguntas do Onboarding.
* **Inteligência e Educação Financeira:** Consultas a dúvidas conceituais, dicas de livros ou conteúdos aprofundados são enviadas e respondidas com apoio da base externa hospedada no [NotebookLM](https://notebooklm.google.com/notebook/bbbd5c4a-6356-4855-842a-d4628cbb44f2).

---

## 🧪 Exemplo de Contexto e Validação
Primeiras 5 linhas extraídas diretamente da base de dados `fince_dados_teste.csv`:

```csv
Data;Tipo;Categoria;Subcategoria;Descrição;Valor;Método de Pagamento
03/06/2025;Receita;Receita;Salário;Salário Mensal Empresa;5500,00;Pix
04/06/2025;Despesa;Estilo de Vida e Lazer;Cuidados Pessoais;Mensalidade Academia;114,24;Cartão de Crédito
06/06/2025;Investimento;Futuro e Investimentos;Investimentos;Aporte Mensal Tesouro Selic;485,00;Pix
09/06/2025;Despesa;Gastos Essenciais;Alimentação;Supermercado BH;335,65;Cartão de Crédito
```

---
