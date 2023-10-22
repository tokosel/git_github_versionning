# git_github_versionning
Travaux Pratiques : Gestion de version avec Git/GitHub
Objectif : Apprendre à utiliser Git pour gérer un projet, créer des branches, effectuer des modifications, et
utiliser GitHub pour collaborer avec d'autres personnes.
Instructions :
Étape 1: Configurer Git
a) Installez Git sur votre ordinateur si ce n'est pas déjà fait.
b) Configurez votre nom d'utilisateur et votre adresse e-mail dans Git en utilisant les commandes git
config --global user.name "VotreNom" et git config --global user.email
"votre@email.com".
Étape 2: Créer un dépôt local
a) Créez un nouveau répertoire sur votre ordinateur pour votre projet.
b) Initialiser un dépôt Git local à l'intérieur de ce répertoire en utilisant la commande git init.
Étape 3: Ajouter et valider des fichiers
a) Créez quelques fichiers (par exemple, fichier1.txt, fichier2.js) dans votre répertoire de projet.
b) Ajoutez ces fichiers à l'index (staging area) en utilisant la commande git add <nom-dufichier>.
c) Validez les changements en créant un commit avec la commande git commit -m "Premier
commit".
Étape 4: Créer une branche
a) Créez une nouvelle branche pour travailler sur une nouvelle fonctionnalité en utilisant la commande
git branch ma-branche.
b) Passez à cette nouvelle branche en utilisant la commande git checkout ma-branche.
Étape 5: Effectuer des modifications
a) Modifiez les fichiers que vous avez créés précédemment pour ajouter une nouvelle fonctionnalité.
b) Ajoutez à nouveau ces fichiers modifiés à l'index et validez les changements en créant un nouveau
commit.
Étape 6: Fusionner les branches
a) Revenez à la branche principale (par exemple, "main" ou "master") en utilisant la commande git
checkout main.
b) Fusionnez votre branche de fonctionnalité dans la branche principale en utilisant la commande git
merge ma-branche.
c) Résolvez les éventuels conflits de fusion s'il y en a.
Étape 7: Créer un compte GitHub
a) Si vous n'avez pas encore de compte GitHub, créez-en un sur https://github.com/.
Étape 8: Créer un dépôt distant sur GitHub
a) Créez un nouveau dépôt sur GitHub en suivant les instructions sur la plateforme. Ne cochez pas la case
"Initialize this repository with a README".
Étape 9: Lier le dépôt local au dépôt distant
a) Associez le dépôt local à votre dépôt distant en utilisant la commande git remote add origin
<URL-du-repo-GitHub>.
Étape 10: Pousser les modifications vers GitHub
a) Poussez vos commits vers le dépôt distant en utilisant la commande git push origin main.
Étape 11: Créer une "pull request" sur GitHub
a) Sur la page de votre dépôt sur GitHub, créez une "pull request" pour demander la fusion de votre
branche de fonctionnalité dans la branche principale (main).
b) Demandez à un collaborateur d'examiner et d'approuver votre "pull request".
Étape 12: Mettre à jour le dépôt local
a) Une fois que votre "pull request" a été approuvé et fusionné, mettez à jour votre dépôt local en utilisant
la commande git pull origin main.
