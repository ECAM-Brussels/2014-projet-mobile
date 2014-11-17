# Git Repos
- [Application ISEI 1](https://github.com/ApplicationISEI/isei)
- [ApplicationISEI/ISEI-2](https://github.com/ApplicationISEI/ISEI-2)
- [bouffeaalma](https://github.com/bouffeaalma/Projet-Android)


# Package managers : Windows - OSx - Unix
The following descriptions will show how to install on windows with chocolatey

Just replace the `choco` calls by `apt-get` or `brew` if you are on unix or osx

- [Windows : Chocolatey](https://chocolatey.org/)
- Osx :
	- [Homebrew — The missing package manager for OS X](http://brew.sh/)
	- [Homebrew Cask](http://caskroom.io/)
	- [braumeister.org](http://braumeister.org)
- Unix : Apt

# Documentations links
## PhoneGap
- [Wiki](https://github.com/phonegap/phonegap/wiki)

# PhoneGap
## Introduction
PhoneGap is a [nodejs](http://nodejs.org/) utility that will help you :
- generate a PhoneGap project
- build an apk from your project
- run your project in an emulator
- run you project on your android phone

## Installing PhoneGap
**Dependencies**
- [node.js](http://nodejs.org/)
- [PhoneGap | Home](http://phonegap.com/)
- [Git](http://git-scm.com/)

in a commandline :
```sh
choco install nodejs
npm install -g phonegap
phonegap create my-android-project-name-here
cd my-android-project-name-here
```

## Run in a browser using : a static web server
**Dependencies**
- [nws](https://www.npmjs.org/package/nws)
```sh
npm install -g nws
cd android-project/www
nws
# browse : localhost:3030
# on mobile : %pc_ip_address%:3030
```

## Run in an enhanced browser using : Phonegap Developer App
**Dependencies**
- [PhoneGap Developer App](http://app.phonegap.com/)
- [PhoneGap Developer - Android](https://play.google.com/store/apps/details?id=com.adobe.phonegap.app)
```sh
cd my-android-project-name-here
phonegap serve
# accessible through phonegap app or browser with the given url
```

# Build and apk using : PhoneGap website
- [Adobe PhoneGap Build](https://build.phonegap.com)
Just provide your git and it will create you with a qr code to install the application from

# Build an apk using : PhoneGap tool
**Dependencies**
- [Android SDK | Android Developers](https://developer.android.com/sdk/index.html)
- [Apache Ant - Welcome](http://ant.apache.org/)
