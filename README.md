# 📘 Pretalab Ciclo 14 - Git e GitHub

Este repositório registra minhas práticas e aprendizados de **Git** e **GitHub** durante o Ciclo 14 da Pretalab.

---

## 📚 O que aprendi

- Conceitos básicos: commits, branches, merge.
- Ciclo de vida de arquivos no Git: add → commit → push.
- Trabalhar com repositórios remotos no GitHub.
- Criar, usar e integrar branches.
- Abrir Pull Requests e fazer merge.
- Tags, rebase e git stash.
- Boas práticas de mensagens e nomes de branches.

---

## 🛠️ Comandos principais

### Controle de arquivos
```bash
git status          # Verifica alterações
git add <arquivo>   # Adiciona arquivo ao stage
git commit -m "msg" # Cria um commit
git diff            # Mostra diferenças
Branches
bash
Copiar código
git branch                  # Lista branches
git checkout -b feature-x   # Cria e entra em nova branch
git checkout main           # Troca de branch
Integração
bash
Copiar código
git merge feature-x    # Junta branch com main
git rebase main        # Reaplica commits de uma branch sobre outra
Remoto
bash
Copiar código
git remote -v          # Mostra remotos
git push origin main   # Envia commits
git pull origin main   # Atualiza branch local
🎯 Boas práticas
Mensagens de commit curtas e claras:

feat: nova funcionalidade

fix: correção de bug

Nomes de branches descritivos: feature/login, bugfix/cart

Fazer commits pequenos e frequentes.

Manter a branch main estável.

Atualizar a branch antes de dar push (git pull --rebase).



