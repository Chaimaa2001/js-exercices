# js-exercices
-----------KAINE CHAIMAA------------
EXERCICE DUR LES FONCTIONS
Solutions des exercices JavaScript
exercice3-----
let chaine="abcad";
let l="a"
function nombre_occ(chaine,l)
{
    let r=0;
    for(let i=0;i<chaine.length;i++)
    {
        if(chaine[i]==l)
        {
                r++;
        }
    }
    return r;
}
console.log(nombre_occ(chaine,l));
exercice4----------------
let chaine1="abacddec"
function lettre_non_repeted(chaine1)
{
    
    for(let i=0;i<chaine1.length;i++)
    {
        r=0;
        for( let j=0;j<chaine1.lettre_non_repeted;j++)
        {
            if(chaine1[i]!=chaine1[j] )
            {
                if(r!=chaine1.length)
                {
                    r++;
                    continue;
                }
                else
                {
                    return i;
                }
                 
            }
            else
            {
                break;
            }
           
        }

    }
}
console.log(lettre_non_repeted(chaine1));
