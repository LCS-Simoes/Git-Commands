# Guia de Git e GitHub

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="100" height="100" />
</p>

## 📌 Observações

**Branch (ramo)**: No Git, um "ramo" é uma linha de desenvolvimento independente. Você pode criar novos ramos a partir de um ramo existente para trabalhar em novas funcionalidades ou correções sem interferir diretamente no ramo principal (geralmente chamado de `master` ou `main`).

**-u (upstream)**: Este parâmetro é usado para configurar o "upstream" de um ramo. O upstream é o repositório remoto e o ramo remoto ao qual seu ramo local será enviado (`push`) e do qual receberá atualizações (`pull`).

**-m (move)**: Este parâmetro é usado para renomear um ramo localmente. Você pode usar `-m` seguido pelo nome atual do ramo e pelo novo nome para renomeá-lo.

**Fork**: Um "fork" no GitHub se refere à ação de criar uma cópia do repositório de um usuário em seu próprio espaço no GitHub. Isso permite que você trabalhe independentemente sem afetar o repositório original.

---

## 🚀 Iniciando o versionamento em um repositório

```bash
  echo "#NomeDoRepositorio" > README.md
  git init
  git add README.md  # Não é obrigatório, mas é recomendado
  git commit -m "Primeiro commit"
  git branch -M main
  git remote add origin https://github.com/linkparaseurepositorio.git
  git push -u origin main
```

---

## 🔥 Comandos comuns

```bash
  git add [arquivo]  # Adiciona um arquivo ao índice (staging area) para o próximo commit
  git commit -m "mensagem"  # Salva as mudanças adicionadas ao índice, com uma mensagem
  git status  # Mostra o estado atual do repositório
  git diff  # Exibe diferenças entre arquivos modificados e o último commit
  git pull  # Baixa e mescla mudanças do repositório remoto para o ramo atual
  git push origin [ramo]  # Envia commits do repositório local para o repositório remoto
  git fetch  # Baixa atualizações de um repositório remoto sem mesclá-las
  git checkout -- .  # Descarta as mudanças locais e restaura os arquivos para o último commit
```

---

## 🌿 Git Branch (Ramos)

```bash
  git branch -a  # Lista todos os ramos, tanto locais quanto remotos
  git branch [nome-do-ramo]  # Cria um novo ramo
  git branch -d [nome-do-ramo]  # Deleta um ramo local (use com cuidado)
  git branch -m [nome-do-ramo] [novo-nome]  # Renomeia um ramo
  git checkout [nome-do-ramo]  # Troca para um ramo diferente
  git checkout -b [nome-do-ramo]  # Cria e troca para um novo ramo
  git merge [nome-do-ramo]  # Mescla mudanças de outro ramo para o ramo atual
  git push origin [nome-do-ramo]  # Envia commits do ramo local para o repositório remoto
```

---

## ⚡ Comandos avançados

```bash
  git rebase [nome-do-ramo]  # Reaplica commits de um ramo para outro
  git cherry-pick [hash-do-commit]  # Aplica mudanças de um commit específico para o ramo atual
  git diff --staged  # Mostra diferenças entre o último commit e o que está preparado para o próximo commit
  git reflog  # Exibe o histórico das referências HEAD, útil para recuperar commits perdidos
  git stash  # Armazena temporariamente mudanças para que você possa trabalhar em outra coisa
  git stash pop  # Restaura mudanças que foram salvas com `git stash`
  git revert [hash-do-commit]  # Cria um novo commit que desfaz as mudanças feitas por um commit anterior
```

---

## 🔐 Conectando com SSH

Para configurar o GitHub com SSH, acesse:

🔗 [Documentação Oficial](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)

---

## 🤔 Diferenças entre Git, GitHub e Git Bash 😵

| Ferramenta  | O que é | Função Principal |
|------------|----------|----------------|
| **Git** | Sistema de controle de versão distribuído | Gerenciar e versionar código localmente |
| **GitHub** | Plataforma online que hospeda repositórios Git | Facilitar a colaboração e gerenciamento de projetos com Git na web |
| **Git Bash** | Terminal para Windows com suporte a comandos Unix e Git | Executar comandos Git e Unix no Windows |

---

## 📜 Licença

Este material é de uso livre e pode ser compartilhado e modificado conforme necessário. 😊

---

