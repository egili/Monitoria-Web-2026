# 🎨 CSS3 Cheat Sheet - Monitoria Web

## 📦 Box Model (Modelo de Caixa)
- **Content**: O conteúdo real (texto, imagem).
- **Padding**: Espaço interno (entre o conteúdo e a borda).
- **Border**: A linha que envolve o padding e o conteúdo.
- **Margin**: Espaço externo (afasta o elemento de outros elementos).

`box-sizing: border-box;` $\rightarrow$ *Dica: Use isso globalmente para que o padding não aumente o tamanho total do elemento.*

## 📍 Posicionamento
- `static`: Padrão do navegador.
- `relative`: Posicionado relativo a si mesmo.
- `absolute`: Posicionado relativo ao ancestral `relative` mais próximo.
- `fixed`: Fica preso na tela, mesmo ao rolar.
- `sticky`: Alterna entre relative e fixed conforme o scroll.

## ⚡ Flexbox (Layout Unidimensional)
**No Container (Pai):**
- `display: flex;` $\rightarrow$ Ativa o flexbox.
- `flex-direction: row | column;` $\rightarrow$ Direção dos itens.
- `justify-content: center | flex-start | flex-end | space-between | space-around;` $\rightarrow$ Alinhamento no eixo principal.
- `align-items: center | flex-start | flex-end | stretch;` $\rightarrow$ Alinhamento no eixo transversal.
- `gap: 10px;` $\rightarrow$ Espaço entre os itens.

**Nos Itens (Filhos):**
- `flex-grow: 1;` $\rightarrow$ Faz o item crescer para ocupar o espaço disponível.
- `align-self: center;` $\rightarrow$ Alinha apenas aquele item específico.

## 📐 CSS Grid (Layout Bidimensional)
- `display: grid;`
- `grid-template-columns: repeat(3, 1fr);` $\rightarrow$ Cria 3 colunas iguais.
- `grid-template-rows: auto 100px;` $\rightarrow$ Define altura das linhas.
- `grid-column: 1 / 3;` $\rightarrow$ Faz o item ocupar da coluna 1 até a 3.

## 📱 Responsividade (Media Queries)
```css
/* Quando a tela for menor que 768px (Tablets/Celulares) */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```
