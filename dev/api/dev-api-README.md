# Mock User API

[Descrição curta...]

## Descrição do Projeto

[Descrição completa...]

### Arquivos do Projeto

- **`arquivo.json`** - [Descrição do que contém]
- **`arquivo.json`** - [Descrição do que contém]
- **`pasta/arquivo.ts`** - [Descrição do que contém]

## Instalação e Execução

### Pré-requisitos

- [Ambiente de execução]
- [Gerenciador de pacote]

### Passos para Instalar Localmente

1. **Clone o repositório**:
```
git clone seu-projeto-url-no-github
````

2. **Instale as dependências**:

```
npm install // alterar conforme realidade
```

3. **Inicie o servidor**:
```bash
npm run dev // alterar conforme realidade
```

### Scripts Disponíveis

[Se houver]

## Endpoints da API

[Adicione uma imagem]


### GET /endpoint
[O que faz]

**Resposta:** (Status [Code])
```json
[
  {
    "id": "uuid-string",
    "name": "Fulano de Tal",
  }
]
```

### POST /endpoint
[O que faz]

**Body:**
```json
{
  "name": "Fulano de Tal",
}
```

**Resposta:** (Status [Code])
```json
{
  "id": "uuid-string",
  "name": "Fulano de Tal",
}
```

### GET /endpoint
[O que faz]

**Resposta:** (Status [Code])
```json
{
  "id": "uuid-string",
  "name": "Fulano de Tal",
}
```

### PUT /endpoint
[O que faz]

**Body (todos os campos são opcionais):**
```json
{
  "name": "Novo Nome",
}
```

**Resposta:** (Status [Code])
```json
{
  "message": "Usuário atualizado com sucesso",
  "user": { /* dados atualizados */ }
}
```

### DELETE /endpoint
[O que faz]

**Resposta:** (Status [Code])
```json
{
  "message": "Usuário deletado com sucesso"
}
```

## Tecnologias Utilizadas

- **Framework** - [O que é e faz]
- **Linguagem** - [O que é e faz]
- **Biblioteca 1** - [O que é e faz]
- **Biblioteca 2** - [O que é e faz]
- **Ferramenta de desenvolvimento** - [O que é e faz]

## Estrutura de Dados

[Detalhes do Body]

```typescript
interface User {
  id: string;           // UUID único gerado automaticamente
  name: string;         // Nome do usuário
}
```

## Armazenamento de Dados

[Como os dados são armazenados]

## Contriuições

Para dúvidas ou contribuições, sinta-se à vontade para abrir uma issue ou pull request.