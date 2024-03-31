
LOTOFÁCIL - Sistema de Loteria em Java
Este é um projeto em Java para simular um sistema de loteria chamado LOTOFÁCIL. O sistema é capaz de gerar jogos aleatórios, permitir que os jogadores façam suas apostas, verificar os resultados e calcular prêmios de acordo com as regras da loteria. O sistema funciona por meio do terminal, lendo e escrevendo dados.

Funcionalidades
O sistema oferece as seguintes funcionalidades:

Menu interativo para a loteria, utilizando estruturas switch case e do while.
Três modalidades de aposta: de 0 a 100, de A à Z e em número par ou ímpar.
Geração de números aleatórios para sorteio.
Verificação de resultados e cálculo de prêmios de acordo com as regras estabelecidas.
Como usar
Clone o repositório para sua máquina local:
bash
Copy code
git clone https://github.com/seu-usuario/lotofacil.git
Compile o código Java:
Copy code
javac Lotofacil.java
Execute o programa:
Copy code
java Lotofacil
Siga as instruções exibidas no terminal para fazer suas apostas.
Regras de Negócio/Requisitos
Menu LOTOFÁCIL
markdown
Copy code
**************************
Menu LOTOFÁCIL:
1) Apostar de 0 a 100
2) Apostar de A à Z
3) Apostar em par ou ímpar
0) Sair
**************************
Regras para a aposta de 0 a 100
O jogador deve escolher um número inteiro entre 0 e 100.
Caso o número escolhido seja maior que 100 ou menor que 0, será exibida a mensagem "Aposta inválida.".
O sistema realiza um sorteio aleatório de um número entre 0 e 100.
Se o número escolhido pelo jogador for igual ao número sorteado, ele ganha um prêmio de R$ 1.000,00.
Regras para a aposta de A à Z
O jogador deve escolher uma letra de A à Z.
Caso não seja uma letra, será exibida a mensagem "Aposta inválida.".
O sistema escolhe uma letra premiada (por exemplo, a inicial do nome do desenvolvedor).
Se a letra escolhida pelo jogador for igual à letra premiada, ele ganha um prêmio de R$ 500,00.
Regras para a aposta de número par ou ímpar
O jogador deve escolher um número inteiro.
O sistema verifica se o número escolhido pelo jogador é par ou ímpar.
Se o número digitado for par, ele ganha um prêmio de R$ 100,00.
Caso contrário, será exibida a mensagem "Que pena! O número digitado é ímpar e a premiação foi para números pares.".
Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do repositório, implementar melhorias e enviar um pull request.
