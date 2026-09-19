
QA Test Management

Documentação inicial de um sistema de gestão e automação de testes de software em um ambiente corporativo.

1. Visão geral

O sistema tem como objetivo apoiar o time de QA no gerenciamento de casos de teste, execução de testes, registro de resultados e acompanhamento de bugs.

O contexto considera uma equipe pequena, com aproximadamente 12 pessoas, utilizando Jira, Robot Framework e Python.

2. Escopo

O sistema contempla:

Gerenciamento de casos de teste;
Execução e registro dos resultados;
Armazenamento de evidências;
Automação de testes;
Acompanhamento de bugs através do Jira.
Restrições e lacunas

A solução deve ser simples de manter e compatível com o ambiente corporativo existente.

Ainda não estão definidos detalhes como banco de dados, infraestrutura e tecnologia do backend. Essas informações serão detalhadas em uma etapa posterior.

3. Visão estrutural

O fluxo representa a execução de um teste automatizado e o registro de uma falha.

Sequencia Diagrama

<img width="1644" height="964" alt="image" src="https://github.com/user-attachments/assets/42fe4b27-b980-4bb1-84ca-47d474ade9d0" />

4. Decisões e ajustes

Os diagramas foram gerados com apoio de GenAI e revisados para representar melhor o contexto de QA.

Foi mantido o Robot Framework como ferramenta de automação e o Python como linguagem de apoio. O Jira foi incluído como integração para o registro de bugs.

Também foram evitadas informações que ainda não fazem parte do contexto conhecido, como banco de dados e infraestrutura.

5. Estratégia de testes

A solução deve considerar:

Testes unitários;
Testes de integração;
Testes E2E;
Automação com Robot Framework;
Testes de regressão.

6. Próximos passos

Como próximos passos, seria necessário detalhar:

Arquitetura da aplicação;
Banco de dados;
APIs;
Autenticação;
Infraestrutura;
Pipeline de CI/CD;
Estratégia de execução dos testes automatizados;
Integração com Jira;
Política de armazenamento de evidências.
