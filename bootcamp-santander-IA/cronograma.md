# 📅 Cronograma Diário: Roteiro de 30 Dias

Abaixo está o seu roteiro de estudos detalhado dia a dia. Utilize as caixas de seleção `[ ]` para acompanhar seu progresso!

---

## 📅 Semana 1: Dominando Java e Programação Orientada a Objetos (POO)
*Foco: Compreender a base conceitual e a sintaxe do Java sob a ótica de objetos.*

- [ ] **Dia 1: Introdução e Sintaxe Básica**
  - **Teoria:** Ambiente Java (JDK e IntelliJ IDEA), Estrutura de um programa Java, Variáveis, Tipos de dados e Métodos.
  - **Prática:** Criar uma calculadora simples que lê dados do teclado e executa operações matemáticas básicas.
- [ ] **Dia 2: Classes e Objetos**
  - **Teoria:** Definição de Classes, Instanciação de Objetos, Construtores, Encapsulamento, Getters e Setters.
  - **Prática:** Desenvolver um Sistema de Cadastro de Pessoas em memória.
- [ ] **Dia 3: Herança e Sobrescrita**
  - **Teoria:** Relações de Herança (`extends`), a palavra-chave `super` e Sobrescrita de métodos (`@Override`).
  - **Prática:** Criar a classe mãe `Pessoa` e as filhas `Cliente` e `Funcionario`, sobrescrevendo o método de exibição de dados.
- [ ] **Dia 4: Polimorfismo e Abstração**
  - **Teoria:** Polimorfismo, Classes Abstratas e Interfaces.
  - **Prática:** Criar um sistema de pagamentos (`Interface Pagamento` com métodos para calcular taxa) implementado por `PagamentoBoleto` e `PagamentoCartao`.
- [ ] **Dia 5: Collections**
  - **Teoria:** Manipulação de coleções em Java: `ArrayList`, `HashMap` e `HashSet`.
  - **Prática:** Criar um cadastro de produtos dinâmico utilizando `ArrayList` e buscar itens por código usando `HashMap`.
- [ ] **Dia 6: Tratamento de Exceções**
  - **Teoria:** Estruturas `try/catch`, palavra-chave `throws` e criação de Exceções personalizadas.
  - **Prática:** Criar um sistema de login simples que lança uma exceção personalizada (`SenhaIncorretaException`) se os dados estiverem incorretos.
- [ ] **Dia 7: Mini Projeto de Consolidação**
  - **Prática:** **Sistema de Cadastro de Clientes (Console)**.
    - Requisitos: Cadastrar, Listar, Editar e Excluir (CRUD) clientes salvos em memória (`ArrayList`).
    - *Sem banco de dados nesta etapa.*

---

## 📅 Semana 2: Banco de Dados, SQL e Git
*Foco: Aprender a persistir dados em um banco relacional e versionar seu código localmente.*

- [ ] **Dia 8: Introdução a Bancos de Dados**
  - **Teoria:** Instalação do PostgreSQL e pgAdmin. Conceitos básicos de SQL: `CREATE DATABASE` e `CREATE TABLE`.
  - **Prática:** Criar tabelas iniciais no PostgreSQL via pgAdmin.
- [ ] **Dia 9: Manipulação de Dados (DML)**
  - **Teoria:** Inserção, edição e exclusão de dados usando `INSERT`, `UPDATE` e `DELETE`.
  - **Prática:** Cadastrar e atualizar produtos na tabela criada anteriormente usando scripts SQL.
- [ ] **Dia 10: Consultas de Dados (SELECT)**
  - **Teoria:** Estruturação de consultas com `SELECT`, filtros `WHERE`, ordenações `ORDER BY` e limitações `LIMIT`.
  - **Prática:** Escrever consultas para buscar produtos por faixas de preço e ordenar alfabeticamente.
- [ ] **Dia 11: Relacionamentos e Joins**
  - **Teoria:** Relacionamentos entre tabelas (Chaves Estrangeiras) e junções com `INNER JOIN` e `LEFT JOIN`.
  - **Prática:** Realizar consultas juntando informações de tabelas de vendas e clientes.
- [ ] **Dia 12: Agregações e Agrupamentos**
  - **Teoria:** Funções agregadoras (`COUNT`, `SUM`, `AVG`) e agrupamento `GROUP BY`.
  - **Prática:** Consultar o faturamento total e média de vendas por categoria de produto.
- [ ] **Dia 13: Modelagem de Banco de Dados**
  - **Prática:** Criar a modelagem completa (tabelas, chaves e relacionamentos) de um banco para uma **Biblioteca** ou uma **Loja**.
- [ ] **Dia 14: Versionamento de Código com Git**
  - **Teoria:** Fluxo básico de controle de versão: `git init`, `git add`, `git commit`, `git status` e `git log`.
  - **Prática:** Inicializar um repositório Git local e fazer o commit dos exercícios da semana.

