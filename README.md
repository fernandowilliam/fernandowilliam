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

## Projetos

Agentic Harness corporativo. Framework de governança e execução para dezenas de agentes operando em ambiente corporativo e de engenharia. Três camadas (regras, orquestração e execução), sandboxing de contexto, integrações via MCP, CI/CD que gera changelog semântico, e aprovação humana obrigatória em operação destrutiva ou sobre banco de dados. É o ambiente onde o trabalho do dia a dia roda.

LegalAssist AI. Agentes para qualificação comercial, atendimento, agendamento e processos internos de escritórios jurídicos, com painel de leads, integração a CRM e geração de documentos. Claude, LangChain, Pinecone, Next.js e MongoDB.

OmniSales AI. Atendimento com conhecimento de catálogo, recomendação e segmentação dinâmica para e-commerce. GPT, RAG com function calling, Python, FastAPI e BigQuery.

PharmFlow AI, em andamento. Atendimento e orçamento automatizado de receitas para farmácia de manipulação, verificação de fórmulas, previsão de demanda e automação regulatória. Gemini 2.5 Flash com fine-tuning, TensorFlow e PostgreSQL.

Relocation Agent, em andamento. Agente de imigração e relocation que atende, qualifica leads de anúncio, agenda e faz follow-up pelo WhatsApp. Grok 4, Airtable e WhatsMeow.

## Como trabalho

Prefiro testar uma hipótese antes de escrever código, e não afirmo nada sobre um dado sem ter o número, o período e a fonte. Em automação, desconfio de proposta que automatiza tudo: o desenho começa por onde o humano precisa ficar. Em operação crítica uso guardrails, aprovação humana e falha fechada desde o projeto. Quando entrego, separo o resumo para quem decide do detalhe para quem vai construir.

## Stack

Python (FastAPI, LangChain, pandas, scikit-learn, TensorFlow), SQL e PostgreSQL com pgvector, JavaScript e TypeScript (Node.js, Next.js, HTML e CSS), APIs REST e webhooks, function calling e Model Context Protocol (MCP), modelos da OpenAI, Anthropic, Google, Meta, Mistral e xAI, bancos vetoriais (pgvector, Pinecone, Chroma), MongoDB, Docker, Kubernetes, Terraform, Ansible e Linux. Monitoramento com Zabbix, Prometheus e Grafana. Também uso BigQuery, Supabase e n8n quando o ambiente do cliente pede.

## Antes da IA

Entre 2020 e 2024 liderei infraestrutura e segurança da informação no Exército Brasileiro: cerca de 15 sistemas em servidores Linux virtualizados com deploy por script, versionamento em git, monitoramento com Zabbix e orquestração com Kubernetes; migração de parte deles para containers e nuvem (AWS e Azure); e um data warehouse que alimentou painéis em tempo real para a tomada de decisão. Antes, dez anos na Lima & Zanette, de administrador de sistemas a gestor de TI, com SQL, Python, JavaScript, ITIL, Scrum e a migração da infraestrutura local para nuvem. Em 2024 e 2025, consultoria de infraestrutura híbrida em Braga, Portugal, com Azure, VMware, Fortinet e Veeam.

## Formação

Sistemas de Informação (UniFOA, 2017), pós-graduação em Segurança da Informação (Estácio, 2021) e tecnólogo em Redes de Computadores (UniFOA, 2011). Mestrado em IA em andamento. Certificação MCITP Enterprise Administrator (Microsoft). Português nativo, inglês B2, espanhol A2.

## Contato

LinkedIn: https://www.linkedin.com/in/fernandowilliam/

E-mail: fernando@atomai.digital
