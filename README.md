# Miss-o_Assemble
Sistemas embarcados, práticas de assemble
1° Atividade

--> Marie.JS (print)
--> Como funciona a alocação de memória dinâmica para armazenar seu nome

<img width="819" alt="image" src="https://github.com/PlayerDoni/Missao_Assembly/assets/125417940/3898df81-d284-4f7e-81a4-ab4ef061966e">

cod:
ORG 000 / Inicia o programa no endereço 000

Load D
Store NAME_D /tag
Load O
Store NAME_O
Load N
Store NAME_N
Load O2
Store NAME_O2
Load V
Store NAME_V
Load A
Store NAME_A
Load N2
Store NAME_N2

Halt / Termina execução

/Tabela ASCII
D,HEX 44
O,HEX 4f
N,HEX 4e
O2,HEX 4f2
V,HEX 56
A,HEX 41
N2,HEX 4e

/Reservar o espaço para o Nome 'Donovan'
NAME_D, HEX 0
NAME_O, HEX 0
NAME_N, HEX 0
NAME_O2, HEX 0
NAME_V, HEX 0
NAME_A, HEX 0
NAME_N2, HEX 0
