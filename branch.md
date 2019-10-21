$ git branch dev : création d'une branche

$ git checkout dev : déplacement sur une branche

$ git checkout -b [nom] : déplacement en une seule commande

$ git branch -d [nom_de_la_branche] : suppression de la branche

$ git branch -D [nom_de_la_branche] : forcer la suppression d'une branche

$ git merge [nom] : merge la précédente branche vers la branche nommée avec le [nom]

$ git branch --no-merged : commande pour visualiser les listes dans branches non mergées

$ git log --oneline --graph : visualiser le graph des commits à partir de la branch dans laquelle nous travaillons

$ git stash : remiser le code non terminé

$ git stash list : lister sur la branch les stash

$ git stash apply : récupération de son code modifié

$ git stash drop : suppression de la remise

$ git tag : liste des tags

$ git tag :
    - -a v1.0 -m : tag annoté : objet dans le Git qui pointe un commit donné et n'est pas mobile
    - v1 : tag léger : branche mais le tag n'est pas mobile, il est associé à un commit