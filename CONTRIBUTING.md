# Contribuindo com o projeto

## Preparando o ambiente

_TODO_

## Reportando bugs

_TODO_

## Sugerindo melhorias

_TODO_

## Board de tarefas

[Github issues][issues]

## Fluxo de desenvolvimento

- Pegar da tarefa mais velha para a mais nova
- Abrir pull request
- Code review
- Done!

## Fluxo do Git

Seguimos o [GitFlow][gitflow-url], mas usando Pull Requests para code review.

# Styleguides

## Mensagens de commit styleguide

- Usar modo imperativo (**"Adiciona feature"** não "Adicionando feature" ou "Adicionada feature")
- Primeira linha deve ter no máximo 72 caracteres
- Considere descrever com detalhes no corpo do commit
- _Insira o código da issue do jira no início da mensagem ("CBKAP-67 Adiciona feature")_
- Considere usar um emoji no início da mensagem de commit
  * :art: `:art:` quando melhorar a estrutura/formato do código
  * :racehorse: `:racehorse:` quando melhorar a performance
  * :non-potable_water: `:non-potable_water:` memory leaks
  * :memo: `:memo:` quando escrever alguma documentação
  * :bug: `:bug:` quando corrigir um bug
  * :fire: `:fire:` quando remover códigos ou arquivos
  * :green_heart: `:green_heart:` quando corrigir uma build no CI
  * :white_check_mark: `:white_check_mark:` quando adicionar testes
  * :lock: `:lock:` quando melhorar a segurança
  * :arrow_up: `:arrow_up:` quando der upgrade em dependências
  * :arrow_down: `:arrow_down:` quando der downgrade em dependências
  * :shirt: `:shirt:` quando remover problemas com linter
  * :poop: `:poop:` merda forte!
  * mais? [lista de emojis][emoji-url]

**Exemplo**

```bash
git commit -m ":memo: Adiciona instruções de contribuição
>
> Foi criado o arquivo CONTRIBUTING.md com as instruções de
> como fazer um bom commit"
```

## Pull Requests styleguide

- Siga o padrão das mensagens de commit
- Inclua GIFs animados sempre que possível
- Verifique se todos os testes estão passando (CI)
- Siga os styleguides de código
- Documente a nova feature de acordo com o styleguide
- _Só pode fazer merge se tiver n approved_
- _Considere editar o título colocando um emoji no início:_
  * :construction_worker: `:construction_worker:` quando ainda está com trabalho em progresso
  * :wrench: `:wrench:` quando precisar de mudanças
  * :warning: `:warning:` quando precisar de teste manual


## Linguagem styleguide

_TODO_

## Testes styleguide

_TODO_

## Documentação styleguide

_TODO_

[emoji-url]: http://www.emoji-cheat-sheet.com/
[gitflow-url]: http://nvie.com/posts/a-successful-git-branching-model/
[issues]: https://github.com/mguilarducci/animalandia/issues?q=is%3Aissue+is%3Aopen+sort%3Acreated-asc
