# Rest API Sample Go/Sqlite
## API Restful que utiliza usuários/emails como exemplo

<p align="center">
  <img src="images/golang.png"/ alt="Golang">
</p>


A aplicação foi escrita totalmente em Go 🐹, visando utilizar o mínimo de dependências possíveis, tratar a maioria dos erros com os devidos cuidados e documentada com comentários de fácil entendimento

Pacotes utilizados

- Gorilla/Mux 🦍
- GORM


## Features

- Na aplicação é possível ver os usuários já adicionados previamente
- Adicionar novos usuários
- Ver usuários específicos
- Excluir algum usuário desejado
- Atualizar as informações


## Requisitos

```sh
Golang: https://golang.org/dl/
Sqlite3 instalado e configurado com as configurações desejadas
API Client de sua preferência (O que aparece nas imagens se chama Postman)

Após ter instalado o go
Gorilla mux: go get -u github.com/gorilla/mux
GORM: go get -u gorm.io/gorm
```


## Na prática

Iniciando a aplicação

![](images/1-starting.png)


Acessando os usuários já inseridos

![](images/2-gettingusers.png)


Adicionando novos usuários

![](images/3-addingusers01.png)

![](images/3-addingusers02.png)

![](images/3-addingusers03.png)

![](images/3-addingusers04.png)


Atualizando o usuário desejado

![](images/4-updateuser01.png)

![](images/4-updateuser02.png)


Deletando o usuário desejado

![](images/5-deleteuser01.png)

![](images/5-deleteuser02.png)



## Utilização

Basta utilizar o comando go build e aproveitar o aplicativo! 😊
