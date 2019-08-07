

### Desafio Backend Intelipost

Não vivemos sem música e queremos saber quais álbuns são/tem nossos cantores e/ou bandas favoritas 😎

Muitos cantores aparecem em vários álbuns e com isso nossas opções aumentam muito 😅.

Exemplo:

| Nome  | Álbuns  |
|---|---|
| Sidney Magal  | "Baila Magal", "Coração Latino" e "Vibrações"  |
|  Wesley Safadão |  "Ws Mais um Vez", "Eu e a torcida do Brasil" e "Romance com safadeza" |
|  Serj tankian |  "Harakiri", "Black Blooms" e "The Rough Dog" |
|  Mike Shinoda |  "The Rising Tied", "Post Traumatic", "Post Traumatic EP" e "Where'd You Go  |
|  Michel Teló |  "Bem Sertanejo", "Bem Sertanejo - O Show (Ao Vivo)", "Bem Sertanejo - (1ª Temporada) - EP"|
|  Guns N' Roses |  "Use Your IIIlusion I", "Use Your IIIlusion II" e "Greatest Hits"|
|  Linkin Park |  "Meteora", "Meteora (Bonus Edition)", "Hybrid Theory", "Hybrid Theory (Bonus Edition)" e  "Hybrid Theory Live Around The World"|

## Instruções

 * Resolva o teste em um repositório privado do github. 
	* Libere acesso de leitura do repositório para o usuário techtest@intelipost.com.br
	* Envie um email para techtest@intelipost.com.br notificando a conclusão do teste 
 * Codifique como se fosse um sistema para entrar em produção, que poderia sofrer alterações e adição de novas features.
 * Considere que a aplicação terá muitos acessos simultâneos e que podem existir milhões de artistas
 * Modele o relacionamento entre Artista e Álbum como sendo 1xN
 * Utilize o projeto e as tecnologias fornecidas como base, porém adicione as dependências que considerar necessárias

## Tarefas
 
 * Crie uma API pública em que seja possível listar, cadastrar, deletar e atualizar artistas (C.R.U.D).
 * Crie um endpoint público de rating dos artistas (0 - 5 pontos).
 * Crie um endpoint público de busca por nome do artista, permitindo ordenar por ordem alfabética (asc e desc) e também pelo tamanho do nome do artista em número de letras (futuramente podemos ter outras formas de ordenação).
 * Ao retornar o(s) artista(s), devolva os álbuns relacionados a ele, o link de acesso de cada álbum (use a API do [Spotify](https://developer.spotify.com/documentation/web-api/) com modo de autenticação Client Credentials Flow), e o rating médio de cada artista.

## Regras
 
 * Os álbuns devem ser listados por ordem alfabética. No caso de existir um com as 2 primeiras palavras iguais mostrar apenas o menor.
 
   * Exemplo: <br/>
      * Lista de álbuns <br/>
        1) Post Traumatic EP <br/>
        2) Post Traumatic (Deluxe Version) (**Não exibir**) <br/>
        <br/>

## O que esperamos ?

 * Explicação de como rodar localmente e também como seria possível realizar o deploy.
 * Testes
 * Legibilidade
 * Escalabilidade 
 * Commits pequenos
 * Ver sua experiência codificando
 * CLEAN CODE
 * Keep it simple =] (gostamos de soluções simples e práticas)
