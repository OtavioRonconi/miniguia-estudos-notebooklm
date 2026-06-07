# 📘 Miniguia de Estudos: Introdução a Finanças Pessoais com NotebookLM

Bem-vindo ao repositório do meu Caderno Temático! Este projeto foi desenvolvido como parte do desafio da DIO, explorando o uso da Inteligência Artificial (Google NotebookLM) como ferramenta de aprendizagem ativa, curadoria de conhecimento e engenharia de prompts.

---

## 🎯 Contexto e Objetivos

**Assunto Escolhido:** Reserva de Emergência e Renda Fixa Básica.

A educação financeira é o primeiro passo para a estabilidade. O objetivo deste caderno é compilar os fundamentos de como organizar as finanças iniciais, entender o conceito de Reserva de Emergência e identificar quais produtos de Renda Fixa são adequados para esse propósito. 

**Objetivos de Estudo:**
1. Compreender o que é e como calcular uma Reserva de Emergência.
2. Diferenciar os principais indexadores da economia (Selic e CDI).
3. Identificar as melhores opções de investimento seguro e com alta liquidez.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM com informações precisas e confiáveis, foram selecionadas **3 fontes abertas** focadas em educação financeira básica. (Os documentos foram carregados no Notebook para as interações):

1. **[Cartilha de Educação Financeira da CVM]**: Material oficial da Comissão de Valores Mobiliários sobre conceitos básicos de poupança e investimentos.
2. **[Guia Tesouro Direto Oficial]**: Documentação pública sobre o funcionamento dos títulos do governo (foco no Tesouro Selic).
3. **[Artigo Educacional B3 - O que é Renda Fixa]**: Texto didático da bolsa brasileira sobre o funcionamento da Renda Fixa e a importância da liquidez.

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Ao interagir com o NotebookLM, testei diferentes abordagens para extrair o melhor conteúdo. Abaixo está o registro das tentativas, dificuldades e refinamentos.

| Tentativa | Prompt Utilizado | Resultado e "Cicatrizes" | Solução / Refinamento |
| :--- | :--- | :--- | :--- |
| **Teste 1 (Geral)** | *"Resuma os textos sobre renda fixa."* | **Ruim.** A IA gerou um texto longo, misturando conceitos complexos que não servem para um iniciante. | Percebi que precisava limitar o escopo da IA e pedir formatos específicos. |
| **Teste 2 (Direcionado)**| *"Com base apenas nos documentos anexados, defina o que é Reserva de Emergência e liste 2 investimentos ideais para ela."* | **Bom.** A resposta foi precisa, mas faltou explicar o "porquê" de cada investimento. | Adicionar uma instrução para justificar as escolhas usando o conceito de 'liquidez'. |
| **Teste 3 (Final)** | *"Aja como um professor de finanças. Liste em bullet points: 1) A regra de cálculo da reserva de emergência; 2) A diferença entre Selic e CDI; 3) Por que o Tesouro Selic e CDBs de liquidez diária são recomendados. Cite de qual fonte tirou cada informação."* | **Excelente.** Resposta bem estruturada, didática, fundamentada exclusivamente nos materiais carregados e com citações corretas. | O segredo foi definir um **papel (persona)**, usar **estruturas em lista** e exigir a **citação da fonte**. |

---

## 📖 Miniguia de Estudo: Reserva de Emergência e Renda Fixa

Abaixo, o resultado consolidado do estudo com o apoio da IA.

### 1. Resumos Estruturados

*   **O que é Reserva de Emergência?**
    É um montante financeiro guardado exclusivamente para cobrir imprevistos (perda de emprego, problemas de saúde, consertos urgentes).
    *   *Como calcular:* Deve cobrir de **6 a 12 meses** dos seus gastos fixos mensais (ex: se você gasta R$ 3.000/mês para viver, a reserva ideal para 6 meses é de R$ 18.000).
*   **Onde Guardar esse Dinheiro?**
    O foco aqui não é rentabilidade, mas sim **Segurança** e **Liquidez** (facilidade de resgate).
    *   *Tesouro Selic:* Título público do governo federal. Risco baixíssimo e pode ser resgatado a qualquer momento sem perda do valor investido.
    *   *CDB de Liquidez Diária (100% do CDI):* Título emitido por bancos. O dinheiro rende diariamente próximo à taxa básica de juros e pode ser sacado imediatamente.

### 2. Glossário de Conceitos

*   **Taxa Selic:** É a taxa básica de juros da economia brasileira, definida pelo Banco Central. Serve de referência para todas as outras taxas.
*   **CDI (Certificado de Depósito Interbancário):** É a taxa de juros utilizada em empréstimos entre os próprios bancos. Caminha quase colada na Taxa Selic e é o principal indicador de rentabilidade da Renda Fixa privada.
*   **Liquidez:** É a velocidade e facilidade com que você consegue transformar um investimento em dinheiro vivo na sua conta sem perder valor.
*   **CDB:** Certificado de Depósito Bancário. É um empréstimo que você faz a um banco em troca de juros.

### 3. Prompts Reutilizáveis para Futuras Revisões

Para continuar aprofundando os estudos ou revisar esse caderno no futuro, utilize os seguintes prompts no NotebookLM:

1.  **Revisão Rápida:** *"Me faça 3 perguntas de múltipla escolha sobre Selic e CDI baseadas nos documentos, e só forneça o gabarito depois que eu responder."*
2.  **Aprofundamento:** *"Considere o conceito de CDB apresentado na Fonte 3. Quais são os riscos envolvidos nesse investimento caso o banco declare falência?"*
3.  **Analogias Didáticas:** *"Explique o conceito de 'Liquidez Diária' usando uma analogia com situações do dia a dia, para que alguém que nunca estudou finanças consiga entender facilmente."*

---
*Projeto desenvolvido para o desafio da plataforma DIO.*