---

## 📅 Semana 3: GitHub e Introdução ao Spring Boot
*Foco: Publicar código na nuvem e iniciar a jornada com o framework Spring Boot.*

- [ ] **Dia 15: GitHub e Trabalho Remoto**
  - **Teoria:** Integração com GitHub, criação de repositórios remotos, comandos `git push`, `git pull` e `git clone`.
  - **Prática:** Subir todos os projetos criados até agora para o seu perfil do GitHub.
- [ ] **Dia 16: Ramificação (Branches)**
  - **Teoria:** Trabalho com ramificações: `git checkout`, `git branch`, `merge` e conceito de `pull request`.
  - **Prática:** Criar uma branch `feature/ajuste-calculadora`, fazer modificações e mesclá-las na branch principal (`main`).
- [ ] **Dia 17: Introdução ao Spring Boot**
  - **Teoria:** O que é Spring Boot, gerenciador de dependências Maven, estrutura de diretórios e inicialização do projeto via Spring Initializr.
  - **Prática:** Gerar e rodar o seu primeiro esqueleto de aplicação Spring Boot.
- [ ] **Dia 18: Construindo a Camada REST API**
  - **Teoria:** Protocolo HTTP e mapeamento de endpoints usando `@RestController`, `@GetMapping` e `@PostMapping`.
  - **Prática:** Criar um endpoint "/status" que retorna uma mensagem de texto e um "/usuarios" simples.
- [ ] **Dia 19: Arquitetura em Camadas e Injeção de Dependências**
  - **Teoria:** Organização do código: `@Controller`/`@RestController`, `@Service` e a injeção automática de dependências (`@Autowired`).
  - **Prática:** Separar as regras de negócio em uma classe de serviço e injetá-la no controlador.
- [ ] **Dia 20: Persistência com Spring Data JPA**
  - **Teoria:** Mapeamento Objeto-Relacional (ORM), anotações `@Entity`, `@Table`, `@Id` e criação de interfaces com `JpaRepository`.
  - **Prática:** Conectar seu projeto Spring Boot ao PostgreSQL e configurar as credenciais no `application.properties`.
- [ ] **Dia 21: Validações e DTOs (Data Transfer Objects)**
  - **Teoria:** Criação de DTOs para tráfego seguro de dados, validação de campos (`@NotNull`, `@NotBlank`, `@Size`) e boas práticas de design de API.
  - **Prática:** Implementar validações no payload recebido em um endpoint de cadastro.

---

## 📅 Semana 4: Projeto para Portfólio (API de Biblioteca)
*Foco: Desenvolver um projeto completo do início ao fim e publicá-lo para recrutadores.*

- [ ] **Dia 22: Setup e Configurações Iniciais**
  - **Prática:** Criar o projeto no Spring Initializr, importar para a IDE e configurar o banco PostgreSQL no `application.properties`.
- [ ] **Dia 23: Banco de Dados e Entidades**
  - **Prática:** Modelar e criar a entidade `Livro` com campos como id, titulo, autor, isbn e dataPublicacao.
- [ ] **Dia 24: Camadas Repository e Service**
  - **Prática:** Desenvolver a interface `LivroRepository` e a classe `LivroService` contendo as regras para gerenciar os livros.
- [ ] **Dia 25: Camada Controller (Endpoints CRUD)**
  - **Prática:** Criar os endpoints para cadastrar (`POST`), listar (`GET`), buscar por id (`GET`), editar (`PUT`) e excluir (`DELETE`) livros.
- [ ] **Dia 26: Validações e Tratamento de Erros**
  - **Prática:** Adicionar validações nas requisições e implementar um manipulador global de exceções (`@ControllerAdvice`) para retornar erros limpos ao cliente.
- [ ] **Dia 27: Testes Manuais com Postman**
  - **Prática:** Criar uma collection no Postman e testar todos os cenários da sua API (caminhos felizes e de erro).
- [ ] **Dia 28: README e Publicação no GitHub**
  - **Prática:** Subir o código final para o GitHub e criar um `README.md` exemplar, explicando o projeto, como rodar e quais tecnologias foram usadas.
- [ ] **Dia 29: Refatoração e Boas Práticas**
  - **Prática:** Limpar imports não utilizados, formatar o código, renomear variáveis confusas e adicionar comentários pontuais explicativos.
- [ ] **Dia 30: Projeto Concluído & Próximos Passos**
  - **Ação:** Revisar todo o conteúdo estudado, atualizar seu LinkedIn detalhando o projeto e adicioná-lo ao seu currículo profissional.

---

> [!NOTE]
> Você pode acessar os materiais de apoio de cada semana no arquivo **[recursos.md](file:///c:/Users/bieln/Downloads/bootcamp-santander-IA/recursos.md)**.
