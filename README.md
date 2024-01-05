# calculadora- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> <link rel="stylesheet" href="js.js">
</head>
<body>
    <script>       
        var operacao = prompt("Escolha o tipo de operação matemática:\n1 - Soma\n2 - Subtração\n3 - Multiplicação\n4 - Divisão");
operacao = parseInt(operacao);

var num1 = parseFloat(prompt("Digite o primeiro número:"));
var num2 = parseFloat(prompt("Digite o segundo número:"));

var resultado;

switch (operacao) {
    case 1:
        resultado = num1 + num2;
        break;
    case 2:
        resultado = num1 - num2;
        break;
    case 3:
        resultado = num1 * num2;
        break;
    case 4:
        resultado = num1 / num2;
        break;
    default:
        alert("Escolha de operação inválida.");
}

if (resultado !== undefined) {
    alert("O resultado da operação é: " + resultado);
}
    </script>
</body>
</html>
