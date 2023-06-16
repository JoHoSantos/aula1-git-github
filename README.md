# aula1-git-github

Tutoriais GITHUB
Pré configuração para seu usuario:
git config --global --unset.all user.name
git config --global --unset.all user.email
git config --global user.name NOME-DO-USUARIO-GITHUB
git config --global user.email EMAIL-DO-GITHUB

para criar pasta:
mkdir nome-da-pasta

para acessar pasta:
cd nome-da-pasta

para sair da pasta atual:
cd ..

para iniciar o repositorio:
git init

para criar documentos:
echo "# NOME-DA-PASTA" >> NOME-DO-ARQUIVO(.md)(.exe)(.bat).
touch NOME-DO-ARQUIVO + EXTENÇÃO (.md)(.exe)(.bat).

para listar itens da pasta:
ls

para adicionar conteudo(arquivos) no repositorio:
git add NOME-DO-ARQUIVO-PASTA
git add . (ponto) [ADICIONA TODOS OS ARQUIVOS/PASTAS)

para desfazer um add:
git reset NOME-DO-ARQUIVO
git reset (SEM-NOME-DO-ARQUIVO-PARA-DESFAZER-GERAL)

para deixar um comentario no arquivo:
git commit -m "DESCRIÇÃO AQUI"

para verificar se tem alguma alteração feita precisando de commit ou ver o status:
git status

para adicionar projeto do GIT para o GITHUB
git remote add origin LINK-DA-PASTA-NO-GIT-HUB(EX:https://github.com/JoHoSantos/aula1-git-github.git)
git branch -M main (para agregar a BRANCH)

para ver alterações feita:
git fetch

para enviar/postar arquivo do GIT para o GITHUB
git push -u origin main



.gitignore TOKEN: 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
