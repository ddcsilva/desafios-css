# Desafio 8: Layout Completo com Grid Areas

Agora é hora de criar um **layout de página completo**! Vamos usar o poder do CSS Grid com **áreas nomeadas** (`grid-template-areas`) para criar uma estrutura de página profissional com header, sidebar, conteúdo principal e footer.

## 🎯 O que são Grid Areas?

Grid Areas permitem nomear regiões do seu grid e posicionar elementos de forma semântica e visual. É como desenhar o layout no próprio CSS!

```css
grid-template-areas:
  "header header"
  "sidebar content"
  "footer footer";
```

## Sua Missão

### 1. Estrutura HTML

Crie uma estrutura de página completa com:

- **Header** (`.header`) - Cabeçalho com logo e navegação
- **Sidebar** (`.sidebar`) - Menu lateral
- **Main Content** (`.main-content`) - Conteúdo principal
- **Footer** (`.footer`) - Rodapé

### 2. Grid Container

Configure o `.page-container` com:

- `display: grid`
- `grid-template-columns: 250px 1fr` - Sidebar fixa e conteúdo flexível
- `grid-template-rows: auto 1fr auto` - Header e footer automáticos, conteúdo cresce
- `min-height: 100vh` - Altura mínima de toda a viewport

### 3. Grid Template Areas

Use `grid-template-areas` para nomear as áreas:

```css
grid-template-areas:
  "topo topo"
  "menu conteudo"
  "rodape rodape";
```

### 4. Posicione os Elementos

Associe cada elemento à sua área:

- `.header { grid-area: topo; }`
- `.sidebar { grid-area: menu; }`
- `.main-content { grid-area: conteudo; }`
- `.footer { grid-area: rodape; }`

### 5. Estilize os Componentes

- **Header:** Use Flexbox para alinhar logo e links horizontalmente
- **Sidebar:** Liste os links verticalmente com espaçamento
- **Footer:** Centralize o texto de copyright
- Use BEM para nomenclatura das classes!

### 6. Responsividade

Adicione uma media query para mobile:

- Mude o grid para uma coluna
- Reorganize as áreas para empilhar verticalmente:

```css
grid-template-areas:
  "topo"
  "menu"
  "conteudo"
  "rodape";
```

---

## 🎨 Conceitos Principais

- **`grid-template-areas`** - Nomeia regiões do grid
- **`grid-area`** - Posiciona elementos nas áreas nomeadas
- **Grid + Flexbox** - Combine as duas ferramentas
- **Layout Completo** - Header, Sidebar, Content, Footer
- **Responsividade** - Reorganize o layout em telas pequenas

---

## 💡 Vantagens do Grid Areas

✅ **Visual e semântico** - O código CSS mostra o layout
✅ **Fácil de reorganizar** - Mude apenas o `grid-template-areas`
✅ **Responsivo** - Adapte o layout com media queries
✅ **Profissional** - Padrão usado em aplicações reais

---

## 🚀 Dica Extra

Grid Areas é perfeito para dashboards, admin panels e aplicações web. É a forma mais moderna e elegante de criar layouts complexos!
