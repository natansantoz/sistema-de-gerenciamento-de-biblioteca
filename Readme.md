<h1 align="center">Sistema de Gerenciamento de Biblioteca</h1>

<p align="center">
		<a href=""><img alt="Java" src="https://img.shields.io/badge/Language-Java-2d5b7c.svg" height="20"/></a>
<a href=""><img alt="Swing" src="https://img.shields.io/badge/GUI-Java%20Swing-3779aa.svg" height="20"/></a>
<a href=""><img alt="Maven" src="https://img.shields.io/badge/Build-Maven-4ea7e1.svg" height="20"/></a>
<a href=""><img alt="JasperReports" src="https://img.shields.io/badge/Reports-JasperReports-fefab8.svg" height="20"/></a>
<a href=""><img alt="MySQL" src="https://img.shields.io/badge/Database-MySQL-2d5b7c.svg" height="20"/></a>
	</p>

Implementação de um **Sistema de Gerenciamento de Empréstimos de Livros** para biblioteca desenvolvido como trabalho de conclusão da disciplina **Programação Orientada a Objetos**.

O sistema é desktop e utiliza interfaces gráficas em Java Swing.

### Funcionalidades
- Gerenciamento de livros
- Gerenciamento de clientes
- Gerenciamento de empréstimos e devoluções
- Autenticação com sistema de login

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

<h3 align="center">Tela de Login</h3>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="#">
      <img src="https://github.com/natansantoz/TCD-POO/blob/main/imagens/login.png" width="600" style="max-width: 100%;">
  </a>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

<h3 align="center">Tela Principal</h3>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="#">
      <img src="https://github.com/natansantoz/TCD-POO/blob/main/imagens/02.png" width="700" style="max-width: 100%;">
  </a>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

<h3 align="center">Gerenciamento de Livros</h3>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="#">
      <img src="https://github.com/natansantoz/TCD-POO/blob/main/imagens/3.png" width="700" style="max-width: 100%;">
  </a>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

<h3 align="center">Gerenciamento de Clientes</h3>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="#">
      <img src="https://github.com/natansantoz/TCD-POO/blob/main/imagens/5.png" width="700" style="max-width: 100%;">
  </a>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

<h3 align="center">Gerenciamento de Empréstimos</h3>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="#">
      <img src="https://github.com/natansantoz/TCD-POO/blob/main/imagens/4.png" width="700" style="max-width: 100%;">
  </a>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

<h3 align="center">Diagrama de Classes</h3>

<p align="center">
  <a target="_blank" rel="noopener noreferrer" href="#">
      <img src="https://github.com/natansantoz/TCD-POO/blob/main/imagens/Diagrama.png" width="800" style="max-width: 100%;">
  </a>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

### Estrutura do Projeto

```bash
TCD-POO/
├── dependency-reduced-pom.xml
├── imagens
│   ├── 02.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   ├── Diagrama.png
│   └── login.png
├── nbactions.xml
├── pom.xml
├── Readme.md
└── src
    └── main
        ├── java
        │   └── io
        │       └── github
        │           └── natansantoz
        │               └── trabalho_classes
        │                   ├── dao
        │                   │   ├── AutorDao.java
        │                   │   ├── AutorLivroDao.java
        │                   │   ├── ClienteDao.java
        │                   │   ├── ConexaoBd.java
        │                   │   ├── Dao.java
        │                   │   ├── EditoraDao.java
        │                   │   ├── EmprestimoDao.java
        │                   │   ├── ExemplarDao.java
        │                   │   ├── GeneroDao.java
        │                   │   ├── IDao.java
        │                   │   ├── IdiomaDao.java
        │                   │   ├── LivroDao.java
        │                   │   └── UsuarioDao.java
        │                   ├── entity
        │                   │   ├── Autor.java
        │                   │   ├── AutorLivro.java
        │                   │   ├── Cliente.java
        │                   │   ├── Contato.java
        │                   │   ├── Editora.java
        │                   │   ├── Emprestimo.java
        │                   │   ├── Entidade.java
        │                   │   ├── Exemplar.java
        │                   │   ├── Genero.java
        │                   │   ├── Idioma.java
        │                   │   ├── Livro.java
        │                   │   ├── PessoaFisica.java
        │                   │   ├── PessoaJuridica.java
        │                   │   └── Usuario.java
        │                   ├── gui
        │                   │   ├── AtualizarAutor.java
        │                   │   ├── AtualizarCliente.java
        │                   │   ├── AtualizarEditora.java
        │                   │   ├── AtualizarEmprestimo.java
        │                   │   ├── AtualizarGenero.java
        │                   │   ├── AtualizarIdioma.java
        │                   │   ├── AtualizarLivro.java
        │                   │   ├── AtualizarUsuario.java
        │                   │   ├── CadastrarAutor.java
        │                   │   ├── CadastrarCliente.java
        │                   │   ├── CadastrarEditora.java
        │                   │   ├── CadastrarEmprestimo.java
        │                   │   ├── CadastrarExemplar.java
        │                   │   ├── CadastrarGenero.java
        │                   │   ├── CadastrarIdioma.java
        │                   │   ├── CadastrarLivro.java
        │                   │   ├── CadastrarUsuario.java
        │                   │   ├── componentes
        │                   │   │   ├── Cartao.java
        │                   │   │   ├── ModeloCartao.java
        │                   │   │   ├── PanelBordaApenasEmCima.java
        │                   │   │   ├── PanelBorda.java
        │                   │   │   ├── Tabela.java
        │                   │   │   └── TableHeader.java
        │                   │   ├── ExcluirAutor.java
        │                   │   ├── ExcluirCliente.java
        │                   │   ├── ExcluirEditora.java
        │                   │   ├── ExcluirEmprestimo.java
        │                   │   ├── ExcluirExemplar.java
        │                   │   ├── ExcluirGenero.java
        │                   │   ├── ExcluirIdioma.java
        │                   │   ├── ExcluirLivro.java
        │                   │   ├── ExcluirUsuario.java
        │                   │   ├── InternaTelaTelatorios.java
        │                   │   ├── JanelaPrincipal.java
        │                   │   ├── Login.java
        │                   │   ├── TelaClientes.java
        │                   │   ├── TelaEmprestimos.java
        │                   │   ├── TelaInicio.java
        │                   │   ├── TelaLivros.java
        │                   │   ├── TelaLivrosNaoAdm.java
        │                   │   ├── TelaRelatorios.java
        │                   │   └── TelaUsuarios.java
        │                   ├── Program.java
        │                   └── util
        │                       ├── Endereco.java
        │                       ├── Util.java
        │                       └── ViaCep.java
        └── resources
            ├── Banco_Tabelas_e_Registros_Necessarios.sql
            ├── coffee.jpg
            ├── coffee_stain.png
            ├── Images
            │   ├── awwbook-computer.png
            │   ...
            │   └── icons8_User_Menu_Female_20px_6.png
            ├── relat_alocacoes_1.jasper
            ├── relat_alocacoes.jasper
            ├── RelatorioTCDcliente.jasper
            ├── RelatorioTCDeditora.jasper
            ├── RelatorioTCDemprestimo.jasper
            ├── RelatorioTCDlivro.jasper
            ├── RelatorioTCDusuario.jasper
            └── TestePF.jasper

```

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)

**Ícones**: Ícone dos livros usado na tela de login criado por [mikan933 - Flaticon](https://www.flaticon.com/free-icons/book)

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)](#table-of-contents)
