# remmember

Um vault pessoal pra lembrar de **sites, apps, IAs, livros e filmes** que você já usou — ou ainda quer usar.

Campo de busca + galeria de cards com logo, tags e o status **"já usei / quero usar"**. Tudo num único arquivo HTML, sem build, com persistência local no navegador.

![remmember](https://img.shields.io/badge/single--file-HTML-FF8A5C)

## Funcionalidades

- 🔎 **Busca** instantânea por nome, nota, tag ou link
- 🏷️ **Filtros** por tipo (Site/App/IA/Livro/Filme/Outro), status e tags
- 🖼️ **Logo automático** de cada ferramenta (unavatar → DuckDuckGo → emoji)
- ✅ **Status "já usei / quero usar"** — o ponto central do app
- ✍️ **Autocomplete de tags** com base nas que você já criou
- 💾 **Persistência local** (localStorage) — seus dados ficam no seu navegador
- ⌨️ Atalhos: `n` adiciona, `/` foca a busca, `Esc` fecha, `⌘/Ctrl+Enter` salva

## Como usar

É um arquivo único. Basta abrir o [`index.html`](index.html) no navegador — dois cliques no arquivo já funciona.

Ou rode um servidor estático local:

```bash
python3 -m http.server 4200
# abra http://localhost:4200
```

> Nota: `file://` e `localhost` usam armazenamentos separados — escolha um e use sempre o mesmo.

## Dados iniciais

Vem com 53 ferramentas de referência (inspirado no ToolVault) pra você começar filtrando e marcando o que já usou. Edite ou remova à vontade — é tudo seu.

## Stack

HTML + CSS + JavaScript puro, sem dependências, sem build.
