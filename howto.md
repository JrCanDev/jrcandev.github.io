**TUTO - Comment demander l'ouverture d'un compte pour l'hébergement d'un site web statique ?**
---------
Site web statique : html/css. Pas de php ni de BD.

1 - Trouver un nom de projet (nom en minuscule sans caractère spécial)
  
2 - Vérifier que ce nom n'est pas déjà pris en vous rendant à l'adresse : https://projets.jrcandev.netlib.re/NomduProjet sinon trouver un autre nom

3 - Dans le salon ⁠hébergement_projets de la catégorie PROJETS, tagguer admin-sys en donnant le nom du projet à créer et en précisant que c'est pour un site statique.

Le compte sera créé et le mot de passe vous sera envoyé.


**TUTO - Comment mettre en ligne un site web statique au travers du navigateur ?**
---------
1 - Se rendre à l'adresse suivante : https://files.jrcandev.netlib.re/web/client/login

2 - Entrer les login et mot de passe

&nbsp;&nbsp;2a - Si première connexion, changer son mot de passe en cliquant sur la nom du projet en haut à droite de la fenêtre.
![sftpGO_profil](https://github.com/JrCanDev/jrcandev.github.io/assets/6851276/17c31b1c-2009-4d17-aa66-b901da15c25b)
![sftpGO_changement_mot_de_passe](https://github.com/JrCanDev/jrcandev.github.io/assets/6851276/f820c93b-5b01-4b21-9f53-f4fce78b1a11)


&nbsp;&nbsp;2b - Entrer l'ancien mot de passe puis deux fois le nouveau.
  
&nbsp;&nbsp;2c - Validez par "change my password" puis se reconnecter.
  
3 - Cliquer déposer les fichiers à mettre en ligne. Faire attention à bien avoir un fichier **index.html**

Attention ! Impossible de déposer des répertoires. Il faut les créer à la min, entrer dedans et ensuite y déposer les fichiers.
![sftpGO_nouveau_dossier](https://github.com/JrCanDev/jrcandev.github.io/assets/6851276/0e2b6a2f-2491-4203-a04a-aa0b2a9f1e04)

Si des caractères spéciaux apparaissent sur les pages (il y en aura). Il faut ajouter

**<meta charset="utf-8">**

dans la section **header** de vos pages.
