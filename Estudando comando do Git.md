# Estudando comando do Git

1. Criar um arquivo ".gitignore" na pasta inicial do repositório
2. Procurar no google por gitignore visual studio 2020 para pegar as exclusões
3. Iniciar o gitbash na pasta do repositório
4. git init -> comamdo para inicializar o repositório
5. Comandos de identificação:
   1. git config --global user.name "Fabrício Procaci"
   2. git config --global user.email "fprocaci@gmail.com"
6. Comandos para salvar a versão:"
   1. git add . -> Comando para mandar os arquivos para a stage
   2. git commit -m "descrição do commit" -> Comando para enviar os commits que estão na stage
7. Comandos para voltar ao último commit:
   1. git clean -df
   2. git checkout
8. Comando para ver todos os commits e suas descrições
   1. git log --oneline
9. Comandos para reescrever a descrição do último commit e para desfazer o último commit
   1. git reset --soft HEAD~1 -> comando para reescrever a descrição do último commit
   2. git reset --hard HEAD~1 -> comando para desfazer o último commit
10. Comando para assossiar meu repositório local ao do GitHub
    1. git remote add origin <URI do repósitório no GitHub>
    2. git remote set-url origin <URI do repósitório no GitHub>
11. Comando para clonar um repositório do GitHub

