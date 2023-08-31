# Movies_go
<br>
<br>
[ENG] Movies CRUD API. Run 'main.go', enter the URLs in Postman:
<br>
<br>
GET - Get All Movies

```
http://localhost:8000/movies
```
<br>
<br>
GET - Get Movie By Id

```
http://localhost:8000/movies/{id}
```
<br>
<br>
POST - Create a Movie

```
http://localhost:8000/movies
```
Body
```
{
    "isbn": "2543",
    "title": "Movie Three",
    "director": {
        "firstname": "Jack",
        "lastname": "James"
    }
}
```

<br>
<br>
PUT - Update a Movie

```
http://localhost:8000/movies/{id}
```
Body
```
{
    "isbn": "7658",
    "title": "Movie Four",
    "director": {
        "firstname": "Arnold",
        "lastname": "Tucker"
    }
}
```

<br>
<br>
DELETE - Delete a Movie

```
http://localhost:8000/movies/{id}
```
<br>
<br>
[PT-BR] Filmes CRUD API. Rode 'main.go', insira as URLs no Postman:
<br>
<br>
GET - Listar todos Filmes

```
http://localhost:8000/movies
```
<br>
<br>
GET - Listar Filme por ID

```
http://localhost:8000/movies/{id}
```
<br>
<br>
POST - Criar um Filme

```
http://localhost:8000/movies
```
Body
```
{
    "isbn": "2543",
    "title": "Movie Three",
    "director": {
        "firstname": "Jack",
        "lastname": "James"
    }
}
```

<br>
<br>
PUT - Atualizar um Filme

```
http://localhost:8000/movies/{id}
```
Body
```
{
    "isbn": "7658",
    "title": "Movie Four",
    "director": {
        "firstname": "Arnold",
        "lastname": "Tucker"
    }
}
```

<br>
<br>
DELETE - Deletar um Filme

```
http://localhost:8000/movies/{id}
```
<br>
