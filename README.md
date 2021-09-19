# minha-lista-de-filmes
  
- Projeto para listagem,detalhamento e gerenciamento de filmes, possibilitando o filtro dos filmes por nome ou gênero em Angular

- Ao acessar a API ela redireciona automaticamente para para `http://localhost:4200/filmes` onde é listado todos os filmes.

- Ao acessar `http://localhost:4200/filmes/cadastro` traz a possibilidade de adicionar um novo filme.

- Ao acessar `http://localhost:4200/filmes/:id` ela exibe uma tela com todas as informações do filme especifica, onde id é a indentificaçao do filme.

# Tecnologias utilizadas
- Angular 12
- TypeScript
- JavaScript
- HTML5
- CSS3

# Como compilar e executar o programa

- Executar `ng serve` em um servidor de desenvolvimento na pasta minha-lista-de-filmes. Navegar para `http://localhost:4200/filmes`. 
- Executar `json-server --watch db.json` em um servidor de desenvolvimento na pasta minha-lista-de-filmes, para subir o JSON que é aonde fica salvo os filmes.
