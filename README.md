# 📘 Guia de Comandos Git

Este repositório tem como objetivo documentar e explicar os principais comandos do **Git**, uma ferramenta essencial para o controle de versão em projetos de desenvolvimento de software.

## 🧠 Objetivo

Ajudar iniciantes e desenvolvedores que desejam revisar ou aprender os comandos mais usados do Git com exemplos práticos.

---

## ⚙️ Pré-requisitos

Antes de usar os comandos, é necessário ter o Git instalado no seu sistema.  
Você pode baixar o Git em: https://git-scm.com/

---

## 📋 Comandos Básicos

| Comando | Descrição |
|--------|-----------|
| `git init` | Inicializa um novo repositório Git. |
| `git clone <url>` | Clona um repositório remoto. |
| `git status` | Mostra o status dos arquivos no diretório de trabalho. |
| `git add <arquivo>` | Adiciona arquivos à área de stage. |
| `git commit -m "mensagem"` | Salva as alterações com uma mensagem descritiva. |
| `git push` | Envia os commits para o repositório remoto. |
| `git pull` | Puxa as alterações do repositório remoto para o local. |
| `git log` | Mostra o histórico de commits. |
| `git branch` | Lista as branches existentes. |
| `git checkout <branch>` | Troca para outra branch. |
| `git merge <branch>` | Junta a branch especificada com a atual. |

---

## 🧪 Exemplos Práticos

### Iniciando um projeto com Git

```bash
git init
git add .
git commit -m "Primeiro commit"
git remote add origin <URL-do-repositório>
git push -u origin main

