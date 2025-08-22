# DsList2025
# Projeto DSList - Bootcamp Java Spring 
# Promovido pela devsuperior - Prof. Dr. Nelio Alves

  # ⬇️⬇️⬇️ Aula 01 ⬇️⬇️⬇️

<img width="408" height="441" alt="image" src="https://github.com/user-attachments/assets/bf5ed936-0be7-4d25-9516-a8cf12ff97d8" />

<img width="1760" height="863" alt="image" src="https://github.com/user-attachments/assets/e2f3756b-0eef-4a61-b190-2045c49e2575" />

## API Rest:
- Cliente/servidor com HTTP
- Comunicação stateless (*)
- Interface uniforme, formato padronizado (*)
- Cache
- Sistema em camadas
- Código sob demanda (opcional)

<img width="793" height="635" alt="image" src="https://github.com/user-attachments/assets/2fbda7ff-4ff7-4d3a-a3e5-41d30db5cd5b" />


<img width="666" height="247" alt="image" src="https://github.com/user-attachments/assets/90a74458-dc36-4658-8e53-54987dbe14df" />

## Aula 01 - O que aprendi:

- Conceitos  
- Sistemas web e recursos  
- Cliente/servidor, HTTP, JSON  
- Padrão Rest para API web  
- Estruturação de projeto Spring Rest  
- Entidades e ORM  
- Database seeding  
- Padrão camadas  
- Controller, service, repository  
- Padrão DTO

  # ⬇️⬇️⬇️ Aula 02 ⬇️⬇️⬇️

<img width="991" height="427" alt="image" src="https://github.com/user-attachments/assets/03903e1b-72da-4bd3-b628-8a9d53a36555" />

<img width="925" height="369" alt="image" src="https://github.com/user-attachments/assets/9ddbaa80-f12a-41ed-804d-7d19c4d396d5" />

<img width="962" height="352" alt="image" src="https://github.com/user-attachments/assets/9f687946-79c3-4e41-9734-c35dbbaf4a2c" />

## Aula 02 - O que aprendi:
 - Relacionamentos N-N
 - Classe de associação, embeddedid
 - Consultas SQL no Spring Data JPA
 - Projections

   
  # ⬇️⬇️⬇️ Aula 03 ⬇️⬇️⬇️

  # Perfis de projeto
   - Perfil de desenvolvimento e testes:- test- Banco de dados H2
   - Perfil de homologação / staging:- dev- Banco de dados Postgres de homologação
   - Perfil de produção:- prod- Banco de dados Postgres de produção

  # Passos homologação
  -Preparação do ambiente
  -Docker
  -ou
  -Postgresql+ pgAdminou DBeaver
  -Homologação local
  - 1 Criar perfis de projeto
  -system.properties
  - 2 Gerar script da base de dados
  -apagar arquivo gerado
  - 3 Criar base de dados de homologação
  - 4 Rodar app no modo deve validar

  # Passos deployCI/CD
  - Pré-requisitos-Conta no Railway-Conta no Githubcom mais de 90 dias-Projeto Spring Boot salvo no seu Github-Script SQL para criação e seedda base de dados-Aplicativo de     gestão de banco instalado (pgAdminou DBeaver)
 Passos Railway
 - 1. Prover um servidor de banco de dados 
 - 2. Criar a base de dados e seed
 - 3. Criar uma aplicação Railway vinculada a um repositório Github
 - 4. Configurar variáveis de ambiente
 
 -APP_PROFILE
 -DB_URL (Formato: jdbc:postgresql://host:porta/nomedabase)
 -DB_USERNAME
 -DB_PASSWORD
 -CORS_ORIGINS

 -5. Configurar o domínio público para a aplicação
 -6. Testar app no Postman
 -7. Testar a esteira de CI/CD

 # Aula 03 - O que aprendi:
 - Perfis de projeto
 - Ambiente local com Docker Compose
 - Processo de homologação local
 - Processo de deploycom CI/CD
 - Configuração de CORS


# ⬇️⬇️⬇️ Aula 04 ⬇️⬇️⬇️
   
 - O que você aprendeu:
 - Design e implementação de endpoint especial
 - Operação de atualização no Spring
 - Operaçõescom List
 - Verbo HTTP e idempotência





