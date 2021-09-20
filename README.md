# minha-lista-de-filmes
  
- Projeto para listagem,detalhamento e gerenciamento de filmes, possibilitando o filtro dos filmes por nome ou gênero em Angular

- Ao acessar a API ela redireciona automaticamente para para `http://localhost:4200/filmes` onde é listado todos os filmes.
![filme1](https://user-images.githubusercontent.com/30246572/134058142-5a94a4e6-9f0c-429d-bedf-7b405c4e02ab.png)

- Ao acessar `http://localhost:4200/filmes/cadastro` traz a possibilidade de adicionar um novo filme.
![filme2](https://user-images.githubusercontent.com/30246572/134058155-97e14187-4d06-404c-a8aa-540d272ac358.png)

- Ao acessar `http://localhost:4200/filmes/:id` ela exibe uma tela com todas as informações do filme especifico, onde id é a indentificaçao do filme.
![filme3](https://user-images.githubusercontent.com/30246572/134058190-25196c9f-c5a9-46fb-8cce-65fa3472e983.png)

- Ao acessar `http://localhost:4200/filmes/cadastro/:id` ela exibe uma tela que possibilita a alteração das informações do filme, onde id é a indentificaçao do filme.
![filmes3](https://user-images.githubusercontent.com/30246572/134058198-4a2243b8-a06d-4670-ae48-4740cbfa00d2.png)

# Tecnologias utilizadas
- Angular 12
- TypeScript
- JavaScript
- HTML5
- CSS3

# Como compilar e executar o programa

- Executar `ng serve` em um servidor de desenvolvimento na pasta minha-lista-de-filmes. Navegar para `http://localhost:4200/filmes`. 
- Executar `json-server --watch db.json` em um servidor de desenvolvimento na pasta minha-lista-de-filmes, para subir o JSON que é aonde fica salvo os filmes.
