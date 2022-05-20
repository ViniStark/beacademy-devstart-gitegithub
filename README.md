
# Comandos Git

Listagem de alguns dos principais comandos git e explicação do que fazem. 

Projeto desenvolvido como atividade do programa DevStart da escola BeAcademy.

### Comandos

- **git config**

Comando que te identifica como usuário, vinculando a seu nome e E-mail aos seus commits.

```bash
  $ git config –global user.name “nome”
  $ git config –global user.email “email”
```

- **git init**

Cria um novo projeto com um repositório vazio.

```bash
  $ git init "nome do repositório"
```

- **git status**

Mostra em qual branch você se encontra, se existem commits e se existem arquivos aguardando commit.

```bash
  $ git status
```

- **git add**

Adiciona arquivos ao repositório, possibilitando fazer commits com eles. Na forma abaixo, adiciona apenas um arquivo específico.

```bash
  $ git add "nome do arquivo"
```

Já na forma abaixo, todos os arquivos alterados são adicionados ao repositório para poderem entrar em um commit.

```bash
  $ git add .
```

- **git commit**

Realiza o commit dos arquivos prontos acompanhado de uma breve descrição do commit.

```bash
  $ git commit -m “descrição”
```
- **git log**

Mostra o histórico de commits e informações associadas a eles.

```bash
  $ git log
```

- **git branch**

Na sua forma mais simples, lista as branchs e sinaliza em qual delas você se encontra:

```bash
  $ git branch
```

Também é possível criar uma branch:

```bash
  $ git branch "nome da branch"
```

Deletar uma branch:

```bash
  $ git branch -d "nome da branch"
```

Ir para uma branch diferente da atual: 

```bash
  $ git checkout "nome da branch destino"
```

Unir a branch atual com uma outra branch: 

```bash
  $ git merge "nome da branch que você deseja trazer"
```






## Autor

- [@ViniStark](https://www.github.com/vinistark)

