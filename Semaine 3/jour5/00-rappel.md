

```js

function traitement(){}
let duree = 100 ; // durée e, millisecondes

//executer la fonction traitement toutes les 1 seconde (a l'infini)
let interva = setInterval(traitement , duree)

//opération inverse
clearInterval(interval)
```

# système d'onglet

```html
<button>Action</button>
<button>Action</button>
<div></div>
<div></div>
```

````js
let button = document.querySelectorAll("button");
let div = document.querySelectorAll("div");

//evenement => addEventListener

function effet (e)
//le parametre e permet d'avoir des infos sur l'action que l'on vint de déclancher
{
    let index = e.target.dataset.index
    //faire l'effet escompté
}

fot(let i = 0 ; i < button.length ; i = i + 1){
    button[i].addEvntListener("click" , effet )
}
```