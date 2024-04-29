const readline= require("readline-sync")
let op; 
let nome=""
let sobrenome=""
let numero =""
let endereço=""

let clientes = [];

do {
    

console.clear()
console.log("=========================");
console.log("|\tMENU\t\t|");
console.log("=========================");
console.log("|\t\t\t|");
console.log("|01.AGENDAR\t\t|");
console.log("|02.TELA DE CLIENTES   \t| ");
console.log("|03.AGENDAMENTO\t\t|");
console.log("=========================");

// cadastrar um novo cliente FUNÇÃO






switch (op) {
    case 1: 
    let cliente = {
        nome: nomeInput
        idade:idadeInput
        endereço:endereçoInput
        numero:numeroInput
    }
    clientes.push(cliente);
    let idadeInput = readline.question("digite sua Idade: ").toUpperCase
    let nomeInput = readline.question("digite seu Nome: ").toUpperCase
    let endereçoInput = readline.question("digite seu endereço: ").toUpperCase
    let numeroInput = readline.questionInt("digite seu Numero: ")

        break;
    case 2:

        
        console.log(clientes);
       
       
        break;
    case 3:
       
        break;

    default:
        break;
}








