# Como contribuir

Este guia vale para todos os repositórios da organização que não tenham o seu próprio.

## Trabalho começa em uma issue

Toda mudança parte de uma issue. Se não existe uma, abra antes de codar.

## Branches

Crie a branch a partir de `main`, com um prefixo que diga o tipo: `feat/`, `fix/`, `docs/` ou `chore/`, seguido de um nome curto.

## Commits

Use mensagens no formato `tipo: descrição curta` (`feat:`, `fix:`, `docs:`, `chore:`), no imperativo e com a referência da issue quando houver. Um commit, uma mudança.

## Pull requests

- Preencha o modelo da pull request.
- Rode os testes antes de pedir revisão.
- Mantenha a mudança pequena e focada em uma issue.
- Ninguém dá push direto no `main`: tudo passa por pull request.

## Segredos

Nunca versione senhas, chaves, tokens, arquivos `.env`, certificados nem dumps de banco. Use arquivos de exemplo (`.env.example`) sem valores reais. Se algo vazou, avise antes de apagar o histórico, para trocarmos a credencial.
