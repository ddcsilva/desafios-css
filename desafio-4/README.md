# Desafio 4: O Layout Adaptável

**Sua Missão:** Fazer com que os botões fiquem em uma coluna em telas pequenas.

## Passo 1: Permitir quebra de linha

Primeiro, precisamos "permitir" que os itens possam quebrar a linha. Adicione a propriedade `flex-wrap: wrap;` à sua regra `.container`.

## Passo 2: Criar a Media Query

Depois, adicione o bloco de código abaixo no final do seu arquivo CSS. Ele será o nosso "if":

```css
@media (max-width: 600px) {
  /* Estilos aqui dentro só valem para telas com 600px de largura ou menos */
}
```

## O Desafio Principal

Dentro da media query, **qual propriedade do `.container` você mudaria** para que os botões se organizem em uma coluna em vez de uma linha?

---

**Dica:** Pense em como você definiu inicialmente a direção dos elementos no Flexbox! 🤔
