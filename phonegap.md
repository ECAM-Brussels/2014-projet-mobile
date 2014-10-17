# N.B. 
- Toutes les commandes qui suivent sont à introduire dans un terminal
- Familiariser vous avec les commandes de bases de ceux-ci
```sh
pwd
ls
cd
mkdir
rm
mv
cp
```
- Ou les équivalents windows

# Installer Node.Js
- http://www.nodejs.org
- Ceci installe la commande npm
- Vérifier qu'elle soit accessible depuis tout terminal

#  Installer PhoneGap
```sh
npm install -g phonegap
```
- Ceci installe phone gap globalement (-g)

# Usage de PhoneGap
```sh
phonegap --help
```
- cette commande liste les options de phonegap

# Créer une application PhoneGap
```sh
phonegap create $NOM_APPLICATION
```
- Ceci crée l'aroborescence suivante : 
```
└───$NOM_APPLICATION
    ├───.cordova
    ├───hooksk
    ├───platforms
    ├───plugins
    └───www
        ├───index.html
        ├───css
        ├───img
        ├───js
        ├───res
        │   ├───icon
        │   │   ├───android
        │   │   └───...        
        │   └───screen
        │       ├───android
        │       └───...
        └───spec
            └───lib
                └───jasmine-1.2.0
```
- Qui correspond à une application helloworld type
- En modifiant  index.html vous pouvez déjà custommiser votre Hello World
