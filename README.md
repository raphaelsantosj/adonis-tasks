# Adonis Tasks

Esse aplicativo foi feito usando este [tutorial](https://scotch.io/tutorials/building-a-web-app-with-adonisjs)

## Configuração

Comece clonando o repositório com o seguinte comando.

```bash
git clone https://github.com/raphaelsantosj/adonis-tasks.git
```

Os arquivos ( markup files ) são referenciados como submodulos, então certifique-se de clona-los também.

```bash
git submodule init 
git submodule update
```

Em seguida, instale as dependências do npm.

```bash
npm install
```

Depois disso renomeie o  `.env.example` como `.env` e faça as mudaças necessárias para a conexão com o banco de dados.

E rode o comando.

```bash
adonis migration:run
```
