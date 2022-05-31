# Dinâmica Git/Github

Essa dinâmica tem como objetivo treinar:

- Branchs
- Merges
- Conflitos

---

# Descrição

A turma será divida em grupos de até no máximo 6 pessoas

## Passo 1

- Um integrante deve criar o repositório no github com o nome `treinando-branchs` `VAZIO` (sem readme, descrição, lincença ou .gitignore)
- Ele deve adicionar todos os integrantes
  - Você encontrará a opção em `settings/collaborators/Add People`
- Todos os integrantes devem confirmar o email

## Passo 2

- Um integrante deve criar um arquivo chamado `index.html` e adicionar o seguinte conteúdo

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Git e Github</title>
  </head>
  <body>
  </body>
</html>
```

- Esse integrante deve subir para o github
- Todos os integrantes devem dar um clone do repositório com esse novo arquivo

## Passo 3

- Cada integrante deve adicionar uma tag `h1` dentro da tag `body`. O conteúdo dentro do `h1` deve ser aleatório entre os integrantes
- Cada integrante deve tentar mandar o conteúdo para o github. Caso ocorra algum problema devem discutir entre os membros para buscar uma solução

## Passo 4

- Cada integrante deve alterar o conteúdo da tag `title` e por um valor aleatório  (não podendo ser o mesmo entre os integrantes)
- Em seguinda, devem subir o conteúdo para o github. Caso ocorra algum problema devem discutir entre os membros para buscar uma solução

## Passo 5

- Cada integrante deve criar um `branch` diferente, por exemplo `feature/new-section`. Cada branch deve ter um nome diferente.
- Em seguida cada um deve criar uma `section` contendo duas `div` e dentro delas um `h2` e um `p` com conteúdo aleatório. Por exemplo

```html
<section>
  <div>
    <h1>Dinâmica Html</h1>
    <p>Conteúdo</p>
  </div>
  <div>
    <h1>Dinâmica Html</h1>
    <p>Conteúdo</p>
  </div>
</section>

```

- Ao finalizar, cada integrante deve criar uma PR e em seguinda por alguém para revisar e dar um merge com a branch principal



