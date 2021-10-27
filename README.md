### Api para registro de pokemons

### ENDPOINT para registro

## POST/register

requeste:

```json
{
  "name": "Name User",
  "email": "user123@gmail.com",
  "password": "user321",
  "age": 69
}
```

reponse:

```json
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InJvZHJpZ28xMkBnbWFpbC5jb20iLCJpYXQiOjE2MzUyMDk0NzQsImV4cCI6MTYzNTIxMzA3NCwic3ViIjoiMSJ9.r3QQ3PC4MGN6AdVYS0N1gRzEvD60-8_KQHyHZSkuRQs",
  "name": "Name User",
  "email": "user123@gmail.com",
  "password": "user321",
  "age": 69,
  "id": 1
}
```

### LOGIN

## POST/ login

request:

```json
{
  "email": "user123@gmail.com",
  "password": "user321"
}
```

response:

```json
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJlbWFpbCI6InJvZHJpZ28xMkBnbWFpbC5jb20iLCJpYXQiOjE2MzUyMDk0OTEsImV4cCI6MTYzNTIxMzA5MSwic3ViIjoiMSJ9.B8amhSCbbsoRgtH3ihpKh2n5es3okm1mJVQf6lEV5-U",
  "name": "Name User",
  "email": "user123@gmail.com",
  "password": "user321",
  "age": 69,
  "id": 1
}
```

### Pokemons register

## POST/ Pokemons

request:

```json
{
  "name": "Pikachu",
  "type": "Eletrico",
  "Weight": 4,
  "height": 0.5
}
```

response:

```json
{
  "name": "Pikachu",
  "type": "Eletrico",
  "Weight": 4,
  "height": 0.5,
  "id": 4
}
```

### DELETE/Pokemons/id-pokemon
