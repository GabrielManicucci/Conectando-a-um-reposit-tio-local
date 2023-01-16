# Git and GitHub 
	- Learning about git and GitHub
	
#  Comandos básicos 
	- git add . (prepara o arquivo ordenando quais arquivos devem ser adicionados,
  no caso,todos arquivos com o ponto ".")
  	- git commit -m " " (adiciona um ponto na história)
	- git log (pesquisa/reastreia os commits feitos)
	- git diff (mostra as modificações no código dos arquivos que ainda não foram
adicionados para serem commitados
	- git diff --color-word
	- git commit -am "mensagem" (já adiciona de forma direta as alterações nos 
aquivos que já foram commitados, dessa forma não precisa usar de novo "git add")
	- git show código do commit (mostra as modificações que já foram commitadas)
	 git rm -r --cached (remove tudo que está no repositório local)

# Comandos para criar um repositpó local git e linkar com github
-  git init .
-  git add .
-  git commit -m "initial commit"
-   git remote add origin: link
-   git push -u origin main
