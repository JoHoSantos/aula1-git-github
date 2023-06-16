# aula1-git-github
### ***<h3><p align="center">TUTORIAL BASICO GITHUB</p>***
<!-- TOKEN: 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 -->
  
``Pré configuração para seu usuario:``

<sub>git config --global --unset.all user.name</sub>

<sub>git config --global --unset.all user.email</sub>

<sub>git config --global user.name NOME-DO-USUARIO-GITHUB</sub>

<sub>git config --global user.email EMAIL-DO-GITHUB</sub>

``Para criar pasta:``

<sub>mkdir nome-da-pasta</sub>

``Para acessar pasta:``

<sub>cd nome-da-pasta</sub>

``Para sair da pasta atual:``

<sub>cd ..</sub>

``Para iniciar o repositorio:``

<sub>git init</sub>

``Para criar documentos:``

<sub>echo "# NOME-DA-PASTA" >> NOME-DO-ARQUIVO(.md)(.exe)(.bat). touch NOME-DO-ARQUIVO + EXTENÇÃO (.md)(.exe)(.bat).</sub>

``Para listar itens da pasta:``

<sub>ls</sub>

``Para adicionar conteudo(arquivos) no repositorio:``

<sub>git add NOME-DO-ARQUIVO-PASTA</sub>
<sub>git add . (ponto) [ADICIONA TODOS OS ARQUIVOS/PASTAS)</sub>

``Para desfazer um add:``

<sub>git reset NOME-DO-ARQUIVO</sub>
<sub>git reset (SEM-NOME-DO-ARQUIVO-PARA-DESFAZER-GERAL)</sub>

``Para deixar um comentario no arquivo:``

<sub>git commit -m "DESCRIÇÃO AQUI"</sub>

``Para verificar se tem alguma alteração feita precisando de commit ou ver o status:``

<sub>git status</sub>

``Para adicionar projeto do GIT para o GITHUB``

<sub>git remote add origin LINK-DA-PASTA-NO-GIT-HUB(EX:https://github.com/JoHoSantos/aula1-git-github.git) git branch -M main (para agregar a BRANCH)</sub>

``Para ver alterações feita:``

<sub>git fetch</sub>

``Para enviar/postar arquivo do GIT para o GITHUB``

<sub>git push -u origin main</sub>
