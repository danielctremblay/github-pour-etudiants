# :wave: Leçon 1 : Les bases de GitHub pour GIS 811

## 🤓 Les finalités d'apprentissages de cette leçon

Le but de cette leçon est d'offrir une introduction à GitHub. Des ressources supplémentaires vous seront également suggérées afin de parfaire vos apprentissages et favoriser le démarrage de vos projet en qualité de données sur cette plateforme. 🚀

## :octocat: Git et GitHub

Git est un **système de gestion du versionnement (VCS, en anglais) distribué**. C'est un outil qui facilite la gestion des changements dans vos projets de code, de documentation ou d'écriture et favorise la collaboration et le partage. À l'aide de Git, vous pouvez suivre les changements dans votre projet de façon à conserver une copie de tout ce que avez produit et, au besoin, revenir à une version antérieure d'un projet. Git facilite aussi le développement de projets en collaboration avec d'autres personnes. Tous les membres d'un groupe peuvent collectivement participer à un projet commun et fusionner (*merge*) leurs contributions dans une version finale.

GitHub est une initiative qui permet de tirer toute la puissance de Git tout en offrant une interface Web conviviale. GitHub est largement utilisé dans l'univers technologique et au-delà pour soutenir la collaboration et assurer le versionnement de projets.

GitHub sert à propulser de nombreuses technologies de pointe dans le monde. Que vous souhaitiez visualiser les données, automatiser des processus ou rédiger des documents, GitHub facilite l'accès à une communauté et des outils qui peuvent vous aider à faire avancer votre projet. Cette leçon débute avec les bases de GitHub pour l'utilisation dans l'apprentissage du langage SQL.

## :octocat: Comprendre la séquence de travail de GitHub

La séquence des opérations GitHub consiste en un flux de travail simple qui favorise l'expérimentation et la collaboration dans vos projets sans le risque de compromettre ou perdre les versions antérieures de vos réalisations.

### Les référentiels

Un référentiel (*repository ou repo*) est l'espace dédié de votre projet, pensez au référentiel comme un dossier de travail. Il contient tous les fichiers du projet et chacune de leur version. Vous pouvez travailler seul ou en équipe sur les fichiers d'un référentiel.
<img src="https://www.freecodecamp.org/news/content/images/2019/11/explanation.png"></img>

### Le clonage

Lorsqu'un référentiel est créer au moyen de GitHub, il est stocké dans le nuage. Vous pouvez cloner un référentiel pour créer une copie locale sur votre poste de travail, puis utiliser Git pour synchroniser les deux instances. Ce fonctionnement simplifie la résolution de problème, l'ajout ou le retrait de fichiers et le téléversement (*push*) de contributions (*commits*) volumineuses. Vous pouvez également utiliser l'outil d'édition de votre choix plutôt que l'interface Web de GitHub. Cloner un référentiel permet de récupérer l'ensemble des données du référentiel présent dans GitHub à ce moment précis. Ceci inclut toutes les versions antérieures de tous les fichiers et dossiers du projet! Cette façon de faire peut s'avérer très utile si vous découvrez, lors de l'évolution du projet, que vous préférez une version précédente spécifique. Vous pouvez apprendre à cloner un référentiel en consultant la leçon ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)(en).

### L'indexation et le téléversment

L'indexation et le téléversement (*commiting and pushing*) permettent la documentation et le transfert des changements que vous avez faits sur votre poste de travail vers le référentiel stocké dans le nuage GitHub. De cette façon, votre enseignant ou vos collègues peuvent accéder à vos plus récentes contributions lorsque vous êtes prêt à les partager. Vous pouvez indexer les changements dans votre projet à tout moment, mais il est généralement pratique d'indexer vos contributions lorsque vous terminez une période spécifique de travail (ex. fin d'une session, d'un jour ou d'un sprint de travail) ou lorsque vous avez atteint un jalon particulier du projet. Chaque indexation permet de créer un point de contrôle (*checkpoint*) auquel vous pouvez ajouter un message qui spécifie la nature la contribution que vous indexez (ex. La requête no. 1 est complétée). Les messages d'indexation permettent de suivre et de contrôler les contributions au projet dans le temps.

Lorsqu'un ou plusieurs points de contrôle ont été ajoutés au projet vous pouvez téléverser l'ensemble des changements au référentiel distant GitHub en utilissant la commande **push**. L'indexation et le téléversement peuvent paraître nouveaux au départ, mais vous vous y ferez rapidement.

### GitHub, pour aller plus loin (non requis pour GIS 811)

Dans le cadre du cours GIS 811, vous aurez à utiliser principalement le clonage, l'intexation et le téléversement. Toutefois, GitHub sert d'abord la communauté de développement logiciel. Pour cette raison, il offre un ensemble de fonctionnalités dédiées à la gestion des contributions simultanées de plusieurs personnes. Si ces fonctionnalités ne sont pas en usage dans le cours, il peut être utile de connaître les concepts clés dans l'éventualité d'une collaboration avec une équipe BI ou TI. GitHub permet notamment de créer des branches (*branches*), i.e. des versions alternatives et concurrentes de votre projet, des biffurcations (*forks*), i.e. des versions alternatives et concurrentes de projets d'autres personnes et des demandes d'intégration qui permettent d'évaluer les contributions externes pour les intégrer à la version principale (*main*) d'un projet. Vous pouvez approfondir les notions de GitHub et accéder à différentes resssources en suivant les liens suivants :

#### 📚  Ressources (en) (non requis pour GIS 811)
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)

