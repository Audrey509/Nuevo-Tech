 # '''js

# Tableau

let notes = [ 1, 2, 5, 6, 10];

# Traitement sur les tableaux

# Comment récupérer une valeur de tableau

notes[2];
notes[4];


# Récupéré totes les valeurs d'un tableau
for(let i = 0 ; i < 5 ; i = i + 1){
    console.log(notes[1]);            ²              
}

# //////////////////////////////////////

for(let i = 0 ; i < notes.length ; i = i + 1){
    console.log(notes[1]);            ²              
}

#  Objet

        let auto = {
            marque : "peugoet" ,
            prix : 5000
        };

        let auto2 = {
            marque : "VW" ,
            prix : 6000
        };


        auto.prix ;// 5000
        auto2.marque;//peugeot

       //j'ai acheté une peugeot a 5000 euros

       let phrase = "J'ai acheté une " + auto.marque + " à " + auto2.prix + " euros ";

       console.log(phrase);


        let phrase = {
            auteur : "Victor" ,
            contenu : "bonjour!" ,
            ecrire : function(){ 
                let synthese = this.auteur + "a ecrit" +  this.contenu;
                console.log(synthese);
            }
        };

        phrase.ecrire();

# DOM

# Document Objet Model

// javascript va créer une variable qui s'appelle
document
// objet qui est crée automatiquement par javascript qui contient TOUTES les balise html de la page
// grace a cet objet que l'on peut modifier la page web

//selectionne toutes les balise p
let p = document.querySelectorAll("p")
p[0]
p[1]

//traitement sur les balises selectionnées

p[0].innertText = "....";
p[0].style["color"] = "blue";
p[0].innerHTML = "text <h1>toto</h1>"



let p = document.querySelector("p")//selectionner le 1er p dans la page






# ,,,,,,,,,,,,,