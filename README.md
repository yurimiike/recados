# API de Recados

Link para teste no render

```bash
  https://teste-d86f.onrender.com
```

Instalar as depêndencias do projeto

```bash
  yarn install | npm install
```

Iniciar o projeto

```bash
  yarn run dev | yarn dev | npm run dev
```

## Documentação da API

#### Retorna todos os estudantes, com filtragem por nome opcional

```http
  GET /students/:name?
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `name` | `string` | **Opcional**. Nome do usuário para filtragem |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Atualizar um estudante através do email dele

```http
  PUT /students/email
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `name`      | `string` | **Opcional**. Nome do growdever |
| `email`      | `string` | **Opcional**. Email do growdever |
| `age`      | `number` | **Opcional**. Idade do growdever |
| `turma`      | `number` | **Opcional**. Turma do growdever |
| `class`      | `number` | **Opcional**. Turma do growdever |
| `mentorName`      | `string` | **Opcional**. Nome do mentor |

#### Apagar um estudante através do email dele

```http
  DELETE /students/email
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `email`      | `string` | **Obrigatório**. Email do growdever |
