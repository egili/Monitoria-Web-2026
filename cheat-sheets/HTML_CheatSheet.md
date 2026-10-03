# 🚀 HTML5 Cheat Sheet - Monitoria Web

## 🏗️ Estrutura Básica
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
</head>
<body>
    <!-- Conteúdo aqui -->
</body>
</html>
```

## 🏷️ Tags Semânticas (Essenciais para SEO e Acessibilidade)
| Tag | Descrição | Quando usar? |
| :--- | :--- | :--- |
| `<header>` | Cabeçalho | Topo da página ou de uma seção. |
| `<nav>` | Navegação | Menus de links principais. |
| `<main>` | Conteúdo Principal | O conteúdo único e central daquela página. |
| `<article>` | Artigo | Conteúdo independente (ex: post de blog). |
| `<section>` | Seção | Agrupamento temático de conteúdo. |
| `<aside>` | Lateral | Conteúdo relacionado, mas não principal (sidebar). |
| `<footer>` | Rodapé | Informações de copyright, contato, links finais. |

## ✍️ Textos e Formatação
- `<h1>` a `<h6>`: Títulos (h1 é o mais importante, use apenas UM por página).
- `<p>`: Parágrafo.
- `<a>`: Link (`href="url"`).
- `<ul>` / `<li>`: Lista não ordenada (pontinhos).
- `<ol>` / `<li>`: Lista ordenada (números).
- `<strong>`: Negrito (importância semântica).
- `<em>`: Itálico (ênfase).
- `<span>`: Elemento genérico inline (para estilizar partes de um texto).

## 🖼️ Mídia e Formulários
- `<img src="caminho" alt="descrição">`: Imagem (Sempre use `alt`!).
- `<form action="url" method="POST">`: Formulário.
- `<label for="id">`: Etiqueta para inputs.
- `<input type="text|email|password|number|date|checkbox|radio">`: Campo de entrada.
- `<textarea>`: Texto longo.
- `<select>` / `<option>`: Menu suspenso.
- `<button type="submit">`: Botão de envio.
