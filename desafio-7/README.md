# Desafio 7: Organização Profissional com BEM

Para finalizar, vamos falar de algo que eleva um desenvolvedor: **arquitetura e organização**. Quando um projeto cresce, os nomes das classes CSS podem virar uma bagunça. Para evitar isso, existem metodologias de nomenclatura. A mais famosa é a **BEM (Block, Element, Modifier)**.

## 🎯 Entendendo BEM

A ideia é simples:

- **Block:** O componente independente. Ex: `.card`

- **Element:** Uma parte que só existe dentro do bloco. A sintaxe é `bloco__elemento`. Ex: `.card__image`, `.card__content`

- **Modifier:** Uma variação de estilo do bloco ou elemento. A sintaxe é `bloco--modificador`. Ex: `.card--highlighted`, `.button--disabled`

## Sua Missão

### 1. Refatore as classes para BEM

Refatore seu HTML e CSS para usar a nomenclatura BEM no componente do card:

- `.card-content` → `.card__content`
- `.card img` → `.card__image`
- Adicione classes `.card__title` e `.card__text` aos elementos internos

### 2. Adicione um Modificador

Crie um modificador `.card--highlighted` que:

- Adicione uma borda colorida
- Tenha uma sombra mais forte
- Destaque visualmente um dos cards

### 3. Melhore a Interatividade

Adicione efeitos de `:hover` nos cards:

- Use `transform: translateY(-5px)` para criar um efeito de elevação
- Aumente a sombra no hover
- Adicione `transition` para suavizar as animações

### 4. Controle as Imagens

Use `object-fit` para que todas as imagens tenham o mesmo tamanho sem distorcer:

- Defina uma altura fixa (ex: `height: 300px`)
- Use `object-fit: cover` ou `object-fit: scale-down`
- Centralize com `object-position: center`

### 5. Adicione um Título

Crie um título principal para o projeto usando `<h1 class="title">` e estilize-o para ficar bonito e destacado.

### 6. Centralize o Layout

- Adicione `max-width: 1200px` no `.grid-container`
- Use `margin: 0 auto` para centralizar
- Adicione um `background-color` no body para melhorar o visual

---

## 💡 Dica Final

Esse é um exercício de **organização e boas práticas**. O importante não é só fazer funcionar, mas fazer de forma profissional e escalável! 🚀
