# atividadedaAline
TIPOS DE ESTRUTURAS REPETIÇÃO

for_statement - ele faz o laço seja repetido até ser falso;
 SINTAXE:
for ([expressaoInicial]; [condicao]; [incremento]) declaracao

do...while_statement - ele vai repetir até que a condição específica seja falsa, caso não seja ele continuará;
SINTAXE:
do declaracao while (condicao);

while_statement -  ele vai seguir todas as instruções desde que uma instrução específica seja verdadeira;
SINTAXE:
n = 0; 
x = 0; 
while (n < 3) { 
n++;
 x += n; 
}

label_statement - ele identifica um código específico no seu programa;
SINTAXE:
markLoop:
 while (theMark == true) {
 facaAlgo(); 
}

break_statement - ele é usado para terminar os laços; 
SINTAXE:
for (i = 0; i < a.length; i++) { 
if (a[i] == theValue) { break;
  } 
}

continue_statement - ele reinicia o comando do seu programa;
SINTAXE:
i = 0;
 n = 0;
 while (i < 5) {
 i++; if (i == 3) { 
continue;
   } 
n += i;
 }

for...in_statement -  ele executa as interações a partir de uma variável específica;
SINTAXE:
function dump_props(obj, obj_name)
 { var result = " ";
 for (var i in obj)
 { result += obj_name + "." + i + " = " + obj [i] + "<br>"; 
   } 
result += "<hr>"; 
return result; 
}

for...of_statement - ele executa um valor de cada propriedade distinta.
SINTAXE:
let arr = [3, 5, 7];
 arr.foo = "hello"; 
for (let i in arr) { 
console.log(i);
 // logs "0", "1", "2", "foo" } for (let i of arr) {
 console.log(i); // logs "3", "5", "7"
 
 ESTRUTURAS CONDICIONAIS
else - ele serve para executar códigos específicos que sejam true ou false;
SINTAXE:
if ( condicao ) { // códigos que serão // executados caso a // condição seja verdadeira } else // códigos que serão // executados caso a // condição seja falsa }
else if - ele serve para testar uma condição antes de testar o comando;

if ternário - essa é a segunda forma da estrutura if;
SINTAXE:


operador && - ele consegue executar um comando de forma parecida com o if;
SINTAXE:


if - serve para especificar uma linha de código caso seja verdadeira.
SINTAXE:

SWITCHS
Switch - server para avaliar uma instrução, comparando o valor com uma série case.
