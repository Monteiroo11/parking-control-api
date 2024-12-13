<h1 align="center">Parking Control API 🚗</h1>

<p align="center">
  Este é um projeto de estudo desenvolvido com <strong>Spring Boot</strong>, que implementa uma API REST para o gerenciamento de vagas de estacionamento. Durante o desenvolvimento, foram aplicadas boas práticas de programação, conceitos de arquitetura MVC, e ferramentas modernas para construção de microserviços.
</p>

<hr>

<h2>⚙️ Funcionalidades</h2>
<ul>
  <li><strong>CRUD completo</strong>: Métodos POST, GET, PUT e DELETE para gerenciar vagas de estacionamento.</li>
  <li><strong>Validações</strong>: Validação de campos obrigatórios com Spring Validation.</li>
  <li><strong>Paginação e ordenação</strong>: Organização das respostas das requisições GET.</li>
  <li><strong>Prevenção de duplicidades</strong>: Regras para evitar registros duplicados com base em placa, número da vaga e apartamento.</li>
  <li><strong>Formatação de datas</strong>: Configuração global no padrão ISO 8601 (UTC).</li>
  <li><strong>Estrutura escalável</strong>: Divisão do projeto em camadas (Controller, Service, Repository e DTO).</li>
</ul>

<hr>

<h2>🛠️ Tecnologias utilizadas</h2>
<ul>
  <li><strong>Java 11</strong></li>
  <li><strong>Spring Boot 2.7+</strong></li>
  <li><strong>Spring Data JPA</strong></li>
  <li><strong>Hibernate</strong></li>
  <li><strong>PostgreSQL</strong></li>
  <li><strong>Maven</strong></li>
</ul>

<hr>

<h2>⚡ Configuração do ambiente</h2>
<ol>
  <li>Certifique-se de ter as ferramentas instaladas:
    <ul>
      <li>JDK 11+</li>
      <li>Maven</li>
      <li>PostgreSQL</li>
      <li>IntelliJ IDEA (ou outro IDE de sua preferência)</li>
    </ul>
  </li>
  <li>Configure o banco de dados PostgreSQL:
    <ul>
      <li>Crie um banco de dados chamado <code>parking_control</code>.</li>
      <li>Atualize o arquivo <code>application.properties</code> com as credenciais do banco.</li>
    </ul>
  </li>
  <li>Execute o projeto através do Maven ou diretamente pela IDE.</li>
</ol>

<hr>

<h2>🚀 Como usar</h2>
<p>
  <strong>Testes da API:</strong> Utilize ferramentas como <a href="https://www.postman.com/">Postman</a> ou <a href="https://insomnia.rest/">Insomnia</a> para testar as rotas da aplicação.
</p>
<p>Endpoints principais:</p>
<ul>
  <li><code>POST /parking-spot</code>: Cadastrar nova vaga de estacionamento.</li>
  <li><code>GET /parking-spot</code>: Listar todas as vagas (com paginação).</li>
  <li><code>GET /parking-spot/{id}</code>: Buscar vaga por ID.</li>
  <li><code>PUT /parking-spot/{id}</code>: Atualizar informações de uma vaga.</li>
  <li><code>DELETE /parking-spot/{id}</code>: Remover vaga.</li>
</ul>

<hr>

<h2>📂 Estrutura do projeto</h2>
<p>O projeto foi estruturado seguindo os princípios do MVC:</p>
<ul>
  <li><strong>Model</strong>: Representação das entidades e mapeamento para o banco de dados.</li>
  <li><strong>Controller</strong>: Pontos de entrada da API e mapeamento de rotas.</li>
  <li><strong>Service</strong>: Camada intermediária com regras de negócio.</li>
  <li><strong>Repository</strong>: Interface de persistência usando Spring Data JPA.</li>
</ul>

<hr>

<h2>🎯 Objetivo do projeto</h2>
<p>
  Este projeto foi criado como um estudo prático para entender o funcionamento do Spring Boot, explorando conceitos como:
</p>
<ul>
  <li>Inversão de Controle (IoC) e Injeção de Dependências (DI).</li>
  <li>Configuração inicial com Spring Initializr.</li>
  <li>Conexão com banco de dados relacional usando JPA e Hibernate.</li>
  <li>Validações e boas práticas no desenvolvimento de APIs.</li>
</ul>

<hr>

<h2>📚 Recursos adicionais</h2>
<ul>
  <li>Link para o projeto no GitHub: <a href="#">[Adicionar o link aqui]</a></li>
  <li>Material de apoio:
    <ul>
      <li><a href="https://spring.io/projects/spring-boot">Documentação oficial do Spring Boot</a></li>
      <li>Ferramentas úteis: <a href="https://www.postman.com/">Postman</a>, <a href="https://www.pgadmin.org/">PgAdmin</a></li>
    </ul>
  </li>
</ul>
