# Fernando William

Engenheiro de soluções de IA. Coloco agentes LLM, RAG e automação de processos em produção para empresas de varejo, direito, saúde e e-commerce, e meço o que eles fazem depois de entrar no ar. Antes disso, 15 anos em infraestrutura, banco de dados e segurança da informação.

O trabalho começa antes do código: entender o processo, decidir em qual parte a IA compensa e em qual parte continua sendo trabalho de gente, construir, colocar em produção e acompanhar os números. A base de infraestrutura é o que me deixa cuidar do que o protótipo costuma deixar de fora: deploy, monitoramento, controle de acesso e o que acontece quando algo falha.

## Números de produção

Cada um com período e fonte, porque número sem isso não vale nada.

- 13 tenants em operação e 36.120 execuções de workflows de agente na semana de 31/08 a 06/09/2026, contadas na base de execuções da plataforma.
- Classificador de conversas com 85% de concordância contra 393 rótulos humanos, em 2.019 conversas. O classificador por palavra-chave que ele substituiu ficava em 45%.
- Erro de classificação de 28% para 16%, medido em teste A/B pareado e 45 dias de observação em produção.
- Acionamento de atendimento humano validado em harness: 20 de 20 cenários corretos. O baseline falhava em 4 de 4.

## Código público

- [Triagem de tickets com abstenção](https://github.com/fernandowilliam/triagem-tickets-com-abstencao): classificador que decide sozinho 6 em cada 10 tickets, acerta 96 de cada 100 desses e devolve o resto para uma pessoa. Medido em 47.837 tickets públicos; inclui o LLM medido e retirado, a leitura dos erros que achou rótulo errado na origem e o piloto com regra de decisão.

## O que procuro

Posição em que uma pessoa responde do diagnóstico ao resultado medido, junto à liderança: engenharia de soluções de IA, AI engineer, automação com agentes. São Paulo presencial ou remoto.

## Stack

Python (FastAPI, LangChain, scikit-learn), PostgreSQL com pgvector, TypeScript e Node.js, Docker e Kubernetes, n8n quando o cliente já opera nele. Modelos da OpenAI, Anthropic e Google; function calling e MCP. Mestrado em IA em andamento.

## Contato

[LinkedIn](https://www.linkedin.com/in/fernandowilliam/) · fernando.william84@gmail.com
