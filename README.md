# Teste-Tecnico-Front-end
Teste técnico realizado para o programa de formação FCamara

1.	Se você tivesse 5 diferentes arquivos de folhas de estilo, qual seria a melhor forma de integrá-los no site?
R:
Utilizaria um automatizador de tarefas para concatenar e evitar retrabalhos visando ganhar tempo e utilizaria o Sass para evitar repetições de seletores e propriedades, deixando o código menor.

2.	Fale 3 formas de diminuir o page load (tempo de carregamento real e percebido).
R:
- Reduzindo o peso das imagens.
- Criando arquivos separados (estilos e scripts) e carregando-os na página HTML.
- Reduzindo o máximo possível o tamanho dos arquivos (utilizando frameworks e bibliotecas, visando diminuir a quantidade de linhas de código).

3.	Quais ferramentas você usa para testar a performance do seu código?
R:
JMeter.

4.	Considere o HTML5 como uma plataforma web aberta. Quais são os blocos de construção de HTML5?
R:
header, footer, nav, aside, article e section.

5.	Você pode explicar a diferença entre GET e POST?
R:
A Visibilidade: a requisição GET é enviada como string anexada a URL, já a requisição POST é encapsulada ao corpo da requisição e não pode ser vista.

6.	Liste quantas propriedades display você puder lembrar.
R:
inline, linline-block, block, none e flex.

7.	Qual a diferença entre inline e inline-block?
R:
inline ocupa somente o espaço que for necessário para sua exibição, não podendo ser definido height ou width nem padding ou margin. Já o inline-block aceita que os atributos sejam definidos.

8.	Qual a diferença entre elementos posicionados de forma relativa, fixa, absoluta e estática?
R:
relativa – se usarmos com as propriedades: top, right, bottom e left, podemos movimentar o bloco da posição inicial de acordo com as declarações das propriedades citadas e ela preserva o espaço em que ocupava.
fixa – o bloco fica posicionado fixamente na tela quando é feito a rolagem na página. 
absoluta – retira o elemento da posição original, fazendo com que o elemento seguinte ocupe o lugar deixado pelo mesmo.
estática – valor padrão do posicionamento. Sobrescreve o posicionamento declarado no elemento anterior.

9.	Qual a diferença entre .call e .apply?
R:
.call – utiliza o this como primeiro parâmetro e os próximos são os parâmetros da função.
.apply – invoca uma função com o this e um array com os parâmetros da função.

10.	Qual a diferença entre == e ===?
R:
== compara somente o valor. 
=== compara o valor e tipo. 
Ex:
 “1” == 1; // true. 
“1” === 1; // false.
