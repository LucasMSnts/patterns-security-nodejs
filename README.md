# GoBarber-Backend
Utilizando o backend do [GoBarber](https://github.com/LucasMSnts/gobarber-backend) para estudar sobre Patterns...

# O que são Design Patterns?

- Patterns são regras de organização do código;
- Constante evolução;
- Otimização prematura;
- Patterns comuns:
  - Singleton (a classe só pode ter uma instância);
  - Repository (abstração da conexão com o banco);
  - Service (abstração de lógica);
  - Observer (comunicação por eventos);

# Utilizado no Projeto

- Singleton Pattern
  - O Node.js transforma toda exportação de objeto em um singleton;
  - Novos requires/imports importam a mesma instância;
- Service Pattern
  - Abstrair lógica do controller;
  - Quando? (code smell)
    - Código muito denso;
    - Condicionais dentro do controller;
    - Regra de negócio redundante;

Patterns são úteis em projetos conforme crescem;

Quando uma aplicação Node.js cresce muito usa outras alternativas:
  - Micro-serviços;
  - Serverless;

# Segurança no Node.js

Alguns links:
- [Express Brute](https://www.npmjs.com/package/express-brute)
- [Helmet](https://helmetjs.github.io/)
- [CORS](https://expressjs.com/en/resources/middleware/cors.html)
