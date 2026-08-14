# 📘 Miniguia de Estudos: Como Funciona a Renda Fixa

> Projeto prático desenvolvido para o desafio da **Digital Innovation One (DIO)**, utilizando o **NotebookLM** para curadoria de conhecimento, aprendizagem ativa e engenharia de prompts.

---

## 🔗 Acesse o Caderno no NotebookLM

Você pode navegar diretamente pelo caderno interativo criado para este projeto através do link abaixo:

👉 **[Clique aqui para acessar o Caderno no NotebookLM](https://notebook.google.com/notebook/1f141760-f53a-4cf8-88e5-e887a199656d)**


---

## 🎯 Contexto e Objetivos

* **Tema Escolhido:** Como Funciona a Renda Fixa (Conceitos Básicos, Títulos Públicos e Privados e Indicadores Financeiros).
* **Objetivos de Estudo:** 
  1. Compreender o conceito fundamental de Renda Fixa e a diferença entre títulos públicos e privados.
  2. Analisar como a Taxa Selic, o CDI e a Inflação (IPCA) impactam a rentabilidade das aplicações.
  3. Compreender os mecanismos de proteção ao investidor, como o Fundo Garantidor de Créditos (FGC).
  4. Explorar a IA como ferramenta de aprendizagem ativa e engenharia de prompts.

---

## 📚 Curadoria de Fontes

Relação de materiais abertos e oficiais inseridos no NotebookLM:

1. 📄 **Caderno de Cidadania Financeira** - *Banco Central do Brasil (BCB)* - [Acessar Portal](https://www.bcb.gov.br/)
2. 📄 **Guia Oficial do Tesouro Direto** - *Secretaria do Tesouro Nacional* - [Acessar Tesouro Direto](https://www.tesourodireto.com.br/)
3. 📄 **Guia de Produtos de Renda Fixa** - *Comissão de Valores Mobiliários (CVM)* - [Acessar Portal do Investidor](https://www.investidor.gov.br/)
4. 📄 **Mecanismo de Proteção e Garantia ao Investidor** - *Fundo Garantidor de Créditos (FGC)* - [Acessar FGC](https://www.fgc.org.br/)

---

## 🔬 Engenharia de Prompts & "Cicatrizes" (Troubleshooting)

### 🧪 Testes de Prompts
* **Pergunta Estratégica 1:** O que é o FGC e quais produtos ele cobre?
  * **Prompt v1 (Simples):** `"O que é FGC e o que ele cobre?"`
  * **Resultado v1:** A IA deu uma resposta curta e genérica sobre proteção bancária, sem citar valores e sem especificar os limites por CPF.
  * **Prompt v2 (Refinado):** `"Atuando como um educador financeiro, explique o conceito de FGC com base nas fontes fornecidas. Apresente em tópicos: o que é, o limite de cobertura por CPF e por instituição, e quais produtos de Renda Fixa possuem essa garantia."`
  * **Resultado v2:** Resposta bem estruturada, citando com precisão o teto de R$ 250.000,00 por CPF/instituição, detalhando a isenção em títulos públicos e fornecendo citações diretas das fontes.

### 🩹 Cicatrizes e Aprendizados (Troubleshooting)
* **Desafio Encontrado:** Ao perguntar sobre rentabilidade dos títulos do Tesouro, a IA misturou conceitos gerais da internet em vez de focar estritamente nas regras dos documentos carregados.
* **Como Solucionei:** Adicionei ao prompt o comando de restrição: *"Responda utilizando exclusivamente as informações presentes nas fontes do caderno"*, garantindo respostas fiéis e sem alucinações.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 1. Resumos Estruturados

* **O que é Renda Fixa e Modalidades de Rendimento:**
  A Renda Fixa é uma modalidade de investimento na qual o investidor "empresta" dinheiro para um emissor (Governo, bancos ou empresas) em troca de uma remuneração com regras definidas no momento da aplicação.
  * **Pré-fixada:** A taxa de juros é fixa desde o início (ex.: 10% ao ano).
  * **Pós-fixada:** A rentabilidade segue um indexador econômico (ex.: 100% do CDI ou Taxa Selic).
  * **Híbrida:** Combina uma taxa fixa com um índice de inflação (ex.: IPCA + 6% ao ano).

* **Títulos Públicos vs. Títulos Privados:**
  * **Títulos Públicos (Tesouro Direto):** Emitidos pelo Tesouro Nacional para financiar investimentos públicos. Considerados os investimentos de menor risco de crédito do país (*Risco Soberano*).
  * **Títulos Privados Bancários (CDB, LCI, LCA):** Emitidos por instituições financeiras para captar recursos. Destaque: LCI e LCA possuem isenção de Imposto de Renda para pessoas físicas.

* **Mecanismos de Segurança (FGC):**
  * **Limite de Cobertura:** Até **R$ 250.000,00 por CPF/CNPJ e por instituição financeira** (com teto global de R$ 1.000.000,00 a cada 4 anos).
  * **Produtos Cobertos:** Poupança, CDB, RDB, LCI, LCA. Títulos públicos **não** dependem do FGC, pois contam com a garantia direta do Governo Federal.

---

### 📕 2. Glossário de Conceitos

* **Taxa Selic:** Taxa básica de juros da economia brasileira, definida pelo COPOM/Banco Central.
* **CDI (Certificado de Depósito Interbancário):** Taxa de juros dos empréstimos entre bancos, usada como referência principal para investimentos pós-fixados.
* **IPCA:** Índice oficial de inflação no Brasil.
* **FGC:** Entidade privada que protege investidores de renda fixa em caso de falência ou liquidação da instituição financeira.
* **Liquidez:** A facilidade e rapidez com que um investimento pode ser resgatado e convertido em dinheiro disponível.

---

### 🚀 3. Banco de Prompts Reutilizáveis

1. 🔹 **Prompt de Revisão Rápida:**
   > *"Atuando como um professor de finanças, elabore um resumo em tópicos com os pontos mais importantes sobre [Inserir Tópico], destacando funcionamento, vantagens, riscos e tributação com base nos documentos do caderno."*

2. 🔹 **Prompt de Simulado / Teste de Fixação:**
   > *"Com base no material fornecido, crie 5 questões de múltipla escolha sobre Renda Fixa (com foco em Selic, CDI e FGC). Inclua o gabarito ao final com justificativas fundamentadas nos textos."*

3. 🔹 **Prompt Comparativo em Tabela:**
   > *"Crie uma tabela comparativa entre CDB e Tesouro Selic detalhando: Emissor, Rentabilidade, Liquidez, Risco, Cobertura pelo FGC e Incidência de Imposto de Renda."*
