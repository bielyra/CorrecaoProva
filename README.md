# CorrecaoProva

## Sobre o projeto

Site sobre instrumentos musicais, feito em HTML puro como trabalho da cadeira Desenvolvimento Front-End para Web.

- **Página inicial (`index.html`):** conta qual foi o primeiro instrumento musical registrado na história, a flauta de osso, e apresenta o aulos da Grécia Antiga.
- **Páginas de categoria (`cordas.html`, `sopro.html`, `teclas.html` e `percussao.html`):** cada uma traz a definição da categoria e uma tabela com os 4 instrumentos mais populares dela, com a data de criação e os gêneros musicais onde são mais comuns.

Todas as páginas têm um menu no topo para navegar entre elas.

## Critérios que o professor me deu:

- Site com HTML Puro;
- O tema do site tem que abordar algo interessante e de certa importância;
- Deve ter entre 3 a 5 páginas;
- Deve ser utilizado todos os recursos e conhecimentos adquiridos sobre HTML.

## Especificações

- **Linguagem:** somente HTML, sem CSS e sem JavaScript.
- **Páginas:** 5 (a página inicial e as 4 categorias).
- **Idioma e codificação:** português do Brasil (`lang="pt-BR"`) e UTF-8.
- **Como abrir:** abrir o arquivo `main/index.html` no navegador.

Estrutura de pastas:

```
CorrecaoProva/
├── README.md
├── img/
│   └── banquet_euaion_louvre_g467_n2.png
└── main/
    ├── index.html
    ├── cordas.html
    ├── sopro.html
    ├── teclas.html
    └── percussao.html
```

## Recursos de HTML utilizados

| Tipo | Elementos e atributos | Onde aparecem |
|---|---|---|
| Estrutura do documento | `<!DOCTYPE html>`, `<html lang>`, `<head>`, `<meta charset>`, `<meta name="viewport">`, `<title>`, `<body>` | Todas as páginas |
| Estrutura semântica | `<header>`, `<nav>` com `aria-label`, `<main>`, `<article>`, `<footer>` | Todas as páginas |
| Seções | `<section>` e `<header>` dentro do `<article>` | Página inicial |
| Títulos e parágrafos | `<h1>`, `<p>`, `<hr>` | Todas as páginas |
| Subtítulos | `<h2>`, `<h3>` | Página inicial |
| Texto com significado | `<dfn>` (termo definido), `<cite>` (nome de obra ou fonte) | Todas as páginas |
| Citações e datas | `<q>` (citação curta), `<abbr title>` (abreviação), `<time datetime>` (data) | Página inicial |
| Destaque de texto | `<b>`, `<i>` | Cordas e sopro |
| Links | `<a href>` para as outras páginas (menu) e para as fontes externas; entidade `&lt;` no link "Voltar ao Menu Inicial" | Todas as páginas |
| Imagem | `<figure>`, `<figcaption>`, `<img>` com `src` (caminho relativo `../img/`) e `alt` | Página inicial |
| Tabela | `<table border="1">`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>` | Páginas de categoria |

## Fontes

### Textos

| Página | Fonte |
|---|---|
| `index.html` | [Qual foi o primeiro instrumento musical registrado na história?](https://www.nationalgeographicbrasil.com/historia/2024/09/qual-foi-o-primeiro-instrumento-musical-registrado-na-historia), Redação National Geographic Brasil, 30 de setembro de 2024. A matéria cita a Encyclopedia Britannica e a World History Encyclopedia. |
| `cordas.html` | [Wikipédia – Instrumento de cordas](https://pt.wikipedia.org/wiki/Instrumento_de_cordas) |
| `sopro.html` | [Wikipédia – Instrumento de sopro](https://pt.wikipedia.org/wiki/Instrumento_de_sopro) |
| `teclas.html` | [Wikipédia – Instrumento de teclas](https://pt.wikipedia.org/wiki/Instrumento_de_teclas) |
| `percussao.html` | [Wikipédia – Instrumento de percussão](https://pt.wikipedia.org/wiki/Instrumento_de_percuss%C3%A3o) |

### Tabelas dos instrumentos

- **Os 4 mais populares de cada categoria:** [Centumth – Top 100 Most Popular Musical Instruments](https://www.centumth.com/archive/top-100-most-popular-musical-instruments), publicado em 2 de junho de 2026.
- **Datas de criação e gêneros musicais:** artigos da Wikipédia sobre cada instrumento, citados abaixo de cada tabela.

### Imagem

- **`img/banquet_euaion_louvre_g467_n2.png`:** jovem tocando o aulos, detalhe de uma cena de banquete pintada pelo Pintor de Euaion numa taça grega (c. 460–450 a.C.), hoje no Museu do Louvre. Foto de Jastrow (2008), em domínio público, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Banquet_Euaion_Louvre_G467_n2.jpg).

## Uso de inteligência artificial

Foi utilizado o Claude, assistente de IA da Anthropic, para inserir nas páginas os textos das fontes bibliográficas que eu informei, seguindo os moldes do `index.html`, cuja formatação foi feita por mim.
