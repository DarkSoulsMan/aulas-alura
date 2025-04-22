# aulas-alura
Códigos básicos dos desafios do começo do curso da alura. 

1- Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas. - V


-------------------------

let BoasV = 'Bem vindo';

console.log(BoasV);

-------------------------


2- Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.


-------------------------



let nome = 'Joao'; // console.log('ola ' +nome)

console.log('ola ' +nome)


-------------------------


3- Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!" 


-------------------------


let nome = 'Joao'; // alert('Olá, ' +nome)

alert('Olá, ' +nome)


-------------------------


4- Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

-------------------------


let quest = prompt('Qual a linguagem de programação que  você mais gosta?');

console.log(quest);

-------------------------


5- Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.



-------------------------



let Valor1 = 10; 

let Valor2 = 8;

let resultado = Valor1 + Valor2;

console.log(`O valor da soma entre o numero ${Valor1} e do numero ${Valor2} será igual a ${resultado}`);



-------------------------




6- Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.


-------------------------



let Valor1 = 10; 

let Valor2 = 8;

let resultado = Valor1 - Valor2;

console.log(`O valor da subtração entre o numero ${Valor1} e do numero ${Valor2} será igual a ${resultado}`);

-------------------------



7- Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.


-------------------------


let idade = prompt('Quantos anos você tem? ');

if(idade > 18){
    console.log('Você é maior de idade, pode entrar no site');


}else{
    console.log('Você não tem idade para entrar nesse site')
}


-------------------------


8 - Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.



Resposta do professor

-------------------------



var numero = parseFloat(prompt("Digite um número:"));


if (numero > 0) {
    console.log("O número é positivo.");
} else if (numero < 0) {
    console.log("O número é negativo.");
} else {
    console.log("O número é zero.");
}



-------------------------



9 - Use um loop while para imprimir os números de 1 a 10 no console.


-------------------------

let contador = 1;

while(contador <= 10){
    console.log(contador);
    contador++;

}

-------------------------


10 - Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.


-------------------------


let nota = prompt('Digite a nota da sua prova')

if(nota >= 7){
    console.log('Aprovado');

}else{
    console.log('Reprovado');

}

--------------------------


11- Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.




Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.


-------------------------


let random = Math.random()

console.log(random);


-------------------------


12- Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.



-------------------------


let random = parseInt(Math.random() *10 + 1);

console.log(random)


-------------------------



13- Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.


-------------------------


let random = parseInt(Math.random() *1000 + 1);

console.log(random)


-------------------------





