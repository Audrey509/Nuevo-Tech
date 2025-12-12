# Fonction
'''''js

// Fonction

// Définition

// Une variable permet de stocker une ou plusieur valeurs
// Une fonction permet de stoxker un ou plusieur traitements

let a = 2;

function b(){
    let a = 10;
    let b = 30;
    let c = a + b;
    if(){}
    for(){}
    console.log();
}

// on veut exécuté les traitement stocké da,s une fonction
// il faut APPELER / EXECUTER cette fonction

b(); // EXECUTION

// Quand on a besoin d'une fonction dont les traitements sont les meme MAIS les valeurs
   à porter à ces traitements sont différents => remplacer les variables dans les 
   fonction PAR des PARAMETRES

 function c(a,b){
    // let a = 10;
    // let b = 30;
    let c = a + b;
 }

c(33 , 55);
c(52 , 24);

//return mot clé que l'on trouve dans une fonction
//a quoi sa sert ??

function creer_profil_etudiant ( prenom , nom , age ){
    let profil = prenom + " " + nom + " " + age
    // prenom = "Alain"
    // nom = "Dupont"
    // age = 22
    // profil = "Alain Dupont 22"

    // la variable profil est LOCAL
    return profil;
    // pouvoir récupérer la valeur stockée dans la variable local profil à 
    l'exterieur de la fonction
}

profil // ERREUR variable INCONNUE ??

let etudiant1 = creer_profil_etudiant("alain" , "DUPONT" , 22);

'''