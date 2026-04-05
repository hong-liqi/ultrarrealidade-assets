# ultrarrealidade-assets

Repositório público de assets para os dossiês HTML dos protagonistas.

## Objetivo

Este repositório existe para hospedar imagens públicas usadas pelos arquivos HTML gerados no projeto principal `Ultrarrealidade`, que permanece separado e pode continuar privado.

## Estrutura

- `docs/`: raiz publicada pelo GitHub Pages
- `docs/assets/`: imagens acessíveis por URL

## Fluxo recomendado

1. Manter o projeto principal em `Ultrarrealidade/`.
2. Copiar para este repositório apenas as imagens que devem ser públicas.
3. Fazer `commit` e `push` neste repositório quando houver novas imagens ou atualizações.
4. Usar no HTML URLs do GitHub Pages apontando para `docs/assets/...`.

## URL esperada

Se o repositório for publicado no GitHub Pages com fonte em `main` + `/docs`, as imagens seguirão o padrão:

`https://SEU-USUARIO.github.io/ultrarrealidade-assets/assets/...`

Exemplo:

`https://SEU-USUARIO.github.io/ultrarrealidade-assets/assets/drago/personagens/vaelor.png`

## Organização sugerida

Dentro de `docs/assets/`, separar por linha narrativa e tipo:

- `docs/assets/drago/personagens/`
- `docs/assets/drago/cenarios/`
- `docs/assets/lunor/personagens/`
- `docs/assets/lunor/navios/`
- `docs/assets/tigre/personagens/`
- `docs/assets/tigre/tribos/`

## Observações

- O HTML pode continuar sendo gerado no projeto principal.
- As imagens aqui hospedadas serão públicas.
- Não é necessário duplicar manualmente tudo; o ideal é copiar apenas o que o dossiê usar.