# :wave: Leçon 2 : Un guide d'utilisation de **GitHub Classroom** pour étudiants

**GitHub Classroom** est un environnement spécifique de GitHub dédié à la gestion de formation pour les étudiants. L'utilisation de cet environnement fait partie des compétences en gestion de l'intelligence d'affaires dans le cours GIS 811. Plus spécifiquement, on gère ici le cycle de production du profilage de données au moyen du langage SQL.

## 🤓 Les finalités d'apprentissages de cette leçon

Le but de cette leçon est d'offrir une introduction à **GitHub Classroom**. Des ressources supplémentaires vous seront également suggérées afin de parfaire vos apprentissages et favoriser le démarrage de vos projet en qualité de données sur cette plateforme.

## Étapes d'introduction
* Créez un compte GitHub étudiant
* Téléchargez, installez et configurez votre client GitHub
  * Client logiciel [GitHub Desktop](https://desktop.github.com). [Voir la documentation](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop).
  * Plugiciel [GitHub et Git pour DataGrip](https://blog.jetbrains.com/datagrip/2018/12/11/datagrip-and-github-step-by-step-integration/)
  * *Attention : vous devez choisir un répertoire racine pour tous vos projets de développement (peut être changé ultérieurement). [Voir la documentation](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/configuring-and-customizing-github-desktop).*
* Suivez le lien GitHub Classroom qui vous est communiqué.
* Sur GitHub Classroom, sélectionnez votre identifiant Classroom (courriel) pour l’associer à votre compte étudiant GitHub.
* Récupérez le référentiel des exercices en exécutant un « *pull* » ou « *fetch origin* ». Voir la documentation pour l’utilisation à des fins de projet.
* Complétez les exercices selon les travaux à réaliser. 
  * Attention! Modifiez directement les fichiers fournis ou ajouter les fichiers nécessaires dans les dossiers du projet.
* Exécutez un « *commit* » à chaque changement important ou fin de période de travail. Ceci permet de garder une trace des changements effectués.
* Exécutez un « *push origin* » pour téléfverser l’ensemble des changements (et l’historique) sur le serveur distant de GitHub Classroom. Le travail pourra alors être corrigé par votre enseignant.
* Vous pouvez exécuter autant de « *push origin* » que vous le souhaitez durant une période de travail.
* Vous pouvez également accéder à votre référentiel directement sur le site Web GitHub par l'entremise de votre navigateur Web. Vous pouvez y modifier l’ensemble des fichiers, mais vous devez alors recopier manuellement le contenu de votre client SGBDR et le site (moins efficace).
* Les fonctionnalités avancées de la mécanique d'embranchement, de récupération d'erreur, de gestion des collisions des modifications, la modification manuelle de l’historique et la gestion des problèmes ne sont pas utiles pour ce cours.
* Si vous êtes de nature curieuse, vous pouvez appliquer au Developer Pack. Cela vous donne accès à une foule de ressources technologiques avec lesquelles vous pouvez vous familiariser. Ces technologies ne seront cependant pas utilisées dans le cadre du cours.


## Autres ressources intéressantes
* [Introduction à GitHub Classroom, un exemple avec R](https://github.com/jfiksel/github-classroom-for-students)(en)
* [Tutoriel de GitHub selon la perspective étudiante](http://evantilton.com/guides/githubclass/)(en)

## Tâches pour cette leçon
* Créez un fichier cip.txt 
* Éditez le fichier et insérez votre cip comme seul texte
* Faites un « *commit* » de votre texte (en ajoutant un message significatif)
* Téléversez ce fichier sur GitHub Classroom dans ce projet si vous utilisez un client GitHub
