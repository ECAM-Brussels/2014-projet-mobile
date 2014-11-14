# Repos gits
- [Application ISEI 1](https://github.com/ApplicationISEI/isei)
- [ApplicationISEI/ISEI-2](https://github.com/ApplicationISEI/ISEI-2)
- [bouffeaalma](https://github.com/bouffeaalma/Projet-Android)


# Installateur de packets pour : Windows - OSx - Unix
Pour installer les dépendances, nous présentons comment le faire sous windows avec chocolately

Pour y arriver sous linux our osx remplacer ces appels par `apt-get` ou `brew` ou installer les à partir de site

- [Windows : Chocolatey](https://chocolatey.org/)
- Osx :
	- [Homebrew — The missing package manager for OS X](http://brew.sh/)
	- [Homebrew Cask](http://caskroom.io/)
	- [braumeister.org](http://braumeister.org)
- Unix : Apt

# Phonegap points de départ dans la documentation
- [Wiki](https://github.com/phonegap/phonegap/wiki)

# Phonegap minimale
Phonegap est aussi un utilitaire [nodejs](http://nodejs.org/) qui vous permettera de générer un projet phonegap,
de le compiler en apk, de l'exécuter dans un émulateur, ou de le lier à l'app [PhoneGap Developer - Android](https://play.google.com/store/apps/details?id=com.adobe.phonegap.app) 

sur une ligne de commande :
```sh
choco install nodejs
npm install -g phonegap
phonegap create my-android-project-name-here
cd my-android-project-name-here
```

# Tester avec : un server web nodejs
## Dépendances
- [nws](https://www.npmjs.org/package/nws)
```sh
npm install -g nws
cd android-project/www
nws
# browse : localhost:3030
# on mobile : %pc_ip_address%:3030
```

# Tester avec : Phonegap Developer App
## Dépendances
- [PhoneGap Developer App](http://app.phonegap.com/)
- [PhoneGap Developer - Android](https://play.google.com/store/apps/details?id=com.adobe.phonegap.app)
```sh
cd my-android-project-name-here
phonegap serve
# accessible sur mobile ou sur le web
```
