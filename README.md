Introdução ao Teste Unitário

Prof. Bernardo Copstein

Você pode resolver os três exercícios que seguem acrescentando essas classes no mesmo projeto que vinha sendo trabalhado até então ou criar outro. Como são apenas classes soltas e os respectivos drivers de teste, não há inconveniente em usar o mesmo projeto.

1) Considere a classe “RomanNumeral” que segue. Ela possui um único método chamado “convert” capaz de conter numerais romanos em seu equivalente decimal. Escreva um driver de teste que você julgue testar adequadamente esta classe.

2) A classe “Calculator” tem um método chamado “evaluate” que recebe por parâmetro uma string com um somatório de inteiros no formato “[inteiro] + [inteiro] + ... + [inteiro]” (inteiro = inteiro positivo). Ex: “54 + 22 + 32 + 4 + 105 + 2”. O método retorna o valor do somatório. Escreva e implemente um driver de testes capaz de testar adequadamente esta classe.

3) Uma indústria de chocolate tem de despachar para seus clientes pacotes com diferentes pesos. As barras são produzidas com dois pesos: 1Kg e 5Kg. Precisa-se saber quantas barras de cada peso deve-se enviar para cada cliente sabendo que a prioridade é enviar barras de 5Kg. A classe “Encomenda” que segue possui um método chamado “qtdadeBarras”. Este recebe por parâmetro à quantidade de barras de 1Kg e 5Kg disponíveis no estoque da indústria e a quantidade encomendada pelo cliente. O método retorna um arranjo com duas posições indicando, respectivamente, a quantidade de barras de 1 e 5 Kg que devem ser usadas para atender a encomenda. Caso as barras disponíveis no estoque não sejam suficientes para atender a encomenda o método deve retornar “null”. O “esqueleto da classe’ pode ser visto abaixo. Implemente um driver de teste capaz de testar a classe adequadamente. Em seguida implemente a classe e verifique a qualidade de sua implementação.

Exemplo 1:
A chamada: e.qtdadeBarras(10,5,23) deve retornar [3,4], ou seja, sabendo que temos 10 barras de 1Kg e 5 barras de 5kg no estoque, quantas barras de cada devem ser usadas para atender uma encomenda de 23 kg? Retorno: 3 barras de um Kg e 4 barras de 5Kg.

Exemplo 2:
A chamada: e.qtdadeBarras(10,3,23) deve retornar [8,3], ou seja, sabendo que temos 10 barras de 1Kg e 3 barras de 5kg no estoque, quantas barras de cada devem ser usadas para atender uma encomenda de 23 kg? Retorno: 8 barras de um Kg e 3 barras de 5Kg.

4) Especificação do problema: Uma barca de passageiros tem 1200 lugares organizados
em 60 fileiras de 20 lugares cada. O sistema de controle de lugares deve controlar tanto
a ocupação dos lugares como a distribuição de peso na barca. Desta forma quando o
cliente chega para embarcar ele escolhe um lugar e o sistema deve dizer se o lugar está
ocupado ou se ele não pode se sentar ali em função da distribuição de peso. As regras
de distribuição de peso são as seguintes:
• Os primeiros 100 passageiros só podem se sentar nas fileiras de 1 a 20.
• Os próximos 100 passageiros só podem se sentar nas fileiras de 40 a 60.
• Os demais passageiros podem sentar-se em qualquer lugar livre.
Os lugares são identificados da seguinte forma: F<nro da fileira>A<nro do assento>. A
numeração das fileiras e lugares inicia em 1.
Exemplos: F02A12, F45A01, F33A18

7) 7. O valor da multa por excesso de velocidade varia conforme o tempo de habilitação do motorista. Motoristas mais experientes pagam mais caro. O limite de velocidade é de 80Km/h. Motoristas que forem pegos em velocidades entre 80km/h e 120km/hora pagam multa de R$ 250,00. Acima de 120Km/h o valor é de R$ 500,00. Esses valores são válidos para motoristas com até 5 anos de habilitação. Entre 5 e 10 anos de habilitação o valor é acrescido de 40% e acima disso o valor das multas dobra. Escreva um conjunto de casos de teste para testar a implementação desta lógica sabendo que as variáveis de entrada são a velocidade identificada e o tempo de habilitação do motorista.
