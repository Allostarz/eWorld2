git add temp.txt
Clone git
La commande git clone est utilisée pour la vérification des dépôts. Si le dépôt se trouve sur un serveur distant, utilisez:
git clone alex@93.188.160.58:/chemin/vers/dépôt
Inversement, si une copie de travail d’un dépôt local doit être créée, utilisez:
git clone /chemin/vers/dépôt
Git commit
La commande git commit permet de valider les modifications apportées au HEAD. Notez que tout commit ne se fera pas dans le dépôt distant.
git commit –m “Description du commit”