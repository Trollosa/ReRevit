# ReRevit — Site

Site institucional da **ReRevit [Soluções para Engenharia]**: projetos elétricos e SPDA, modelos e famílias Revit, plugins via Revit API, sistemas e renders.

Site estático (HTML + CSS + JS puro, sem build). Para visualizar, abra `index.html` no navegador.

## Estrutura

```
index.html              página única (estilos e scripts embutidos)
assets/
  logo-r.png            marca "R" com fundo transparente
  render-casa01.jpg     render usado no topo e no comparador
  wire-casa01.png       wireframe gerado a partir do render (lado clay)
  prancha-casa01.jpg    prancha A1 da Casa 01
  portfolio/            imagens e vídeos da galeria
```

## Onde editar

- **Contatos** (e-mail e WhatsApp): objeto `CONTACT` no início do `<script>` em `index.html`.
- **Galeria de portfólio**: lista `PORTFOLIO` no mesmo script — uma linha por item
  (`src`, `cat`, `title`, opcional `size: 'wide' | 'big'` e `also: 'interior'`).
  Categorias: `exterior`, `interior`, `wire`, `cenografia`, `video`, `prancha`.

## Publicação

Por ser estático, a pasta pode ser publicada diretamente em GitHub Pages, Netlify ou qualquer hospedagem.
