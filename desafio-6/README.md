# Desafio 6: O Grid Mágico e Responsivo

Vamos substituir a sua linha do `grid-template-columns` por uma mais inteligente:

```css
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
```

Sei que parece complicado, mas vamos quebrar:

- **`repeat(...)`** ➡️ Pede ao navegador para repetir um padrão de coluna.

- **`auto-fit`** ➡️ Diz para ele encaixar quantas colunas couberem na tela.

- **`minmax(300px, 1fr)`** ➡️ É o tamanho de cada coluna. Ela terá no mínimo `300px` (a largura do nosso card), mas poderá crescer (`1fr`) para preencher o espaço.

## Sua Missão

1. **Substitua** o seu `grid-template-columns: 1fr 1fr;` por essa nova linha no `.grid-container` e veja o que acontece quando você redimensiona a janela do seu navegador.

2. **Adicione uma propriedade** ao `.grid-container` para que ele se expanda e ocupe **100% da largura** da página. Como um toque final, adicione também um `padding` ao `body` para que os cards não colem nas bordas da tela.

## 🤔 Desafio

**Qual propriedade você usaria para fazer o `.grid-container` ocupar toda a largura?**

---

**💡 Dica:** Pense em como você define a largura de um elemento para ocupar todo o espaço disponível!
