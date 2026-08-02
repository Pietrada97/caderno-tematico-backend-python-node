🚀 Caderno Temático: Desenvolvimento Backend com Python (FastAPI) e Node.js (Express)
Projeto desenvolvido para o Desafio de Projeto da DIO utilizando o NotebookLM como ferramenta de aprendizagem ativa.

1. Contexto e Objetivos
Assunto escolhido
Desenvolvimento de APIs REST modernas utilizando Python + FastAPI e Node.js + Express, comparando as duas abordagens mais utilizadas no mercado atual.
Objetivos de estudo

Entender os fundamentos de APIs REST e boas práticas de backend
Dominar a criação de APIs com FastAPI (Python) e Express (Node.js)
Comparar as duas stacks: performance, produtividade, tipagem, documentação automática e ecossistema
Aprender conceitos essenciais: roteamento, middleware, validação de dados, autenticação e estrutura de projeto
Criar um material de revisão reutilizável para consultas futuras


2. Curadoria de Fontes
Fontes abertas utilizadas no NotebookLM:

Documentação Oficial do FastAPI – Tutorial
https://fastapi.tiangolo.com/tutorial/
Documentação Oficial do Express.js
https://expressjs.com/
MDN – Tutorial Express/Node.js
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs
Full Stack Open – Part 3 (Node.js e Express)
https://fullstackopen.com/en/part3
Full Stack Open – Part 4
https://fullstackopen.com/en/part4

Todas as fontes são oficiais ou de instituições reconhecidas, priorizando qualidade e atualização.


Feito com ☕ e NotebookLM
Desafio de Projeto – DIO

3. Engenharia de Prompts e "Cicatrizes"
Nesta seção documento o processo real de interação com o NotebookLM, incluindo os prompts utilizados, as respostas obtidas e os ajustes realizados.
Prompt 1 – Comparativo FastAPI vs Express
Prompt utilizado:

Com base nas fontes, faça um comparativo objetivo entre FastAPI e Express.js considerando: performance, facilidade de desenvolvimento, documentação automática, tipagem/validação, ecossistema e quando escolher cada um. Use tabela.

Resultado:
A resposta veio bem estruturada, com tabela clara e critérios objetivos. Destacou corretamente a documentação automática do FastAPI e o caráter minimalista do Express.
Cicatriz / Aprendizado:
A resposta ficou boa, mas poderia ter sido mais profunda em performance real e na menção ao TypeScript. Em uma próxima tentativa, pediria exemplos de código curtos e comparação de curva de aprendizado.

Prompt 2 – Estrutura de Projeto

Explique a estrutura de pastas recomendada para um projeto profissional com FastAPI e outro com Express (Node.js). Inclua exemplos de organização de rotas, controllers, services e middlewares.

Resultado:
Excelente. Trouxe estruturas reais e profissionais, separando bem as responsabilidades. Mostrou claramente a diferença de filosofia entre os dois frameworks (FastAPI mais organizado x Express mais livre).
Cicatriz / Aprendizado:
A resposta ficou completa, mas faltou um exemplo mínimo de código de como importar o APIRouter no FastAPI e o express.Router no Express. Em ajustes futuros, pediria o código de exemplo junto com a estrutura de pastas.

Prompt 3 – Validação de Dados

Como funciona a validação de dados de entrada em FastAPI (Pydantic) versus Express? Dê exemplos práticos de validação de body, query e path params.

Resultado:
Uma das melhores respostas. Trouxe exemplos de código claros, comparou bem a abordagem declarativa (FastAPI) com a abordagem via middleware (Express) e explicou as diferenças de erro automático vs manual.
Cicatriz / Aprendizado:
Resposta muito boa. O único ponto de melhoria seria pedir também um exemplo de validação customizada em ambos os frameworks.

Principais aprendizados sobre engenharia de prompts

Pedir tabela e comparação lado a lado melhora muito a qualidade da resposta
Sempre reforçar “com base nas fontes” evita alucinações
Solicitar exemplos práticos de código torna o conteúdo mais útil
Quando a resposta fica boa mas incompleta, o melhor é fazer um prompt de refinamento


4. Miniguia de Estudo
4.1 Resumos Estruturados
Conceitos Fundamentais de Backend

API REST: recursos, verbos HTTP e status codes
Middleware: funções que interceptam requisições
Roteamento: definição de endpoints
Validação de entrada: proteger a aplicação de dados inválidos
Separação de responsabilidades (Controller → Service → Repository)

FastAPI (Python)

Framework moderno baseado em Starlette + Pydantic
Tipagem nativa com type hints
Documentação automática (Swagger/OpenAPI) gerada sozinha
Excelente performance graças ao async/await
Ideal para APIs de alta performance e projetos de IA/ML

Express (Node.js)

Framework minimalista e extremamente flexível
Ecossistema gigante (npm)
Middleware poderoso e extensível
Ideal quando o time já usa JavaScript/TypeScript no frontend
Mais “livre” (você monta a arquitetura do jeito que quiser)

4.2 Glossário de Conceitos Principais
Termo,Significado
Middleware,Função que processa a requisição antes de chegar na rota final
Pydantic,Biblioteca de validação de dados usada pelo FastAPI
APIRouter,Forma de modularizar rotas no FastAPI
express.Router,Forma de modularizar rotas no Express
JWT,JSON Web Token – padrão de autenticação stateless
OpenAPI / Swagger,Especificação e interface visual da documentação da API
Dependency Injection,Padrão usado no FastAPI para injetar dependências
CORS,Mecanismo de segurança que controla quem pode acessar a API
DTO / Schema,Objeto usado para validar e transferir dados
ORM,"Object-Relational Mapping (ex: SQLAlchemy, Prisma, Sequelize)"

4.3 Prompts Reutilizáveis para Revisões Futuras

1 Revisão rápida
Faça um resumo executivo de 1 página sobre as principais diferenças entre FastAPI e Express, destacando quando usar cada um.

2 Checklist de projeto
Crie um checklist completo do que não pode faltar em uma API profissional feita com FastAPI e outro com Express (segurança, validação, logs, documentação, testes, estrutura).

3 Explicação de conceito
Explique [conceito] de forma clara, com exemplo de código em FastAPI e em Express, baseado nas fontes.

4 Comparação de implementação
Mostre lado a lado como implementar [funcionalidade] em FastAPI e em Express (ex: autenticação JWT, upload de arquivos, paginação, tratamento de erros).

5 Perguntas de entrevista
Gere 10 perguntas técnicas de entrevista sobre backend com FastAPI e Express, com respostas resumidas.

Como usar este material

Crie um novo notebook no NotebookLM
Faça upload das fontes listadas acima
Use os prompts da seção 3 e 4.3
Atualize este README conforme for aprendendo mais


Feito com ☕ e NotebookLM
Desafio de Projeto – DIO
