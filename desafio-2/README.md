# Desafio 2: O Botão Interativo

**Sua Missão:** Usando o mesmo código, adicione os seguintes estilos ao seu botão.

## 1. Estilo Padrão (o estado normal)

- Remova a borda (`border`).
- Adicione um `padding` de `15px` na vertical e `30px` na horizontal.
- Defina uma cor de fundo (`background-color`) e uma cor para o texto (`color`).
- Adicione uma leve sombra com `box-shadow`. Um bom valor para começar é `0px 4px 8px rgba(0, 0, 0, 0.2)`.

## 2. Estado de Hover

- Faça a cor de fundo ficar um pouco mais clara ou escura quando o mouse passar por cima.

## 3. Estado Ativo (Clique)

- Quando o botão for clicado (`:active`), quero que ele pareça estar sendo "pressionado". Uma boa forma de fazer isso é mover o botão um pouco para baixo e diminuir a sombra.

**Dica:** você pode usar a propriedade `transform` que já conhecemos!

## 4. Estado de Foco

- Para garantir que usuários que navegam pelo teclado saibam onde estão, adicione um `outline` (um contorno) visível quando o botão estiver em foco.

## 5. Transições Suaves

- Adicione a propriedade `transition` ao seu seletor `.button` (o estado padrão) para que as mudanças nas propriedades `background-color`, `box-shadow` e `transform` aconteçam de forma suave. Um bom tempo para começar é `0.2s`.
