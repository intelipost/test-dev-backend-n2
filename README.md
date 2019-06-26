

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

## Instruções

 * Resolva o teste em um repositório privado do github. 
	* Nos envie o link do mesmo e libere acesso aos usuários da intelipost.
 * Considere que a aplicação terá muitos acessos simultâneos, logo muitos acessos concorrentes.

## Tarefas
 
 * Crie uma api que possamos listar, cadastrar, deletar e atualizar nossos artistas (C.R.U.D).
 * Crie um endpoint de rating dos artistas (0 - 5 pontos).
 * Crie um endpoint que ao informar o nome do artista nos devolva os álbuns relacionados a ele, o link de acesso de cada álbum (use a api do [spotify](https://developer.spotify.com/documentation/web-api/)), e o rating médio de cada artista.
 

## Regras
 
 * Os álbuns devem ser listados por ordem alfabética, no caso de existir um com dois primeiros nomes iguais mostrar apenas o menor.
 
   * Exemplo: <br/>
      * Lista de álbuns <br/>
        1) Post Traumatic EP <br/>
        2) Post Traumatic EP Deluxe (Não exibir) <br/>
        <br/>
      
 * Os dados tem a validade de 1 hora, ou seja durante esse período a resposta deve ser sempre a mesma.
 * Ao pesquisar por um artista que não existe retornar um HTTP Status que achar mais adequado.

## O que esperamos ?

 * Explicação da stack utilizada (justifique suas escolhas).
 * Explicação de como rodar localmente e também como seria possível realizar o deploy.
 * Testes
 * Legibilidade
 * Escalabilidade 
 * Commits pequenos
 * Ver sua experiência codificando.
