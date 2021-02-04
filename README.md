# API REST CRUD node.js
Este é um projeto simples, afins de estudo de uma api rest em node.js

# Requisitos
	- Versão do node v14.15.4
	- Postman (Para teste dos endpoints)
	- Visual Studio Code


## Criação do arquivo de dependências, e do projeto
```
npm init -y
```

## Dependências
Instalando depednências da api
```
npm install --save expre/ss
npm install --save-nodemon
```

## Iniciando servidor
Inicie o servidor digitando no terminal
```
npm start
```

### Testes
Utilize o postman para as rotas:
	payload:	
	{
		firstName: "",
		lastName: "",
		age: 
	}
	
### Rotas
	- (GET) http://localhost:5000/users -> Retorna lista de usuários registrados
	- (POST / payload) http://localhost:5000/users -> Criando usuário
	- (DELETE) http://localhost:5000/:id -> Deleta usuário através do id
	- (PATCH / payload) http://localhost:5000/:id -> Edita usuário através do id, alterando campo informado no payload

