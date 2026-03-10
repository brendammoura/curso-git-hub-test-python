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
git add  > git commit -m "mensagem" > git push

Esse fluxo representa:

1. Adiciona mudanças
2. Cria um commit
3. Envia para o GitHub

---

## Verifica os últimos commits da branch com Git
git log

---

## Verifica as modificações de outros programadores no código
- Baixa atualizações do repositório remoto para o repositório local

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
git reset 

git checkout

---

## Lidando com conflitos de código
- Realiza a verificação de onde está ocorrendo o conflito;
- Corrige o conflito;
- Adiciona (git add) > realiza o commit (git commit -m) > envia ao servidor novamente (git push origin master).

## Baixando repositórios
Exemplos de repositórios para utilizar:
- [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x.git)
- [Laravel](https://github.com/laravel/laravel.git)
- [free-programming-books](https://github.com/EbookFoundation/free-programming-books.git)
- [public-apis](https://github.com/public-apis/public-apis.git)
- [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms.git)

Como baixar/usar esse repositório:
- Clica em Code;
- Pode baixar em Download ZIP ou usando o terminal.

Para usar o terminal:
- Clica em Code;
- Copia o link https;
- Abre o Terminal;
- Digita git clone URL-DO-REPOSITÓRIO;
- Clica Enter;
- Ao acessar a pasta do projeto e o VSCode está a pasta do projeto.

---

## Dicas para uso do terminal
- Para adicionar todos os arquivos modificados: git add .
- Fazer git add e commit na mesma linha: git commit -am "insere a mensagem" e clica Enter.

## Dicas extras:
- Clone o que puder;
- Pulls constantes (para quem trabalha com mais pessoas);
- Sem medo de commitar, quantos mais commits melhor para voltar para linhas antigas do seu repositório;
- Mensagens de commits decentes, seja claro na mensagem para facilitar a verificação;
- Push com segurança, não é legal ficar voltando commits, então só dê Push na hora certa;
- Contribua no GitHub;
- Use constantemente o GitHub, acompanhe códigos de outros programadores, siga amigos, etc;
- ReadMe Elegante, faça páginas informativas, produza uma documentação boa;
- Cuidado com vazamentos, arquivos que tem senhas ou acessos! Não realize commit deles (crie o .gitignore).


---

## Arquivos importantes
- README
- GITIGNORE

OBS: ver no repositório do Laravel o README e o .gitignore para obter as informações.
