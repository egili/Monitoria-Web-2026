# ❓ Perguntas Frequentes (FAQ) - Monitoria Web

Este documento reúne as dúvidas mais comuns dos alunos para que você possa encontrar a resposta rapidamente.

## 🌐 HTML & CSS

### 1. Qual a diferença entre ID (`#`) e Classe (`.`)?
- **Classe (`.`)**: Pode ser usada em múltiplos elementos. Use para estilos que se repetem (ex: `.btn-azul`, `.texto-centralizado`).
- **ID (`#`)**: Deve ser único na página inteira. Use para elementos únicos ou para âncoras de links (ex: `#topo`, `#contato`).

### 2. Por que meu elemento não centraliza com `text-align: center`?
O `text-align: center` só centraliza elementos **inline** ou **inline-block** (como texto, imagens, spans). Se você quer centralizar uma `div` (elemento block), use:
- `margin: 0 auto;` (se a div tiver uma largura definida).
- Ou coloque a div dentro de um container com `display: flex; justify-content: center;`.

### 3. O que é o `z-index` e por que ele não funciona no meu código?
O `z-index` controla a "profundidade" (quem fica na frente de quem). Para que ele funcione, o elemento **precisa** ter uma propriedade `position` definida (como `relative`, `absolute` ou `fixed`). Se estiver como `static` (padrão), o `z-index` será ignorado.

### 4. Qual a diferença entre `px`, `em`, `rem` e `%`?
- **`px` (Pixel)**: Tamanho fixo. Não muda independente da tela.
- **`%` (Porcentagem)**: Relativo ao tamanho do elemento pai.
- **`em`**: Relativo ao tamanho da fonte do próprio elemento ou do pai.
- **`rem` (Root em)**: Relativo ao tamanho da fonte da raiz (`html`). É o mais recomendado para acessibilidade e responsividade.

---

## ⚡ JAVASCRIPT

### 5. Qual a diferença entre `var`, `let` e `const`?
- **`var`**: Forma antiga. Tem escopo global ou de função (evite usar).
- **`let`**: Forma moderna. Tem escopo de bloco `{ }`. Use para valores que vão mudar.
- **`const`**: Para valores que **nunca** mudam (constantes). Use por padrão para evitar bugs.

### 6. O que é o DOM?
DOM (Document Object Model) é a representação do seu HTML como uma árvore de objetos que o JavaScript consegue acessar. Quando você faz `document.querySelector('.classe')`, você está acessando o DOM para alterar a página em tempo real.

---

## 🛠️ GIT & GITHUB

### 7. Fiz um commit, mas esqueci de um arquivo. E agora?
Se você ainda não deu `push`, pode usar:
`git add arquivo-esquecido.html`
`git commit --amend --no-edit`
Isso adiciona o arquivo ao último commit sem criar um novo.

### 8. O que fazer quando dá "Merge Conflict"?
Isso acontece quando duas pessoas alteram a mesma linha do mesmo arquivo.
1. Abra o arquivo com conflito no VS Code.
2. Você verá marcações como `<<<<<<< HEAD` e `>>>>>>> branch`.
3. Escolha qual versão manter (ou combine as duas).
4. Salve o arquivo, faça `git add .` e `git commit`.
