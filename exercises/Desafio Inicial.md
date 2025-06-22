# 🧪 Exercícios Git e GitHub

> Teste seus conhecimentos com desafios práticos baseados em situações reais do dia a dia de um desenvolvedor.

---

## 🧰 Pré-requisitos

- Git instalado ([Download Git](https://git-scm.com))
- Uma conta no GitHub
- Terminal ou Git Bash

---

## 🚦 Níveis de dificuldade

| Nível       | Descrição                              |
|-------------|----------------------------------------|
| 🟢 Iniciante | Comandos básicos                      |
| 🟡 Médio     | Manipulação de branches e conflitos    |
| 🔴 Avançado  | Rebase, cherry-pick e workflows reais  |

---

## 🟢 DESAFIO 1 — Iniciando com Git

**Objetivo**: Criar um repositório local, fazer commits e enviá-lo para o GitHub.

1. Crie uma pasta chamada `meu-projeto`.
2. Inicie um repositório Git:  
   `git init`
3. Crie um arquivo `README.md` com seu nome.
4. Faça um commit inicial.
5. Crie um repositório no GitHub com o mesmo nome.
6. Adicione o repositório remoto e envie:  
   `git remote add origin <URL>`  
   `git push -u origin main`

---

## 🟡 DESAFIO 2 — Trabalhando com Branches

**Objetivo**: Praticar criação, alteração e merge de branches.

1. Clone o repositório criado anteriormente.
2. Crie uma nova branch chamada `dev`:  
   `git checkout -b dev`
3. Crie um arquivo `dev-notes.txt` e escreva algo.
4. Faça commit e volte para a branch `main`.
5. Faça o merge da branch `dev` com a `main`:  
   `git merge dev`

---

## 🟡 DESAFIO 3 — Resolvendo Conflitos

**Objetivo**: Simular e resolver um conflito de merge.

1. Na branch `main`, crie um arquivo `conflito.txt` com o texto:  
   `Linha principal`
2. Faça commit.
3. Crie a branch `conflict` e edite `conflito.txt` para:  
   `Linha conflito`
4. Volte para `main` e edite o mesmo arquivo para:  
   `Linha modificada na main`
5. Faça commit nas duas branches.
6. Agora tente fazer `git merge conflict` dentro da branch `main`.

🔧 Resolva o conflito manualmente, faça `add` e `commit`.

---

## 🔴 DESAFIO 4 — Stash, Rebase e Cherry-pick

**Objetivo**: Comandos intermediários para gerenciamento de alterações.

1. Faça alterações em um arquivo mas **não faça commit**.
2. Use `git stash` para salvar temporariamente.
3. Volte para a branch `main`.
4. Aplique as mudanças com `git stash pop`.
5. Crie uma nova branch `feature-x` a partir de `main`.
6. Faça 2 commits diferentes.
7. Volte para `main` e use `git cherry-pick` para trazer um dos commits.
8. Em seguida, use `git rebase` para reordenar commits em `feature-x`.

---

## 🔴 DESAFIO 5 — Fluxo Colaborativo com Pull Request

**Objetivo**: Praticar colaboração com GitHub.

1. Crie um repositório no GitHub e adicione um colaborador.
2. O colaborador deve:
   - Clonar o repositório
   - Criar uma branch `nova-feature`
   - Fazer uma modificação
   - Enviar a branch com `push`
3. No GitHub, crie um **Pull Request**
4. Faça a revisão, discuta e aceite a alteração.

---

## ✅ Finalização

Marque os desafios que concluiu, e se quiser, **poste seu progresso no GitHub**!

---