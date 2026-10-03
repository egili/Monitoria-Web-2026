# 💻 Guia de Configuração do Ambiente de Desenvolvimento

Este guia ajudará você a configurar sua máquina para programar para a Web de forma eficiente.

## 🛠️ 1. Editor de Código: Visual Studio Code (VS Code)
O VS Code é o editor mais utilizado no mercado por ser leve e extensível.

- **Download:** [code.visualstudio.com](https://code.visualstudio.com/)
- **Instalação:** Siga o instalador padrão para seu sistema operacional (Windows, macOS ou Linux).

### 🔌 Extensões Recomendadas (Essenciais)
Para instalar, clique no ícone de "Quadrados" no menu lateral esquerdo do VS Code e pesquise por:

1. **Live Server**: Abre um servidor local que atualiza a página automaticamente sempre que você salva o arquivo. (Fundamental para HTML/CSS).
2. **Prettier - Code formatter**: Organiza seu código automaticamente (recuo, aspas, ponto e vírgula), mantendo-o limpo e profissional.
3. **Auto Close Tag**: Fecha automaticamente a tag HTML quando você abre uma.
4. **Auto Rename Tag**: Renomeia a tag de fechamento automaticamente quando você altera a tag de abertura.
5. **ESLint**: Ajuda a encontrar erros de sintaxe e bugs no seu JavaScript enquanto você digita.
6. **Material Icon Theme**: Adiciona ícones bonitos aos arquivos, facilitando a identificação de `.html`, `.css` e `.js`.

---

## 🌐 2. Navegador para Desenvolvimento
Embora todos funcionem, o **Google Chrome** ou **Firefox Developer Edition** são os mais indicados devido às suas ferramentas de desenvolvedor (DevTools).

### 🔍 Como usar o "Inspecionar" (F12)
A ferramenta mais importante para um dev web é o **Inspect**:
1. Abra seu site no navegador.
2. Clique com o botão direito em qualquer elemento $\rightarrow$ **Inspecionar**.
3. **Elements Tab**: Permite alterar o HTML e o CSS em tempo real para testar mudanças sem precisar recarregar a página.
4. **Console Tab**: Onde você verá os erros do seu JavaScript e onde usará o `console.log()`.

---

## 🌿 3. Controle de Versão: Git & GitHub
O Git salva o histórico do seu código, e o GitHub hospeda esse histórico na nuvem.

### 📥 Instalação do Git
- **Windows**: [git-scm.com](https://git-scm.com/)
- **Linux (Ubuntu/Debian)**: `sudo apt install git`
- **macOS**: `brew install git`

### ⚙️ Configuração Inicial (Importante)
Abra o seu terminal (ou o terminal do VS Code) e execute:
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

---

## 📝 Resumo do Fluxo de Trabalho
1. Cria a pasta do projeto $\rightarrow$ Abre no VS Code.
2. Cria os arquivos `index.html`, `style.css` e `script.js`.
3. Clica com o botão direito no `index.html` $\rightarrow$ **Open with Live Server**.
4. Codifica $\rightarrow$ Salva (`Ctrl + S`) $\rightarrow$ Vê o resultado no navegador.
5. Finalizou a tarefa? $\rightarrow$ `git add .` $\rightarrow$ `git commit -m "..."` $\rightarrow$ `git push`.
