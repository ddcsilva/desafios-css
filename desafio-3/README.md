# Desafio 3: Orquestração com Flexbox

Até agora, trabalhamos com um único elemento. Mas a maior parte do CSS é sobre como os elementos se relacionam e se arranjam em grupo. O método `position: absolute` que usamos é ótimo para posicionar um item isolado, mas não para criar layouts.

Para isso, vamos usar o **Flexbox**, a ferramenta mais fundamental do CSS moderno para alinhar elementos em uma dimensão (uma linha ou uma coluna).

## Sua Missão

1. No seu `index.html`, crie mais dois botões. Agora você terá **três no total**.

2. Remova todo o código de posicionamento do seu `.container` (as propriedades `position`, `top`, `left` e `transform`). Queremos que o container volte ao fluxo normal da página.

3. **O Desafio Principal:** Usando Flexbox no `.container`, faça com que os três botões fiquem alinhados lado a lado, perfeitamente centralizados na tela (tanto vertical quanto horizontalmente).

## Dicas

- A mágica começa com `display: flex;` no contêiner. Depois, você precisará de propriedades para alinhar e justificar o conteúdo.

- Tente adicionar `gap: 16px;` à sua regra do `.container` e veja o que acontece.
