# data information block
> CREATE TABLE usuarios (
CREATE TABLE usuarios (
       ^^^^^

Uncaught SyntaxError: Unexpected identifier
>     id INT NOT NULL PRIMARY KEY,
    id INT NOT NULL PRIMARY KEY,
       ^^^

Uncaught SyntaxError: Unexpected identifier
>     nome VARCHAR(50) NOT NULL,
    nome VARCHAR(50) NOT NULL,
         ^^^^^^^

Uncaught SyntaxError: Unexpected identifier
>     email VARCHAR(50) NOT NULL,
    email VARCHAR(50) NOT NULL,
          ^^^^^^^

Uncaught SyntaxError: Unexpected identifier
>     idade INT NOT NULL
    idade INT NOT NULL
          ^^^

Uncaught SyntaxError: Unexpected identifier
> INSERT INTO usuarios (id, nome, email, idade)
INSERT INTO usuarios (id, nome, email, idade)
       ^^^^

Uncaught SyntaxError: Unexpected identifier
> VALUES (1, 'João', 'joao@example.com', 30);
Uncaught ReferenceError: VALUES is not defined
> INSERT INTO usuarios (id, nome, email, idade)
INSERT INTO usuarios (id, nome, email, idade)
       ^^^^

Uncaught SyntaxError: Unexpected identifier
> VALUES (2, 'Maria', 'maria@example.com', 25);
Uncaught ReferenceError: VALUES is not defined
> INSERT INTO usuarios (id, nome, email, idade)
INSERT INTO usuarios (id, nome, email, idade)
       ^^^^

Uncaught SyntaxError: Unexpected identifier
> VALUES (3, 'José', 'jose@example.com', 35);
Uncaught ReferenceError: VALUES is not defined
> import java.sql.*;
import java.sql.*;
^^^^^^

Uncaught:
SyntaxError: Cannot use import statement inside the Node.js REPL, alternatively use dynamic import
>
> public class SelecaoDados {
public class SelecaoDados {
       ^^^^^

Uncaught SyntaxError: Unexpected token 'class'
>     public static void main(String[] args) {
    public static void main(String[] args) {
           ^^^^^^

Uncaught SyntaxError: Unexpected identifier
>         try {
...             Connection conexao = ConexaoBanco.getConnection();
            Connection conexao = ConexaoBanco.getConnection();
                       ^^^^^^^

Uncaught SyntaxError: Unexpected identifier
>             Statement stmt = conexao.createStatement();
            Statement stmt = conexao.createStatement();
                      ^^^^

Uncaught SyntaxError: Unexpected identifier
>             ResultSet rs = stmt.executeQuery("SELECT * FROM usuarios");
            ResultSet rs = stmt.executeQuery("SELECT * FROM usuarios");
                      ^^

Uncaught SyntaxError: Unexpected identifier
>             while (rs.next()) {
...                 int id = rs.getInt("id");
                int id = rs.getInt("id");
                    ^^

Uncaught SyntaxError: Unexpected identifier
>                 String nome = rs.getString("nome");
                String nome = rs.getString("nome");
                       ^^^^

Uncaught SyntaxError: Unexpected identifier
>                 String email = rs.getString("email");
                String email = rs.getString("email");
                       ^^^^^

Uncaught SyntaxError: Unexpected identifier
>                 int idade = rs.getInt("idade");
                int idade = rs.getInt("idade");
                    ^^^^^

Uncaught SyntaxError: Unexpected identifier
>                 System.out.println(id + " " + nome + " " + email + " " + idade);
Uncaught ReferenceError: System is not defined
>             }
            }
            ^

Uncaught SyntaxError: Unexpected token '}'
>         } catch (SQLException e) {
        } catch (SQLException e) {
        ^

Uncaught SyntaxError: Unexpected token '}'
>             System.out.println("Erro ao selecionar dados: " + e.getMessage());
Uncaught ReferenceError: System is not defined
>         }
        }
        ^

Uncaught SyntaxError: Unexpected token '}'
>     }
    }
    ^

Uncaught SyntaxError: Unexpected token '}'
> }
}
^

Uncaught SyntaxError: Unexpected token '}'
> <table>
<table>
^

Uncaught SyntaxError: Unexpected token '<'
>   <tr>
  <tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>     <th>ID</th>
    <th>ID</th>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <th>Nome</th>
    <th>Nome</th>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <th>Email</th>
    <th>Email</th>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <th>Idade</th>
    <th>Idade</th>
    ^

Uncaught SyntaxError: Unexpected token '<'
>   </tr>
  </tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>   <tr>
  <tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>1</td>
    <td>1</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>João</td>
    <td>João</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>joao@example.com</td>
    <td>joao@example.com</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>30</td>
    <td>30</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>   </tr>
  </tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>   <tr>
  <tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>2</td>
    <td>2</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>Maria</td>
    <td>Maria</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>maria@example.com</td>
    <td>maria@example.com</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>25</td>
    <td>25</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>   </tr>
  </tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>   <tr>
  <tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>3</td>
    <td>3</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>José</td>
    <td>José</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>jose@example.com</td>
    <td>jose@example.com</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>     <td>35</td>
    <td>35</td>
    ^

Uncaught SyntaxError: Unexpected token '<'
>   </tr>
  </tr>
  ^

Uncaught SyntaxError: Unexpected token '<'
> </table>
</table>
^

Uncaught SyntaxError: Unexpected token '<'
> table {
table {
      ^

Uncaught SyntaxError: Unexpected token '{'
>   border-collapse: collapse;
  border-collapse: collapse;
                 ^

Uncaught SyntaxError: Unexpected token ':'
>   width: 100%;
  width: 100%;
             ^

Uncaught SyntaxError: Unexpected token ';'
> }
}
^

Uncaught SyntaxError: Unexpected token '}'
>
> th, td {
th, td {
       ^

Uncaught SyntaxError: Unexpected token '{'
>   text-align: left;
  text-align: left;
            ^

Uncaught SyntaxError: Unexpected token ':'
>   padding: 8px;
  padding: 8px;
           ^

Uncaught SyntaxError: Invalid or unexpected token
> }
}
^

Uncaught SyntaxError: Unexpected token '}'
>
> th {
th {
   ^

Uncaught SyntaxError: Unexpected token '{'
>   background-color: #4CAF50;
  background-color: #4CAF50;
                  ^

Uncaught SyntaxError: Unexpected token ':'
>   color: white;
Uncaught ReferenceError: white is not defined
> }
}
^

Uncaught SyntaxError: Unexpected token '}'
>
> tr:nth-child(even) {
tr:nth-child(even) {
                   ^

Uncaught SyntaxError: Unexpected token '{'
>   background-color: #f2f2f2;
  background-color: #f2f2f2;
                  ^

Uncaught SyntaxError: Unexpected token ':'
> }
}
^

Uncaught SyntaxError: Unexpected token '}'
>
