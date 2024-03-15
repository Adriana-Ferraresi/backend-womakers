# fastAPI TODO list - aula 11 - Instrutora Nara Guimarães



## Overview:
Para o desenvolvimento desse projeto precisamos ter instaladas as seguintes bibliotecas:

`pip install fastapi uvicorn jinja2 python-multipart`

O intuito do mesmo é criar uma tabela contendo as tarefas com os seus respectivos dias, permitindo com que as mesmas sejam excluidas e que outras sejam inseridas na lista

## Rotas:

`/` - GET: obter os dados no arquivo `database.json` que faz o papel do nosso banco de dados 

`/delete/{id}` - GET: exclui o item da lista de tarefas

`/add` - POST: adiciona um item a lista de tarefas 


## Estilizacao:

Usou-se bootstrap e css para definir o estilo dos elementos

## Organizacao do Repositório:

```
todo_list/
├── main.py
├── database.json
├── static/
│   └── styles.css
└── templates/
    └── todo_list.html

```
