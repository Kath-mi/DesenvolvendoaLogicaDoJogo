# DesenvolvendoaLogicaDoJogo

Nivel Novato:
Para implementar o jogo de comparação de cartas de Super Trunfo conforme os requisitos descritos, vamos seguir os seguintes passos:

Cadastro das Cartas: As cartas devem ter informações como o nome da cidade, estado, código da carta, população, área, PIB, número de pontos turísticos, densidade populacional e PIB per capita.

Cálculo dos Atributos:

Densidade Populacional: População / Área

PIB per capita: PIB / População

Comparação de Atributos:

Para os atributos População, Área, PIB e PIB per capita, a carta com o maior valor vence.

Para o atributo Densidade Populacional, a carta com o menor valor vence.

Estrutura de Decisão: Usaremos if e if-else para comparar os valores das cartas e determinar a vencedora.

Nivél Aventureiro:

Neste desafio, você vai melhorar ainda mais o Super Trunfo, agora incluindo um menu interativo que permitirá ao usuário escolher qual atributo será utilizado para comparar as cartas de dois países. Além disso, você deverá implementar uma lógica de comparação mais complexa, utilizando if-else aninhados e a regra específica para a Densidade Demográfica, onde a carta com o menor valor vence, ao contrário dos outros atributos.

Nível Mestre:

Neste desafio final, você irá criar uma lógica de comparação mais avançada, onde o jogador pode escolher dois atributos diferentes para comparar duas cartas. A comparação será feita com base nesses dois atributos, e a soma dos resultados determinará a carta vencedora. Caso haja empate, a mensagem de empate será exibida.

Objetivos:
Escolha de dois atributos: O jogador deve escolher dois atributos numéricos diferentes para a comparação.

Comparação com múltiplos atributos: A carta com o maior valor para cada atributo vence, mas a Densidade Demográfica segue a regra inversa (menor valor vence).

Soma dos Atributos: Após comparar os dois atributos, somar os valores de cada carta e determinar o vencedor com base na soma.

Empate: Caso as somas sejam iguais, exibir a mensagem de empate.

Menus Dinâmicos: O menu de escolha de atributos deve ser dinâmico, ou seja, o atributo selecionado pelo jogador no primeiro menu não deve aparecer no segundo menu.
