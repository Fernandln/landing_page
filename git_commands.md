# Trabalhando sozinho no git/Github

1. Instalar o git - https://git-scm.com/
2. o Git é uma ferramenta que voce instala no seu sistema operacional.
3. Por sua vez o GitHub é uma rede social/plataforma onde você armazena seus projetos.
4. Repositorio local é quando o [projeto/commits/branchs] ainda está no seu computador.
5. é quando o repositorio remoto é quando o projeto esta na nuvem, ex: github, fontes, gitlab...



## Criando um repositorio local pelo git

1. Abrir o projeto no [VSCode]
2. Abra o terminal no VSCode, Ctrl+J ou Ctrl+'.
3. `Git init` - inicializa o repositorio Git, inicia o repositorio git
4. `git status` - Exibe todos os arquivos presentes no repositorio, quais estão modificados atualizados e não adicionados.
5. `git add [nome_do_arquivo]` - adiciona os arquivos ao repositorio local.
6. `git add .` - Adiciona todos os arquivos.
7. `git commit -m "mensagem do oommit"` - Cria um commit, uma atualização do codigo.
8. `git log` -> lista os commits que foram realizados.
9. `git log --oneline --graph --decorate` -> uma forma compacta de exibir o log
10. `git branch [Nome_da_Branch] ` - Cria uma nova branch.
11. `git branch -M main ` - Força a criação de uma branch chamada Main.
12. `git checkout nome_da_branch` -> muda a branch.
13. `git branch` - exibe as branchs criadas.
14. `git remote add origin https://exemplo.com` - realiza a sincronização do repositorio local com o repositorio remoto.
15. `git push -u origin main` - Envia as informações do repositorio
16. `git clone [url que voce quer copiar]` - faz uma copia de outro repositorio remoto.