# git

# logiciel qui permet de versionner ton code 
# garder plusieur version de ton code => plusieurs photo de ton code au fur a mesure du temps

# installer git : sur ton ordinateur
   <https://git-scm.com/install/windows>
   -restart visual
   -lancer un terminal
   -git --version

# parametré git : donner ton nom et ton email

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
git add .
#action d'enregistrement les fichier validée
git commit -m "description"
```

# mettre en ligne notre travail : sur github

-se créé un projet sur github.com
-cree un repository sur github (repository distant)


```sh
git remote add origin https://github.com/Audrey509/Nuevo-Tech.git
git push -u origin main
```


# dans le repository distant activé une option 

activer l'option "github pages"

Attention por retrouver la bonne adress

<http://127.0.0.1:5500/Semaine%204/jour4/04-exo.html>

# je veux modifier un fichier et le mettre en ligne

1. modifier ton fichier dans Visual Studio Code
2. enregistrer le fichier avec CTRL + s
3. realiser les commandes suivantes

```sh
# prendre le fichier modifié et le push sur github

git add .
git commit -m "modification menu"
git push
```

4. reafrechir la page html dans ton navigateur 
5. Attention il faut vider le cache navigateur pour le mise a jour soit visible


