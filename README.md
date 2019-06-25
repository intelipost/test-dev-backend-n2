

### Desafio

Não vivemos sem música e queremos saber quais álbuns são/tem nossos cantores e/ou bandas favoritas 😎

Muitos cantores aparecem em vários álbuns e com isso nossas opções aumentam muito 😅.

Exemplo:

| Nome  | Álbuns  |
|---|---|
| Sidney Magal  | "Baila Magal", "Coração Latino" e Vibrações  |
|  Wesley Safadão |  "Ws Mais um Vez", "Eu e a torcida do Brasil" e "Romance com safadeza" |
|  Serj tankian |  "Harakiri", "Black Blooms" e "The Rough Dog" |
|  Mike Shinoda |  "The Rising Tied", "Post Traumatic" e "Where'd You Go  |

## Tarefas

 * Crie um microserviço para procurarmos os artistas
 * Crie uma api que possamos listar, cadastrar, deletar e atualizar nossos artistas, álbuns e links de acesso (C.R.U.D).
 * Crie um endpoint que ao informar o nome do artista nos devolva os álbuns relacionados a ele e o link (use a api do [spotify](https://developer.spotify.com/documentation/web-api/)).

## Regras
 
 * Os álbuns devem ser listados por ordem alfabética, no caso de existir um com dois primeiros nomes iguais mostrar apenas o menor.
 * Os dados tem a validade de 1 hora, ou seja durante esse período a resposta deve ser sempre a mesma.
 * Ao pesquisar um artista que não existem em nossa base, popular o banco de dados com as informações obtidas.
 * Ao pesquisar por um artista que não existe retornar um HTTP Status que achar mais adequado.

## O que esperamos ?

 * Explicação de como rodar localmente e também como seria possível realizar o deploy.
 * Testes
 * Código com boa legibilidade
 * Commits pequenos
