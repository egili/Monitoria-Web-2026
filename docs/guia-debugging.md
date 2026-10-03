# 🛠️ Guia de Apoio Prático e Debugging

Programar envolve errar. A diferença entre um desenvolvedor iniciante e um experiente é a capacidade de encontrar e corrigir o erro rapidamente.

## 🔍 1. O Fluxo do Debugging (Como resolver problemas)
Quando algo não funciona, não tente "adivinhar" a solução. Siga este processo:

1. **Isole o problema:** O erro é no HTML (estrutura), no CSS (visual) ou no JS (lógica)?
2. **Leia a mensagem de erro:** Abra o Console do Navegador (F12). Erros em vermelho geralmente dizem a linha exata e o motivo do problema.
3. **Crie a "Menor Versão Possível":** Se seu site tem 500 linhas e não funciona, tente reproduzir o erro em um arquivo novo com apenas 10 linhas.
4. **Explique para o "Patinho de Borracha":** Explique seu código em voz alta para alguém (ou para um objeto). Muitas vezes, ao explicar, você percebe o erro.

---

## 💻 2. Dicas Rápidas de Correção

### ❌ Meu CSS não está sendo aplicado!
- **Verifique o caminho:** O caminho no `<link href="...">` está correto? (Cuidado com maiúsculas e minúsculas).
- **Verifique o seletor:** Você escreveu `.classe` (com ponto) ou `#id` (com hashtag)?
- **Prioridade (Especificidade):** Existe alguma regra mais forte sobrescrevendo a sua? Use o Inspecionar do navegador para ver qual regra está ganhando.
- **Cache:** Tente dar um `Ctrl + F5` para forçar o navegador a recarregar o CSS.

### ❌ Meu JavaScript não faz nada!
- **Cheque o Console:** Existem erros vermelhos? Se sim, clique no link da direita para ir à linha do erro.
- **Verifique a importação:** A tag `<script src="...">` está no final do `body`? Se estiver no `head`, o JS pode tentar rodar antes do HTML existir.
- **Use o `console.log()`:** Coloque `console.log("Chegou aqui!")` em várias partes do código para ver até onde a execução está indo.
- **Sintaxe:** Esqueceu de fechar alguma chave `}` ou parêntese `)`?

---

## 📚 3. Onde buscar ajuda de forma eficiente?

Ao perguntar para o monitor ou em fóruns, evite dizer apenas "não funciona". Use este modelo:

**Modelo de Pergunta Ideal:**
1. **O que eu queria fazer:** "Eu queria que o botão ficasse vermelho ao passar o mouse."
2. **O que aconteceu:** "O botão continua branco e aparece um erro 'Uncaught TypeError' no console."
3. **O que eu já tentei:** "Tentei usar `:hover` e mudei a cor no Inspecionar, mas no arquivo não funciona."
4. **Código:** (Envie o link do GitHub ou o trecho do código relevante).

### Sites Recomendados:
- **MDN Web Docs:** A documentação oficial e mais completa.
- **Stack Overflow:** Para erros específicos de código.
- **W3Schools:** Para exemplos rápidos e simples.
