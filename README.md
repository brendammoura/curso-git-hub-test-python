# Curso Git Hub Test Python 
## Projeto Estudos de Git e GitHub

Prática de controle de versão utilizando Git e GitHub, incluindo criação de repositórios, commits, versionamento de arquivos, documentação em README e publicação de projetos.

## Tecnologias
- Python
- Git
- GitHub
- Visual Studio Code

---

## Aprendizados
- Inicialização de repositórios Git
- Controle de versão com commits
- Publicação de projetos no GitHub
- Leitura de arquivos em Python

---

## Autora
Brenda Moura

---

# Comandos básicos do Git

Este documento reúne alguns dos principais comandos utilizados no terminal para trabalhar com Git e GitHub.

## Verifica versão do Git

Mostra a versão do Git instalada no computador:
git --version

---

## Inicializa um repositório

Cria um novo repositório Git dentro da pasta do projeto:
git init

---

## Verifica o status do projeto

Mostra os arquivos modificados, novos ou prontos para commit:
git status

---

## Adiciona arquivos para o commit

Adiciona arquivos para serem incluídos no próximo commit.

- Adiciona um arquivo específico:
git add nome-do-arquivo

- Adicionar todos os arquivos modificados:
git add .

---

## Cria um commit

Salva uma nova versão do projeto no histórico do Git:
git commit -m "mensagem do commit"

Exemplo:
git commit -m "adiciona README"

---

## Conecta o repositório ao GitHub

Adiciona o repositório remoto (GitHub) ao projeto local:
git remote add origin URL_DO_REPOSITORIO

Exemplo:
git remote add origin https://github.com/usuario/repositorio.git

---

## Envia alterações para o GitHub

Envia os commits locais para o repositório remoto:
git push origin master
ou
git push origin main

---

## Verifica repositório remoto conectado

Mostra os repositórios remotos vinculados ao projeto:
git remote -v

---

## Fluxo básico de trabalho com Git
git add . > git commit -m "mensagem" > git push

Esse fluxo representa:

1. Adiciona mudanças
2. Cria um commit
3. Envia para o GitHub

---

## Verifica os últimos commits da branch com Git
git log

---

## Verifica as modificações de outros programadores no código
git pull origin master

---

## Mostra as diferenças do código anterior e do código atual no terminal
git diff

---

## Une tudo que foi escrito no log e condensa de maneira mais simples
git shortlog ou git log --oneline

---

## Teclas no git log
| Tecla  | Função          |
| ------ | --------------- |
| ↓ ou ↑ | rolar linhas    |
| Space  | próxima página  |
| b      | página anterior |
| q      | sair            |

---

## Limpa o terminal
clear

---

## Mostra tudo que foi feito no commit e modificações no arquivo
git show

---

## Reverte modificações
git reset valor-hash

git checkout

