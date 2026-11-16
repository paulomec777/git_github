# Comandos Git

Resumo dos comandos básicos de Git, feito na aula final de Git e GitHub. O
arquivo original está em `comandos git.docx`.

## Configuração

| Comando | O que faz |
| ------- | --------- |
| `git config --local user.name "Seu Nome"` | Define o nome do autor dos commits neste repositório |
| `git config --local user.email "seu@email.com"` | Define o e-mail do autor dos commits neste repositório |

## Começando um projeto

| Comando | O que faz |
| ------- | --------- |
| `git init` | Inicia um repositório Git na pasta atual |
| `git init --bare` | Cria um repositório "servidor" local, sem pasta de trabalho |

## Dia a dia

| Comando | O que faz |
| ------- | --------- |
| `git status` | Mostra o que mudou e o que está pronto para o commit |
| `git add nome-do-arquivo` | Adiciona um arquivo ao próximo commit |
| `git add .` | Adiciona todos os arquivos e pastas alterados |
| `git commit -m "mensagem"` | Registra um snapshot das mudanças adicionadas |
| `git log` | Mostra o histórico de commits |

## Ignorando arquivos

Liste no arquivo `.gitignore` os arquivos e pastas que não devem ir para o
repositório, como `target/`, `.metadata/` e arquivos com senhas.
