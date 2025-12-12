# git

-logiciel qui permet de versionner ton code 
-garder plusieur version de ton code => plusieurs photo de ton code au fur a mesure du temps

-installer git : sur ton ordinateur
   <https://git-scm.com/install/windows>
   -restart visual
   -lancer un terminal
   -git --version

-parametré git : donner ton nom et ton email

```sh
git config --global user.name "Audrey B"
git config --global user.email "audreybenjamin26@gmail.com"

git config --list
```

# créer un repository local

```sh
# sa permet de créé un repository local(dossier qui contient la versionning)
git init
# permetde valider une liste de fichier avant enregistrement dans le repository
git add
#action d'enregistrement les fichier validée
git commit -m "description"
```

# mettre en ligne notre travail : sur github

-se créé un projet sur github.com
-cree un repository sur github (repository distant)


```sh
git remote add origin....
git push origin main
```


# dans le repository distant activé une option 

activer l'option "github pages"

