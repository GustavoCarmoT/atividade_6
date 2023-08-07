# atividade_6
// Função para calcular a média geométrica
function calcularMediaGeometrica(valor1, valor2) {
return Math.sqrt(valor1 * valor2);
}
// Função principal para obter os valores e exibir o resultado
function main() {
// Prompt para obter o primeiro valor digitado pelo usuário
const primeiroValor = parseFloat(prompt("Digite o primeiro valor:"));
// Prompt para obter o segundo valor digitado pelo usuário
const segundoValor = parseFloat(prompt("Digite o segundo valor:"));
// Verificar se ambos os valores são números válidos
if (!isNaN(primeiroValor) && !isNaN(segundoValor)) {
// Calcular a média geométrica
const mediaGeometrica = calcularMediaGeometrica(primeiroValor, segundoValor);
// Exibir o resultado
console.log(`A média geométrica de ${primeiroValor} e ${segundoValor} é:
${mediaGeometrica}`);
} else {
console.log("Entrada inválida. Por favor, digite valores numéricos válidos.");
}
}
// Chamar a função principal para iniciar o programa
main();
