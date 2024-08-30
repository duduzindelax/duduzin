Calculadora de Média Aritmética
Este projeto é uma calculadora simples para calcular a média aritmética de quatro números inseridos pelo usuário. A aplicação utiliza HTML, CSS e JavaScript para criar uma interface interativa e responsiva. A seguir está uma breve explicação sobre cada parte do código:

HTML
O HTML estrutura a página e define os elementos básicos necessários:

<input>: Campos de entrada para o usuário digitar quatro números. Cada campo é identificado por um ID único para facilitar a manipulação com JavaScript.
<button>: Um botão que, ao ser clicado, aciona a função de cálculo da média.
<div id="resultado">: Uma área onde o resultado da média será exibido.
CSS
O CSS fornece o estilo e o layout da página:

body: Estiliza a página com uma fonte padrão e um fundo suave, centralizando o conteúdo com Flexbox.
.container: Define o estilo do contêiner principal, incluindo fundo branco, bordas arredondadas e sombra para criar um efeito de elevação.
input: Estiliza os campos de entrada com bordas arredondadas e um efeito de foco que melhora a visibilidade.
button: Adiciona estilo ao botão, incluindo cores, bordas arredondadas e efeitos de transição ao passar o mouse.
.result: Define o estilo da área onde o resultado é exibido.
JavaScript
O JavaScript lida com a lógica e interatividade da página:

calcularMedia(): Função principal que:
Obtém os valores dos campos de entrada e os converte para números decimais.
Verifica se todos os valores são válidos e exibe um alerta se algum não for.
Calcula a média dos quatro números.
Exibe o resultado na página com duas casas decimais.
