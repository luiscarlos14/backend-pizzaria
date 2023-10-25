
# API RestFull Projeto Pizzaria

API desenvolvida no curso Fabrica de Apps do Sujeito Programador - Matheus Fraga


## Rodando localmente

Clone o projeto

```bash
  git clone https://github.com/luiscarlos14/backend-pizzaria.git
```

Entre no diretório do projeto

```bash
  cd my-project
```

Instale as dependências

```bash
  npm install ou yarn install
```

Inicie o servidor

```bash
  npm run dev ou yarn run dev
```


## Documentação da API

#### Adiciona um usuário
```http
  POST /users/
```
| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `name` | `string` | **Obrigatório** |
| `email` | `string` | **Obrigatório** |
| `password` | `string` | **Obrigatório** |

#### Login
```http
  POST /session
```
| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `email` | `string` | **Obrigatório** |
| `password` | `string` | **Obrigatório** |


#### Buscar usuário
```http
  GET /me
```
##### Headers | Authorization: Bearer [access_token]


#### Cadastrar Categoria
```http
  POST /category
```
| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `name` | `string` | **Obrigatório** |

#### Listar Categorias
```http
  GET /category
```
##### Headers | Authorization: Bearer [access_token]


## Aprendizados

Projeto em desenvolvimento...


## Stack utilizada


**API Restfull:** Node JS, Typescript, Express, Postgres


## Referência

 - [Sujeito Programador](https://sujeitoprogramador.com/fabricadeaplicativos/)
 - [Documentação do Prisma](https://www.prisma.io/)
 
