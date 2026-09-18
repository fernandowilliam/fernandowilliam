# Fernando William

Engenheiro de soluções de IA. Trabalho com agentes LLM, RAG e automação de processos em produção. Antes disso passei 15 anos em infraestrutura, redes, banco de dados e segurança da informação.

Meu trabalho costuma começar antes do código: entender o processo do cliente, decidir em qual parte dele a IA compensa e em qual parte continua sendo trabalho de gente, e só então desenhar a arquitetura, escrever, colocar em produção e acompanhar os números. A base de infraestrutura é o que me deixa cuidar também da parte que normalmente fica de fora do protótipo: deploy, monitoramento, controle de acesso e o que acontece quando algo falha.

## Em produção

Hoje mantenho agentes de atendimento e qualificação, pipelines de RAG e integrações com CRM para empresas de varejo, direito, saúde e e-commerce, no Brasil e em Portugal. O núcleo é Python e PostgreSQL atrás de APIs próprias. Quando o cliente já opera n8n, a orquestração dos fluxos fica lá e a lógica de decisão continua em código.

Alguns números, com a origem de cada um:

- 13 tenants em operação e 36.120 execuções de workflows de agente na semana de 31/08 a 06/09/2026, contadas na base de execuções da plataforma.
- Classificador de conversas com 85% de concordância contra 393 rótulos humanos, em 2.019 conversas. O classificador por palavra-chave que ele substituiu ficava em 45%.
- Erro de classificação de 28% para 16%, medido em teste A/B pareado e 45 dias de observação em produção.
- Acionamento de atendimento humano validado em harness: 20 de 20 cenários corretos. O baseline falhava em 4 de 4.
- Contexto por chamada de 7.808 para 7.426 tokens, mantendo os 20 cenários do harness.

## Como trabalho

Prefiro testar uma hipótese antes de escrever código, e não afirmo nada sobre um dado sem ter o número, o período e a fonte. Em automação, desconfio de proposta que automatiza tudo: o desenho começa por onde o humano precisa ficar. Em operação crítica uso guardrails, aprovação humana e falha fechada desde o projeto. Quando entrego, separo o resumo para quem decide do detalhe para quem vai construir.

## Stack

Python (FastAPI, pandas, scikit-learn), SQL e PostgreSQL com pgvector, JavaScript e TypeScript (Node.js, Next.js, HTML e CSS), APIs REST, Model Context Protocol (MCP), modelos da OpenAI, Anthropic e Google, Docker, Kubernetes, Terraform e Linux. Também uso BigQuery, Supabase e n8n quando o ambiente do cliente pede.

## Formação

Sistemas de Informação (UniFOA, 2017) e pós-graduação em Segurança da Informação (Estácio, 2021).

## Contato

LinkedIn: https://www.linkedin.com/in/fernandowilliam/

E-mail: fernando@atomai.digital
