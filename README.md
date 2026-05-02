<h1 align="center">🎓 ProjetoADS - Sistema de Gestão Acadêmica</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-blue.svg" alt="Java Badge">
  <img src="https://img.shields.io/badge/Spring_Boot-3.0-brightgreen.svg" alt="Spring Boot Badge">
  <img src="https://img.shields.io/badge/Projeto-Concluído-success.svg" alt="Status Badge">
</p>

<p align="center">
  Sistema web desenvolvido com Spring Boot para gerenciamento de turmas, professores e alunos em uma instituição de ensino.
  <br>
  Projeto final da disciplina de Programação Orientada a Objetos 2 - Faculdade Senac DF 🎓.
</p>

<hr>

<h2>🧠 Aprendizados</h2>

<p>
  Este projeto foi fundamental para consolidar conhecimentos em desenvolvimento web com Java e frameworks modernos. Nele, foi possível:
</p>

<ul>
  <li>Dominar o uso do Spring Boot para construção de APIs REST</li>
  <li>Trabalhar com Thymeleaf para criar interfaces HTML integradas ao backend</li>
  <li>Utilizar Spring Data JPA para mapeamento objeto-relacional (ORM)</li>
  <li>Aplicar boas práticas de arquitetura em camadas</li>
  <li>Fazer a modelagem de entidades reais (alunos, professores, turmas) e seus relacionamentos</li>
</ul>

<hr>

<h2>📋 Descrição do Projeto</h2>

<p>
  O sistema permite a gestão de componentes acadêmicos de uma instituição, oferecendo funcionalidades como:
</p>

<ul>
  <li>Cadastro e listagem de <strong>alunos</strong>, <strong>professores</strong> e <strong>turmas</strong></li>
  <li>Associação de professores a turmas</li>
  <li>Matrícula de alunos em turmas</li>
  <li>Visualização estruturada das turmas e seus participantes</li>
</ul>

<p>
  A aplicação foi projetada com foco em usabilidade e organização, respeitando os princípios da orientação a objetos e do desenvolvimento baseado em camadas.
</p>

<hr>

<h2>🛠️ Como foi feito</h2>

<ul>
  <li><strong>Spring Boot:</strong> para criar o backend robusto e escalável com mínima configuração</li>
  <li><strong>Spring Data JPA:</strong> utilizado para persistência de dados com base em repositórios e queries automáticas</li>
  <li><strong>Thymeleaf:</strong> motor de templates para renderização dinâmica do conteúdo HTML</li>
  <li><strong>Maven:</strong> para gerenciamento de dependências e build do projeto</li>
  <li><strong>PostgreSQL:</strong> banco de dados relacional utilizado para armazenar as informações da aplicação</li>
</ul>

<hr>

<h2>📌 Tecnologias Utilizadas</h2>

<ul>
  <li><a href="https://www.java.com/">Java 17</a></li>
  <li><a href="https://spring.io/projects/spring-boot">Spring Boot</a></li>
  <li><a href="https://spring.io/projects/spring-data-jpa">Spring Data JPA</a></li>
  <li><a href="https://www.thymeleaf.org/">Thymeleaf</a></li>
  <li><a href="https://maven.apache.org/">Apache Maven</a></li>
  <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
</ul>

<hr>

<h2>📁 Estrutura do Projeto</h2>

<pre>
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── projetoads/
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               ├── repository/
│   │   │               └── service/
│   │   └── resources/
│   │       ├── templates/
│   │       ├── static/
│   │       └── application.properties
├── pom.xml
</pre>

<hr>

<h2>🚀 Como Executar</h2>

<ol>
  <li>Clone o repositório</li>
  <li>Importe como projeto Maven em sua IDE (IntelliJ, Eclipse, VSCode...)</li>
  <li>Configure as credenciais do banco de dados PostgreSQL em <code>src/main/resources/application.properties</code></li>
  <li>Execute a classe principal do projeto</li>
  <li>Acesse <code>http://localhost:8080</code> para utilizar o sistema</li>
</ol>

<hr>

<h2>🤝 Contato</h2>

<p>
  Feito com 💙 por Juliano Oliveira. Entre em contato pelo <a href="https://github.com/JulianoCLI">GitHub</a>!
</p>
