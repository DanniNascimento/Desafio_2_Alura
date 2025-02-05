# Resolução dos desafios do curso de lógica de programação

Praticar a lógica de programação, incluindo conceitos como variáveis, condicionais (if-else), loops (while) e interações com o usuário (alert, prompt), é essencial para sua carreira de desenvolvimento de software. Esses fundamentos fornecem a base para resolver problemas de forma estruturada, tomar decisões no código, criar iterações controladas e interagir eficazmente com os usuários. 

Compreender esses conceitos não apenas facilita o aprendizado de novas linguagens e tecnologias, mas também capacita você a criar soluções inovadoras, depurar eficientemente e manter a qualidade ao longo do ciclo de vida do software. Portanto, investir tempo nesses princípios desde cedo é fundamental para construir uma base sólida e bem-sucedida no campo da programação.

#### Desafios - Respostas

1) Pergunte ao usuário qual é o dia da semana. Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". Caso contrário, mostre "Boa semana!".

```js
let diaDaSemana = prompt("Qual é o dia da semana?");

if (diaDaSemana === "Sábado" || diaDaSemana === "Domingo") {
    alert("Bom fim de semana!");
} else {
    alert("Boa semana!");
}

```
Por que usar ===?
Precisão: Garante que tanto o valor quanto o tipo dos operandos sejam exatamente iguais, evitando comparações inesperadas.
Prevenção de Erros: Reduz a chance de erros que podem surgir devido a conversões automáticas de tipo.
Melhor Prática: É considerado uma boa prática para evitar problemas que podem ser difíceis de depurar.

Exemplo prático
Vamos observar o exemplo de um sistema de login:

```js
let senhaDoSistema = "senhaTeste!";

let senha = prompt("Digite a senha do sistema:");

if (senha === senhaDoSistema) {
    alert("Acesso ao sistema garantido");
} else {
    alert("Senha incorreta. Acesso negado.");
}

```
Aqui, senha e senhaDoSistema são comparados usando === para garantir que tanto o valor quanto o tipo sejam exatamente iguais. Isso evita casos onde, por exemplo, senha poderia ser convertida para um tipo diferente antes da comparação, resultando em uma validação incorreta.

Usar === garante que a comparação seja precisa e comporta-se como esperado, evitando potenciais problemas de lógica no código.

```
2) Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.

```js
let numero = prompt("Digite um número:");

if (numero > 0) {
    alert("O número é positivo.");
} else if (numero < 0) {
    alert("O número é negativo.");
} else {
    alert("O número é zero.");
}

```

3) Crie um sistema de pontuação para um jogo. Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!" no console do navegador. Caso contrário, mostre "Tente novamente para ganhar.".

```js
let pontuacao = prompt("Digite sua pontuação:");

if (pontuacao >= 100) {
    alert("Parabéns, você venceu!");
} else {
    alert("Tente novamente para ganhar.");
}

```

4) Crie uma mensagem que informa o usuário sobre o saldo da conta, usando uma template string para incluir o valor do saldo.

```js
let saldo = prompt("Qual é o seu saldo?");
alert(`Seu saldo atual é de R$${saldo}.`);

```

5) Peça ao usuário para inserir seu nome usando prompt. Em seguida, mostre um alerta de boas-vindas usando esse nome.

```js
let nome = prompt("Digite seu nome:");
alert(`Bem-vindo, ${nome}!`);

```
