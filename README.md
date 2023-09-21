# La_Launay_Toons

Ce projet permet d'apprendre la cohesion d'équipe sur un logiciel tel que github.

Pour cloner un projet pour travailler dessus en local on utilise : 
cd Dossier/avec/ton/projet/
git clone https:/github.com/Clement-Szewczyk/La_launay_toonsgit



## Utilisation de git :

### Créer une clé SSH

- Sur Ubuntu on peut utiliser la commande `ssh-key`
- Sur Windows, on peut utiliser la commande `ssh-keygen -t rsa -b 2048 -C "votre_email`

### Ajouter la clé à GitHUb 

  Pour ajouter la clé ssh à votre compte github, vous devez aller dans les paramètres puis dans l'onglet "SSH AND GPG keys" puis cliquez sur ajouter une clé.


### Cloner un dépot 

  Pour clonner un dépot, on doit aller sur la page principale du dépot l'onglet "code". 
  Sur cette onglet, il y a un bouton vert avec écrit "code". Cliquez dessus puis sur ssh et copier le lien.

  Dans un terminale sur votre PC, aller à l'endroit où vous voulez stocker le dossier, puis tapez la commande suivate : 

  `git clone url_copier` en remplaçant url_copier par l'url du dépot. 

### Mettre à jour le dossier 

  Pour mettre à jour le dossier, vous pouvez utiliser les deux commandes suivantes: 

  `git pull`
  `git fetch`

### Faire votre commit 

  Dans un premier temps, vous devez ajouter les fichiers que vous créé/modifié avec la commande `git add "nom_du_fichier"`
  Puis vous devez faire la commande qui va créer le commit : 
  `git commit -m "Nom_de_votre_commit"`

### Envoyer le commit

  Pour envoyer le commit vers le répertoire GitHub, il suffit de faire la ligne de commande `git push`. 