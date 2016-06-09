<h1>Web Service Project</h1>

Sistemas para internet, 4ºCiclo. <br>
Henry Hiraki, Claudir Furlan, Robson Périco, Julio Domingos

======================================================================
<h2>Sobre</h2>
É um web service, puro consumido via curl. Elaboramos uma locadora de jogos, filmes e series.<br>
O sistema esta RestFul, possui as quatro operações: GET, POST, PUT, DELETE.

======================================================================
<h2>Como utilizar o curl</h2>

<h3>Método GET</h3>

<p>Tabela Jogos</p>
```
https://webservice-jogos-henryhiraki22.c9users.io/buscaJogo/1 <- retorna um jogo via ID.

https://webservice-jogos-henryhiraki22-1.c9users.io/listaJogos    <- retorna todos os jogos contido no banco.

```
<p>Tabela Usuário</p>

```
curl https://webservice-jogos-henryhiraki22.c9users.io/buscaUsuario/5 <- retorna via ID.

curl https://webservice-jogos-henryhiraki22.c9users.io/listaUsuarios <- retorna todos os usuários.

```
<p>Tabela Fimes</p>

```


```
<p> Tabela Séries </p>

```


```

<h3>Método POST</h3>

<p>Tabela Jogos</p>

```
curl https://webservice-jogos-henryhiraki22.c9users.io/insereJogo / -v / X POST / -H 'content-type:application/json' / -d '{"nome":"FIFA","valor":299.99, "plataforma":"Playstation", "genero":"SOCCER"}' 
```

<p>Tabela Usuários</p>
```
curl https://webservice-jogos-henryhiraki22.c9users.io/insereUsuario / -v / -X POST / -H 'content-type:application/json' / -d '{"nome":"Henry","login":"Hirak","senha":"123"}'
```
<p>Tabela Fimes</p>
```

```
<p> Tabela Séries </p>
```

```
<h3>Método PUT</h3>

<p>Tabela Jogos<p>
```
curl https://webservice-jogos-henryhiraki22.c9users.io/atualizaJogo / -v / -X PUT / -H 'content-type:application/json' / -d '{"id":8,"nome":"FORZA-6","valor":50.00,"plataforma":"XBOX","genero":"Corrida"}'
```










