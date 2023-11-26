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

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Senha do usuário |

#### Realizar o login de Usuário

```http
  POST /login
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Senha do usuário |

#### Listar todos os Usuários

```http
  GET /listar-todos-usuarios
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `----`      | `----` | Lista todos os usuários cadastrados, sem precisar de parâmetro |

#### Visualizar Usuário

```http
  GET /visualizar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` |  Visualiza um usuário especifico, encontrado pelo id |

#### Alterar dados de Usuário

```http
  PUT /alterar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. Id do usuário |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |


#### Deletar um usuário

```http
  DELETE /deletar-usuario/
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id_usuario`      | `string` | **Obrigatório**. Id do usuário que deseja deletar |


#### Adicionar recado

```http
  POST /adicionar-recado
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id_usuario`      | `string` | **Obrigatório**. Id do usuário |
| `titulo`      | `string` | **Obrigatório**. Titulo do recado |
| `descricao`      | `string` | **Obrigatório**. Conteúdo do recado |

#### Listar recados

```http
  GET /listar-recado/:id?
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | Lista todos os recados de um usuário especifico, encontrado pelo id |

#### Visualizar recado especifico

```http
  GET /visualizar-recado
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id_usuario`      | `string` | **Obrigatório**. Id do usuário |
| `id_recado`      | `string` | **Obrigatório**.Id do recado a ser mostrado |


#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |

#### Cadastrar um usuário

```http
  POST /adicionar-usuario
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `nome`      | `string` | **Obrigatório**. Nome do usuário |
| `email`      | `string` | **Obrigatório**. Email do usuário |
| `senha`      | `string` | **Obrigatório**. Idade do usuário |


