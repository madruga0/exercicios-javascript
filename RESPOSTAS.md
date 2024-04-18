// 1.1
let arr = [1, 2, 3];

for (let i = 0; i < arr.length; i++) {
console.log(arr[i]);
}

// 1.2
var n1 = prompt("Digite o número 1");
var n2 = prompt("Digite o número 2");
var n3 = prompt("Digite o número 3");

console.log(n1);
console.log(n2);
console.log(n3);

//1.3
let number1 = Number(prompt("Digite number 1"));
let number2 = Number(prompt("Digite number 2"));
let number3 = Number(prompt("Digite number 3"));

let soma = number1 + number2 + number3;
let media = soma / 3;

console.log("A média é " + media);

// 1.4
let Fah = Number(prompt("Qual a temperatura atual em FAHRENHEIT?"));

let Cel = ((Fah - 32) * 5) / 9;

console.log("A temperatura em CELSIUS é de: " + Cel + " graus");

// 2.1
let num = Number(prompt("Digite o primeiro número"));
let num2 = Number(prompt("Digite o segundo número"));

const add = num + num2;

if (add > 100) {
console.log(O número ${add} é maior do que 100);
} else {
console.log("undefined");
}

// 2.2
const personagemMorreu = (dano, saude) => {
let novaSaude = saude - dano;

if (novaSaude <= 0) {
return 1;
} else {
return 0;
}
};
console.log(personagemMorreu(1, 10));

// 2.3
function limitaPosicao(posicao) {
return Math.min(100, Math.max(0, posicao));
}
console.log(limitaPosicao(47));

// 4.1
const number = parseInt(prompt("Digite um número inteiro"));

for (let i = 1; i <= 10; i++) {
let resultado = i * number;
console.log(${number}*${i} = ${resultado});
}

// 5.0
const vetor = [14, 58, 20, 77, 66, 82, 42, 67, 42, 4];

vetor.sort((a, b) => a - b);

for (let i = 0; i < vetor.length; i++) {
console.log(vetor[i]);
}
``
