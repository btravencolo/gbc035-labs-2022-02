# Ex01 
As figurinhas da copa do mundo são compostas pelas seguintes informações sobre os jogadores: Nome do Jogador, Data de Nascimento, Altura, Peso, Posição, País.

Crie uma classe Figurinha, que conterá todas as informações das figurinhas.

Em uma outra classe (outro código Java), instancie 3 objetos, com informações de seus jogadores de preferência. Faça atribuição de valores no próprio código e mostre as informações na tela.

# Ex02
Crie um novo projeto, semelhante ao exercício anterior. Torne todas os atributos do exercício 1 privados. Crie métodos para alterar os valores dos atributos e para mostrar os valores dos atributos na tela. Instancie os mesmos três jogadores.

# Ex03
Crie no programa principal um vetor de figurinhas e instancie os jogadores de sua preferência. Mostre as informações de todos os jogadores. Utilize laços para manipulação do vetor.

# Ex04
Crie uma nova classe chamada Selecao, que é composta pelo nome da seleção, por 11 jogadores titulares, o nome do técnico, e outras informações que julgar pertinente. Instancie 2 seleções.

# Ex05
Crie um novo projeto copiando os códigos anteriores da Figurinha e da Seleção. Modifique o código para incluir construtores nas classes. No caso da Figurinha, o construtor vai receber como parâmetro somente o país. Os demais atributos poderão ser inicializados com valores padrões do Java ou outro valor que achar pertinente.

Para o construtor da Selecao, ele deverá receber o nome da seleção e o nome do técnico. O construtor deverá então já criar o vetor dos 11 jogadores e instanciar cada posição, chamando para isso o construtor da Figurinha que permite criar os objetos com o parâmetro do país (que é o mesmo país que foi passado ao construtor da seleção.)