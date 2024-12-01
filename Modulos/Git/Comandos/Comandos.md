# 📋 Resumo de Comandos Git

## 🌱 Inicialização e Configuração
- `git init`: Cria um novo repositório Git.  
- `git config --global user.name "Seu Nome"`: Define o nome do usuário globalmente.  
- `git config --global user.email "email@example.com"`: Define o e-mail do usuário globalmente.  
- `git config --list`: Lista todas as configurações atuais.  

---

## 📁 Controle de Versão Local
- `git add <arquivo>`: Adiciona um arquivo ao stage.  
- `git add .`: Adiciona todos os arquivos modificados ao stage.  
- `git commit -m "mensagem"`: Salva as alterações com uma mensagem de descrição.  
- `git status`: Mostra o status dos arquivos no repositório.
- `git tag -a <V1.0.0> -m "mensagem sobre a tag"`: Cria uma tag para um commit.
- `git tag `: Mostra as tags criadas.
- `git push --tags `: Mostra as tags criadas.  
- `git rebase -i HEAD~x`: Comando para ter controlo sobre o histórico de commits **x = número de commits que desejo verificar**.
- `git rebase main`: Restaura o histórico da branch atual para ficar em igualdade a branch main.
**obs- nunca fazer rebase na branch main apenas na tua branch**
**ex: branch feature/escola tem 2 commits atrás da main para atualizar o histórico da minha branch utilizo**
**git rebase main - pega no histórico da main e atualiza a minha branch**

---

## 🔄 Branching e Merging
- `git branch`: Lista todas as branches.  
- `git branch <nome>`: Cria uma nova branch.
- `git switch -c <nome>`: Cria e troca para uma nova branch.  
- `git checkout <branch>`: Troca para a branch especificada.  
- `git merge <branch>`: Mescla a branch especificada com a atual.  
- `git branch -d <branch>`: Exclui uma branch.

---

## 🌐 Repositórios Remotos
- `git remote add origin <url>`: Conecta o repositório local a um remoto.  
- `git push origin <branch>`: Envia as alterações para o repositório remoto.  
- `git pull origin <branch>`: Baixa e mescla alterações do repositório remoto.  
- `git clone <url>`: Clona um repositório remoto.  

---

## 🔍 Inspeção e Comparação
- `git diff`: Mostra as diferenças entre arquivos no repositório.  
- `git show <commit>`: Exibe as alterações de um commit específico.  
- `git blame <arquivo>`: Mostra quem modificou cada linha de um arquivo.
- `git fetch`: Compara com a branch main e exibe a quantidade de commits a frente ou atrás da branch atual.
- `git log`: Exibe o histórico de commits.
- `git log --oneline --graph`: Exibe o histórico de commits de maneira mais fácil de ler.

---

## ⚙️ Resolução de Problemas
- `git stash`: Armazena temporariamente alterações não commitadas.  
- `git stash apply`: Recupera alterações armazenadas.  
- `git reset <arquivo>`: Remove um arquivo do stage.  
- `git reset --hard <commit>`: Restaura o repositório para um estado anterior.  
- `git reflog`: Mostra o histórico de alterações no HEAD.

---

Este arquivo contém os principais comandos do Git, organizados para facilitar o aprendizado e consulta! 🚀
