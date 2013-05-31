GitMemo
=======

Just some git commands

###Comparer un fichier entre deux branches###

    git difftool branch01:file branch02:file



###Forcer la récupération d'un fichier à partir d'une autre branche###

    git checkout <branch_name> -- <paths>


### Pousser une branche locale sur le remote ###

Pour la personne qui souhaite pousser la branche :

    git push origin branche_locale
    
Pour que quelqu'un d'autre la récupère

    git checkout -b test origin/test

###Annuler un merge###

    git merge --abort
    
