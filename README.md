### **Mario Kart.JS**

![header.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/b49205d5-4f32-4459-80b2-d0044aba22a4/header.gif)

**Objetivo:**

Mario Kart é uma série de jogos de corrida desenvolvida e publicada pela Nintendo. Nosso desafio será criar uma lógica de um jogo de vídeo game para simular corridas de Mario Kart, levando em consideração as regras e mecânicas abaixo.

**Players**

Mario: 

![mario.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/80b65d50-96eb-43ba-ac9d-b9e16bd3d704/mario.gif)

Velocidade: 4

Manobrabilidade: 3

Poder: 3

Bowser: 

![bowser.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/12506d0e-59ef-4f7e-88dd-c1639ed327f4/bowser.gif)

Velocidade: 5

Manobrabilidade: 2

Poder: 5

Peach:

![peach.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/fc77f4b4-8d53-4726-9ad0-17a53152f8d0/peach.gif)

Velocidade: 3

Manobrabilidade: 4

Poder: 2

Luigi: 

![luigi.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/d39c992b-aa55-409e-9440-46809eb4b990/luigi.gif)

Velocidade: 3

Manobrabilidade: 4

Poder: 4

Yoshi: 

![yoshi.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/1041147c-274f-43db-a07e-51480c1633d8/yoshi.gif)

Velocidade: 2

Manobrabilidade: 4

Poder: 3

Donkey Kong: 

![dk.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/a15c0f8b-757f-467d-be6a-39fa0c84b8cf/dk.gif)

Velocidade: 2

Manobrabilidade: 2

Poder: 5

**🕹️ Regras & mecânicas:**

**Jogadores:**

O Computador deve receber dois personagens para disputar a corrida em um objeto cada

**Pistas:**

- Os personagens irão correr em uma pista aleatória de 5 rodadas
- A cada rodada, será sorteado um bloco da pista que pode ser uma reta, curva ou confronto
    - Caso o bloco da pista seja uma RETA, o jogador deve jogar um dado de 6 lados e somar o atributo VELOCIDADE, quem vencer ganha um ponto
    - Caso o bloco da pista seja uma CURVA, o jogador deve jogar um dado de 6 lados e somar o atributo MANOBRABILIDADE, quem vencer ganha um ponto
    - Caso o bloco da pista seja um CONFRONTO, o jogador deve jogar um dado de 6 lados e somar o atributo PODER, quem perder, perde um ponto
    - Nenhum jogador pode ter pontuação negativa (valores abaixo de 0)

**Condição de vitória:**

Ao final, vence quem acumulou mais pontos

![Captura de tela 2024-08-02 030934.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/0f486f4f-3aa4-4184-86ae-03ef4c1d8ba8/5f23b633-73af-4750-a24e-70ba64c49efd/Captura_de_tela_2024-08-02_030934.png)
