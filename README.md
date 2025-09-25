# Cadastro Controle de Fichas

**Cadastro Controle de Fichas** é um aplicativo web/mobile projetado para facilitar o registro e gerenciamento de incidentes e ocorrências. Ele permite que usuários cadastrem, organizem e acompanhem eventos de maneira prática e eficiente. A interface é intuitiva e pode ser adaptada para diferentes contextos ou organizações que necessitem de um sistema de controle de incidentes.

## Tecnologias utilizadas

- **Back-end:** Spring Boot
- **Front-end:** React.js com TypeScript
- **Banco de dados:** PostgreSQL
- **Containerização:** Docker
- **Autenticação:** JWT

## Estrutura do Projeto

```
cadastro-controle-fichas/
│
├── backend/                # Código-fonte do back-end (API)
│   ├── src/
│   │   └── main/
│   │       ├── java/com/cadastro_controle_fichas/backend/
│   │       │   ├── BackendApplication.java
│   │       │   ├── controlers/      # Controllers da API
│   │       │   ├── dtos/            # Data Transfer Objects
│   │       │   ├── entities/        # Entidades do domínio
│   │       │   ├── repositories/    # Repositórios (JPA)
│   │       │   ├── services/        # Lógica de negócio
│   │       │   └── validators/      # Validações customizadas
│   │       └── resources/
│   │           └── application.properties
│   ├── pom.xml              # Gerenciamento de dependências Maven
│   └── Dockerfile           # Dockerização do back-end
│
├── frontend/                # Código-fonte do front-end (React)
│   └── Dockerfile           # Dockerização do front-end
│
├── docker-compose.yml       # Orquestração dos containers
└── README.md                # Documentação do projeto
```

## Como executar o projeto
### ainda estamos ajustando essa parte

1. Certifique-se de ter o Docker e o Docker Compose instalados.
2. Clone este repositório.
3. Execute o comando abaixo na raiz do projeto para subir todos os serviços:
   ```
   docker-compose up --build
   ```
4. O back-end estará disponível em `http://localhost:8081` e o front-end em `http://localhost:8082`.

## Integrantes do Grupo

- Daniela Lopes — Gerente de Projetos
- João Brayner – Desenvolvedor back-end e DevOps
- Felipe Reis — Desenvolvedor Back-end
- Thiago Mariano — Desenvolvedor Front-end
- Claúdio Eduardo — Desenvolvedor Front-end
- José Tacyto — Designer

## Licença

O uso deste software é restrito. Só é permitido utilizar, copiar, modificar ou distribuir este projeto mediante acordo prévio com o grupo responsável pelo Cadastro Controle de Fichas. Para mais informações, consulte o arquivo [LICENSE](./LICENSE).

