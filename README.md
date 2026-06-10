# FIIs Analytics Agents

### PT-BR

1. O usuário consegue fazer pesquisas por tickers individuais ou mais de um por vez;
   1. Traz os dados do yFinance (Abertura, Fechamento, Dividendos, Preços, Data);
   2. Busca notícias da internet;
      1. Salva essas informações no banco de dados;
   3. É possível alimentar a base de dados com PDFs, PowerPoints, Docx, etc.
   4. Faz uma análise de dados utilizando indicadores financeiros pertinentes;
      1. Monta gráficos interativos ÚTEIS para análise de compra e venda baseado nos indicadores;


2. O usuário consegue fazer pesquisas de texto por exemplo:
   * Quais são as últimas notícias sobre FIIs?
   * Quais são os FIIs mais indicados para compra atualmente?
   * Analise o fundo {{FUNDO}} 
   1. A partir disso, o agente vai agregar contexto "marretado";
   2. Buscar na base de dados;
   3. Busca notícias na internet;
      1. Salva essas informações no banco de dados;
   4. Busca os tickers? -> Dependendo da pergunta;
      1. Se houver tickers, faz uma analise financeira com gráficos e tabelas;
   5. Se não houver tickers, faz apenas uma análise textual;

---

### Próximos passos:
**Teoria FIIs**<br/>
* O que eu devo levar em consideração ao analisar um FIIs?
* Quais são os indicadores financeiros adequados?
* Quais tipos de gráficos eu devo utilizar para ter uma análise útil?
* Vou fazer análise preditiva - times series ou algum algoritmo de machine learning clássico?
<br/>

**Ferramentas**<br/>
* Obter dividendos e preços: yFinance;
* Obter VP, liquidez, etc: ???;
* Obter notícias: 1° DuckDuckGo (DDG é bom, mas é bem simples e não é suficiente), 2°???;
* LLMs: Groq e OpenAI;
<br/>

**Teoria Agentes AI**<br/>
* ReAct (Reasoning + Action - API);
* RAG (VectorDB, ChromaDB);
* LangGraph;
* Multiagents (Observability, Guardrails, Routing);
<br/>

**Programação**<br/>
* Gráficos: Plotly e Seaborn;
* Frontend: HTML, CSS e JavaScript;
* Backend: Python (Flask);
<br/>

**Deploy Cloud**<br/>
* Armazenamento: S3;
* Máquina: EC2;
* Domínio: ???;
* Outro Serviço: ???;
<br/>