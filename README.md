# Sistema de Login e Cadastro - PHP & MySQL 🖥
Fantástico sistema com:
<br>
<ul>
  <li>Tela de Home</li>
  <li>Tela de Login</li>
  <li>Cadastro</li>
  <li>Sessões</li>
  <li>Listagem de Registros</li>
  <li>Edição de Registros</li>
  <li>Deleção de Registros</li>
  <li>Pesquisa</li>
  <li>...</li>
</ul> 
### Prototipagem 

![GIF](GitHub/sistemacadastrophp.gif)

### Autor

* **Luca E. Medeiros** *Estudante universitário*

* [Github](https://github.com/lucaem)

* [Linkedin](https://www.linkedin.com/in/luca-estrella-medeiros/)
* [WhatsApp](https://api.whatsapp.com/send?phone=5567999977177)
* luca.em78@mail.com

### licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE.md](LICENSE) para obter detalhes

### Tecnologias utilizadas

* HTML
* CSS
* JAVASCRIPT
* PHP
* MYSQL


## Como usar o Sistema??

1. Clone este repositório;
2. Vai até o localhost > phpmyadmin;
3. Crie um Banco de Dados chamado formulario;
4. Insira sql o seguinte código: 

~~~~
create database formulario;
use formualrio;
create table usuarios(
    id_usuario int AUTO_INCREMENT PRIMARY KEY,
    nome varchar(30),
    senha varchar(30),
    email varchar(40),
    telefone varchar(30),
    sexo varchar(40),
    data_nasc Date,
    cidade varchar(40),
    estado varchar(40),
    endereco varchar(40),
);
~~~~

5. Salve o BD. 




