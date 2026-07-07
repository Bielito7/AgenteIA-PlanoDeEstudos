# 📚 Recursos de Estudo e Referências

Aqui estão reunidos todos os materiais recomendados para apoiar seus estudos em cada etapa do cronograma.

---

## 📅 Semana 1: Java e Programação Orientada a Objetos (POO)

### 🎥 Cursos Gratuitos
* **Curso em Vídeo — Java (Gustavo Guanabara)**: Excelente didática para quem está iniciando do absoluto zero no ecossistema Java.
* **Loiane Groner — Java Básico**: Curso detalhado e muito reconhecido pela comunidade, focado em lógica e orientação a objetos em Java.
* **DevDojo — Maratona Java**: Uma das playlists mais completas e profundas do YouTube para quem quer aprender Java desde o básico até tópicos extremamente avançados.

### 📖 Documentação Oficial
* **[Oracle Java Documentation](https://docs.oracle.com/en/java/)**: O ponto de referência absoluto de toda a linguagem e suas APIs integradas.

### ✍️ Exercícios Práticos
* **[Beecrowd (antigo URI)](https://www.beecrowd.com.br/)**: Excelente portal para treinar algoritmos, estruturas de dados básicas e lógica com Java.
* **[HackerRank (Java Track)](https://www.hackerrank.com/domains/java)**: Desafios curtos de sintaxe e conceitos específicos da linguagem para solidificar o conhecimento diário.

---

## 📅 Semana 2: Banco de Dados, SQL e Git

### 💾 Bancos de Dados e SQL
* **Curso em Vídeo — Banco de Dados**: Explicação intuitiva sobre modelagem relacional, tabelas, chaves e manipulação de dados.
* **[SQLBolt (Interativo)](https://sqlbolt.com/)**: Plataforma prática que permite escrever consultas SQL diretamente no navegador com feedbacks em tempo real.
* **[HackerRank (SQL Track)](https://www.hackerrank.com/domains/sql)**: Desafios de consultas SQL (filtros, agregações e joins) que vão do nível básico ao avançado.

### 🔧 Ferramentas do Dia a Dia
* **[PostgreSQL (Instalador)](https://www.postgresql.org/download/)**: O SGDB relacional que utilizaremos em todo o projeto.
* **[pgAdmin](https://www.pgadmin.org/)**: A interface gráfica oficial para gerenciar, criar e consultar bancos de dados PostgreSQL.

### 🌿 Git (Controle de Versão Local)
* **Curso em Vídeo — Git e GitHub**: O melhor curso introdutório em vídeo para entender o fluxo de versionamento e repositórios locais.
* **[Livro Pro Git (Gratuito)](https://git-scm.com/book/pt-br/v2)**: O livro de referência oficial do Git, disponível em português. Excelente para tirar dúvidas profundas sobre comandos específicos.

---

## 📅 Semana 3: GitHub e Spring Boot

### ☁️ GitHub (Controle de Versão Remoto)
* **Curso em Vídeo — Git e GitHub** *(continuação)*: Foco nas aulas de sincronização de repositório local com repositório remoto, resolução de conflitos, branches e pull requests.

### 🍃 Spring Boot (Framework Back-end)
* **Michelli Brito (YouTube)**: Tutoriais passo a passo de APIs REST completas com Spring Boot, JPA e validações.
* **DevDojo — Spring Boot**: Playlist focada na construção de APIs robustas utilizando as melhores práticas do ecossistema Spring.
* **Amigoscode (Inglês)**: Excelente canal de tutoriais modernos que aborda conceitos de arquitetura limpa e ecossistema Spring.
* **[Spring Boot Documentation](https://spring.io/projects/spring-boot)**: Guia e referências da documentação oficial do ecossistema Spring.

---

## 📅 Semana 4: Desenvolvimento de Portfólio

### 📂 Projeto Principal da Semana: API de Biblioteca
Esta API servirá como o seu principal projeto de portfólio inicial. Utilize-o para colocar em prática tudo o que aprendeu.

* **Requisitos Funcionais (CRUD):**
  * `[ ]` Cadastrar livros
  * `[ ]` Listar todos os livros cadastrados
  * `[ ]` Buscar livro específico por ID
  * `[ ]` Editar informações de um livro existente
  * `[ ]` Excluir um livro do catálogo
* **Tecnologias Envolvidas:**
  * **Linguagem:** Java
  * **Framework:** Spring Boot (Spring Web, Validation)
  * **Persistência:** Spring Data JPA / Hibernate
  * **Banco de Dados:** PostgreSQL
  * **Ferramentas:** Maven, Postman, Git, GitHub

---

## 🚀 Próximos Projetos para Portfólio (Futuro)

Após concluir o plano de 30 dias e dominar a API de Biblioteca, você estará pronto para desenvolver e publicar os seguintes projetos de forma autônoma:

1. **Sistema de Cadastro de Clientes**: Gestão de clientes com validações mais robustas (como CPF/CNPJ e endereços).
2. **Sistema de Estoque**: Controle de entrada e saída de produtos, calculando lucros e quantidades mínimas.
3. **Lista de Tarefas (To Do)**: Permite cadastrar tarefas, definir prioridades e marcar status de conclusão.
4. **Sistema de Pedidos**: Relacionamento complexo entre tabelas (Pedido -> Itens de Pedido -> Produtos).
5. **API de Usuários com Autenticação**: Implementação de login e segurança (ex: JWT com Spring Security).
6. **API para E-commerce**: Sistema completo envolvendo carrinho de compras, cálculo de frete simulado e controle de vendas.
