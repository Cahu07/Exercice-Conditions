# Exercice-Conditions
// Declare and define three variables using a numerical value

// * If the three variables are equal, display "The three variables are the same" in the console
// * If only two of the variables are equal, display "Two of the variables are the same" in the console
// * If the variables are all different display "all variables are different" in the console

const A = 5
const B = 10
const C = 15


if (A === B && B === C){
    console.log("les trois variables sont identiquess")
}
else if ((A === B || A === C || B === C)){
    console.log("Deux des variables sont identiques")
}
else (console.log("toutes les variables sont différentes"))
