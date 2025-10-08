# Desafio 5: Cards e CSS Grid

## Sua Missão 1: Construir o Card

Primeiro, aqui está o HTML para um único card. Você pode colocá-lo dentro do seu `<body>` e remover os botões antigos.

```html
<div class="card">
  <img src="https://via.placeholder.com/300x200" alt="Imagem de exemplo">
  <div class="card-content">
    <h3>Título do Card</h3>
    <p>Este é um parágrafo de exemplo para preencher o conteúdo do nosso card.</p>
  </div>
</div>
```

Agora, o desafio de CSS: **estilize este card para que ele se pareça com um card**.

### Para a div `.card`

- Dê a ela uma largura fixa (ex: `width: 300px;`).
- Adicione uma sombra (`box-shadow`) e um `border-radius` para arredondar os cantos.
- Adicione um `overflow: hidden;` para garantir que a imagem não "vaze" para fora dos cantos arredondados.

### Para a imagem (`.card img`)

- Faça com que ela ocupe 100% da largura do card.

### Para o conteúdo (`.card-content`)

- Adicione um `padding` para que o texto não fique colado nas bordas.

---

## Sua Missão 2: Organizar Cards com CSS Grid

O CSS Grid nos permite organizar o conteúdo em linhas e colunas, como uma planilha.

### No HTML

Copie e cole a div do seu card mais 3 vezes, para termos um total de **4 cards**. Depois, envolva todos eles em um contêiner, assim:

```html
<div class="grid-container">
  <div class="card">...</div>
  <div class="card">...</div>
  <div class="card">...</div>
  <div class="card">...</div>
</div>
```

### No CSS

Vamos aplicar o Grid ao `.grid-container`:

- Comece com `display: grid;`.
- Para criar duas colunas de tamanho igual, use `grid-template-columns: 1fr 1fr;`. (A unidade `fr` representa uma fração do espaço disponível).
- Adicione um `gap` para dar espaço entre os cards, como fizemos com o Flexbox.
