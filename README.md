# Fernando William

Engenheiro de Soluções de IA. Coloco agentes LLM, RAG e automação em produção e meço o resultado.

Trabalho o ciclo inteiro: diagnóstico do processo, decisão de onde a IA gera valor e onde o humano continua insubstituível, arquitetura, código, deploy e medição. Antes de IA, 15 anos em infraestrutura, redes, bancos de dados e segurança da informação. É essa base que faz a solução sobreviver em produção em vez de morrer no protótipo.

## O que está em produção hoje

Agentes de atendimento e qualificação, pipelines de RAG e integrações com CRM para empresas de varejo, direito, saúde e e-commerce, no Brasil e em Portugal. O núcleo é Python e PostgreSQL atrás de APIs próprias; onde o cliente já opera n8n, a orquestração dos fluxos fica nele e o código de decisão continua fora. Alguns números que consigo defender com dado de origem:

- 13 tenants em operação e 36.120 execuções de workflows de agente em uma semana (31/08 a 06/09/2026), medidas na base de execuções da plataforma.
- Classificador de conversas com 85% de concordância contra 393 rótulos humanos em 2.019 conversas, contra 45% do classificador por palavra-chave que substituiu.
- Erro de classificação reduzido de 28% para 16% com teste A/B pareado e 45 dias de observação em produção.
- Acionamento de atendimento humano validado em harness: 20 de 20 cenários corretos, partindo de um baseline que falhava em 4 de 4.
- Contexto por chamada reduzido de 7.808 para 7.426 tokens sem perder nenhum dos 20 cenários do harness.

## Como trabalho

- Hipótese antes de código. Toda afirmação sobre dado vem com teste, número, período e fonte.
- Automatizar 100% é sinal de alerta. O desenho começa por onde o humano fica.
- Guardrails, human-in-the-loop e falha fechada em operações críticas. Segurança é parte da arquitetura, não revisão no fim.
- Executive summary para quem decide, detalhe técnico em anexo para quem constrói.

## Stack

Python (FastAPI, pandas, scikit-learn), SQL e PostgreSQL (pgvector), JavaScript e TypeScript (Node.js, Next.js, HTML e CSS), APIs REST, Model Context Protocol (MCP), LLMs da OpenAI, Anthropic e Google, Docker, Kubernetes, Terraform, Linux.

Também uso BigQuery, Supabase e n8n quando o ambiente do cliente pede.

## Formação

Bacharelado em Sistemas de Informação (UniFOA, 2017) e pós-graduação em Segurança da Informação (Estácio, 2021).

## Contato

[LinkedIn](https://www.linkedin.com/in/fernandowilliam/) · fernando@atomai.digital
