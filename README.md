# Carrinho_De_Controle_Remoto
Utilização de um Arduino Uno para um acionamento coordenado de 2 motores C.C. Possibilitando a condução do modelo de "Carrinho"
Este Modelo, simula operações simples de um carrinho de controle remoto(acelerar, freiar, fazer curvas e dar ré)

# Lista de materiais

* 1 Arduino UNO

* 1 Kit Chassi Acrílico de Carro com 2 motores C.C.

* 1 Módulo Ponte H para Arduino - para 2 motores C.C. 12V

* 1 Módulo Joystick para Arduino

* 1 Protoboard Pequena

* 1 Conector para Bateria 9V para Arduino

* 1 Interruptor

* Fios e Conectores Dupont (Macho e Fêmea)

* 3 Pilhas 12V

* 3 Suportes para pilhas

* 1 Bateria 9V

# Diagrama.
![diagrama1](https://user-images.githubusercontent.com/53185153/68629957-74ecd280-04c4-11ea-9428-079934a6a1a1.png)
 
# Montando o Projeto.
Montamos o chassi do carrinho 2wd e acoplamos os motores DC 6V ao mesmo soldando os contatos. 
conectamos os motores à ponte H e conectamos a fonte de 12V nos bornes correspondentes da mesma atraves de um interruptor, sendo esta fonte uma fonte DC de 3 pilhas de 12V em paralelo. 
acoplamos o arduino ao chassi do carrinho e realizamos as conexoes do joystick no arduino de acordo com diagrama do fritzling
conectamos as 4 conexoes pwm do as da ponte H de acordo com o diagrama e aterramos o arduino e a ponte mutuamente. 
alimentamos o arduino com uma fonte DC de 9V e em seguida 

# Como usar.
O uso do carrinho é bem simples. Todas os comandos que ele recebe vem do módulo joystick para arduino, bastando fazer simples movimentos intuitivos. Movendo para frente ele acelera, para trás ele realiza a ré, movimentando para os lados ele realiza curvas tanto para esquerda quanto para a direita. Por fim, para acionar o modo freio, basta precionar o joystick, repetir este mesmo movimento desativa o modo freio.

# Por que Montar o carrinho?
Este trabalho tem como objetivo exemplificar o uso do arduino no lazer e na aprendizagem de crianças e adolescentes ao passo que promove ensina conceitos básicos de materias importantes para o desenvolvimento do jovem no âmbito escolar tais como conceitos fisicos, matemáticos, aplicação do uso de lógica de computação simples e desenvolvimento da coordenação motora através da montagem além da satisfação e lazer com o produto final do trabalho. O processo de automatização para o carrinho vem como medida de segurança nas operações, por exemplo, uso de sensores que ativam a frenagem do carrinho, evitando acidentes.

# Dificuldades do projeto
A realização desse projeto, infelizmente teve seu tempo muito reduzido, por conta do curto prazo de entrega do carrinho, somado com a demora da entrega dos materias.
Como consequência, muitas implementações foram deixadas de lado, como a implementação de sensores para a automatização do carrinho, o módulo de radiofrequência que possibilitaria o controle a distância.
Vale pontuar que esse não é o primeiro projeto proposto. Por razões externas, essa atividade foi na verdade a terceira escolhida pelo grupo. Os outros dois projetos tiveram que ser deixados de lado, reduzindo ainda mais o tempo para deixar o trabalho completo.


