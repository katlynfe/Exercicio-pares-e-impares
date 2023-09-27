/*
Exercício que tem entrada de números dados pela pessoa e separa em pares e ímpares. Além disso, realiza a soma dos pares e dos ímpares.
*/



const prompt = require('prompt-sync')()


let continuar
let pares = []
let impares = []

do {
    console.clear()
    valor = Number(prompt("Digite um valor qualquer: ")
)
    if (valor % 2 == 0){
        pares[pares.length] = valor
    } else {
        impares[impares.length] = valor
    }

    continuar = prompt("Deseja continuar [s] ou [n]: ")
} while (continuar.toLocaleLowerCase() == 's');

console.log("Pares digitados: " +pares)
console.log("Impares digitados: " +impares)


// soma dos pares

let somaPares = 0
for (let indice = 0; indice < pares.length; indice++) {
    somaPares += pares[indice]    
}

console.log("Soma dos pares: " +somaPares)


let somaImpares = 0
for (let indice = 0; indice < impares.length; indice++) {
    somaImpares += impares[indice]    
}

console.log("Soma dos impares: " +somaImpares)
