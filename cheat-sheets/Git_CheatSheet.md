# 🛠️ Git & GitHub Cheat Sheet - Monitoria Web

## 🚀 Iniciando
- `git init`: Inicia um repositório local.
- `git clone <url>`: Copia um repositório remoto para sua máquina.

## 🔄 Ciclo de Trabalho (O básico do dia a dia)
1. `git status`: Verifica quais arquivos foram alterados.
2. `git add .`: Adiciona todas as alterações para o "estágio" (staging area).
   - *Dica: use `git add nome-do-arquivo` para adicionar apenas um.*
3. `git commit -m "mensagem clara e curta"`: Salva a versão localmente.
4. `git push origin <branch>`: Envia as alterações para o GitHub.

## 🌿 Branches (Ramos)
- `git branch`: Lista as branches existentes.
- `git checkout -b <nome-da-branch>`: Cria uma nova branch e já muda para ela.
- `git checkout <nome-da-branch>`: Muda para uma branch existente.
- `git merge <nome-da-branch>`: Une as alterações da branch escolhida na branch atual.

## ⚠️ Socorro! (Comandos de Recuperação)
- `git checkout -- <arquivo>`: Descarta alterações não commitadas em um arquivo.
- `git reset --hard HEAD`: Volta o código exatamente para o estado do último commit (CUIDADO: apaga tudo que não foi commitado).
- `git pull origin <branch>`: Atualiza seu código local com o que está no GitHub.
