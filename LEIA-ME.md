# Site de Eduardo Prachedes

Site estático em Jekyll, publicado pelo GitHub Pages. Não precisa instalar nada.

## Publicar um texto

Cada texto tem dois arquivos, um em cada idioma:

```
_posts/pt/2026-12-01-incomunicabilidade.md
_posts/en/2026-12-01-incommunicability.md
```

- O nome do arquivo é `AAAA-MM-DD-titulo-sem-acentos.md`. A data vira a data de publicação e o resto vira o endereço (`/textos/incomunicabilidade/`).
- No topo de cada arquivo:

```
---
title: Incomunicabilidade
ref: incomunicabilidade
subtitle: (opcional) um subtítulo
description: (opcional) resumo que aparece no Início
---

Aqui começa o texto...
```

- **`ref` liga as duas versões.** Use o mesmo `ref` no arquivo em português e no em inglês. Se os dois arquivos tiverem exatamente o mesmo nome, o `ref` pode ser omitido.
- Se só existir uma versão, o texto aparece só naquele idioma e o botão de troca leva ao Início do outro idioma.

Pelo site do GitHub: abra a pasta `_posts/pt`, clique em **Add file → Create new file** (ou arraste o .md), salve com **Commit changes**. Em cerca de um minuto o site é atualizado.

## Editar o "Sobre"

`sobre/index.md` (português) e `en/about/index.md` (inglês).

## Trocar a foto

Substitua `assets/img/eduardo.jpg` por outra imagem quadrada com o mesmo nome (ela aparece na página Sobre).
