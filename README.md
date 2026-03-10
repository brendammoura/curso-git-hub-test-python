# Curso Git Hub Test Python

Projeto criado durante o curso de Git e testes com Python.
Anotações de estudos da CTFL.

## Objetivo
Aprender Git, GitHub e automação de testes, utilizando novos meios de estudos para CTFL.

## Tecnologias
- Python
- Git
- GitHub

# Comandos básicos do Git

Este documento reúne alguns dos principais comandos utilizados no terminal para trabalhar com Git e GitHub.

## Verificar versão do Git

Mostra a versão do Git instalada no computador:
git --version


---

## Inicializar um repositório

Cria um novo repositório Git dentro da pasta do projeto:
git init

---

## Verificar o status do projeto

Mostra os arquivos modificados, novos ou prontos para commit:
git status

---

## Adicionar arquivos para o commit

Adiciona arquivos para serem incluídos no próximo commit.

Adicionar um arquivo específico:
git add nome-do-arquivo

Adicionar todos os arquivos modificados:
git add .

---

## Criar um commit

Salva uma nova versão do projeto no histórico do Git:
git commit -m "mensagem do commit"

Exemplo:
git commit -m "adiciona README"

---

## Conectar o repositório ao GitHub

Adiciona o repositório remoto (GitHub) ao projeto local:
git remote add origin URL_DO_REPOSITORIO

Exemplo:
git remote add origin https://github.com/usuario/repositorio.git

---

## Enviar alterações para o GitHub

Envia os commits locais para o repositório remoto:
git push origin master
ou
git push origin main

---

## Ver repositório remoto conectado

Mostra os repositórios remotos vinculados ao projeto:
git remote -v

---

## Fluxo básico de trabalho com Git
git add .
git commit -m "mensagem"
git push

Esse fluxo representa:

1. adicionar mudanças
2. criar um commit
3. enviar para o GitHub

---

## Ver os últimos commits da branch com Git:
git log

---

## Pegar as modificações de outros programadores no código:
git pull origin master