https://openclassrooms.com/courses/gerer-son-code-avec-git-et-github/faire-son-premier-commit

Pour faire un commit il faut:
       
créer un repository dans github        ---> echo "# aaaaaa" >> README.md

initier un git 						   --->	git init

ajouter un fichier ou des fichiers     ---> git add README.md

initier un commit et le décrire		        git commit -m "first commit"

ajouter ce commit à github 		   	   --->	git remote add origin https://github.com/username
dans le bon repository     		      		/blablabla.git

L'envoyer sur la branche principale    ---> git push -u origin master