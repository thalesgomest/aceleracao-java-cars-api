# API Car

### POST Request

Execute a aplicação e faça um post na rota `http://localhost:8080/api/car` com o seguinte corpo:

```JSON
{
	"modelo": "Fiat Argo 1.3",
	"fabricante": "Fiat",
	"dataFabricacao": "10/02/2006",
	"valor": 10.000,
	"anoModelo": 2023
}
```

Requisitos:

-   [x] Criar um controller que represente o formato dos dados fornecidos
-   [x] Criar uma rota de api que possa ser consumida via POST
-   [x] Criar um DTO que represente os dados recebidos
-   [x] Imprimir no console do Spring alguns dos dados pegando do DTO recebidos via post.
