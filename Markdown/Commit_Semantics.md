# Mensagens semânticas de commits
> **Por:** Josh Buchea _https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716.js_

Veja como uma pequena mudança em seu estilo de mensagem de commit pode torná-lo um programador melhor.

Formato: `<tipo>(<contexto>): <mensagem>`

`<contexto>` é opcional

## Exemplo

```
feat: Adicionando a função...
^--^  ^------------^
|     |
|     +-> Resumo no tempo presente.
|
+-------> Tipos: chore, docs, feat, fix, refactor, style, or test.
```
```
fix: Corrigindo o erro de...
^--^  ^------------^
|     |
|     +-> Resumo no tempo presente.
|
+-------> Tipos: chore, docs, feat, fix, refactor, style, or test.
```

Descrição dos tipos:

Tipo|Descrição
:----:|---------
`feat`|Nova funcionalidade que ainda não existia no sistema, solicitada pelo usuário. Não é um novo recurso para script de compilação
`fix`|Correção de bug apontado pelo usuário ou pelo analista. Não é uma correção para um script de compilação
`docs`|Mudanças na documentação
`style`|Formatação, mudança visual de componente, ponto e vírgula faltando etc. Sem alteração do código de produção
`refactor`|Refatorando o código de produção, atualizando funcionalidade já existente no sistema mas que não apresenta problemas. Exemplo: renomeando uma variável, diminuindo estruturas condicionais, alterar quantidade de parâmetros e etc.
`test`|Adicionando testes ausentes, testes de refatoração. Sem alteração no código de produção
`chore`|Atualização de tarefas, configurações de ambiente e etc. Sem alteração do código de produção

Referências:

- _https://www.conventionalcommits.org/_
- _https://seesparkbox.com/foundry/semantic_commit_messages_
- _http://karma-runner.github.io/1.0/dev/git-commit-msg.html_
- _https://chris.beams.io/posts/git-commit/_