$ git blame : recherche modif

$ git diff : vérifier les fichiers changer et ce qui a été changé dans les fichiers
    - git diff HEAD~1 : vérifier un commit précédent
    - git diff HEAD~3 : 3 commits en arrière

$ git restore [dossier] : remettre un dossier dans son état initial avant une modification
    - git restore --staged : commande à appliquer une fois une modification faite et que l'on ajoute le dossier dans l'index

$ git commit "un message" --amen --no-edit : changer uniquement le "message" du dernier commit

$ git reset (HEAD~1) : annule les changements et reviens à la branche précédente (branche locale)

$ git reset [historique] : annulation de ce commit via le numéro [histoirique]

$ git reset --hard HEAD~1 : annule le dernier commit et supprime les modifications 

$ git checkout : déplacement dans l'arbre git 

$ git checkout [nom] : permet de revenir au parant du commit

$ git revert : annule les changements et partage ces annulations avec d'autres