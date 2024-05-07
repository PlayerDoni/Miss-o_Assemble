# Missão_Assemble
Sistemas embarcados, práticas de assemble
1° Atividade

``--> Marie.JS (print)
--> Como funciona a alocação de memória dinâmica para armazenar seu nome ?``

# Explicação: 
Este processo requer que você lide diretamente com as funções de baixo nível do sistema operacional, o que dá controle preciso sobre como a memória é utilizada, mas também implica uma responsabilidade maior para garantir que a memória seja gerenciada corretamente. Sem um gerenciamento apropriado, podem ocorrer problemas como vazamentos de memória, onde a memória não é liberada de volta ao sistema, ou corrupção de memória, onde dados inválidos podem ser escritos em locais não autorizados. Por isso, ao trabalhar com alocação dinâmica em assembly, é crucial entender exatamente como os diferentes comandos funcionam e como eles interagem com a arquitetura do sistema operacional específico que você está utilizando.

<img width="819" alt="image" src="https://github.com/PlayerDoni/Missao_Assembly/assets/125417940/3898df81-d284-4f7e-81a4-ab4ef061966e">

# cod:
ORG 000 / Inicia o programa no endereço 000
```Assembly
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
```


# 2 - Explique DOS, masm e tasm em assembly:

# DOS em Assembly: 

`DOS, ou Disk Operating System, foi um dos primeiros sistemas operacionais amplamente usados em computadores pessoais. Escrever programas em assembly para DOS envolve compreender como esse sistema operacional interage com o hardware do computador, especialmente como ele gerencia a memória, os arquivos e os dispositivos de entrada/saída. Ao programar em assembly para DOS, você geralmente utiliza um conjunto de chamadas de interrupção, que são maneiras de solicitar ao sistema operacional que execute certas operações.` 

# MASM em Assembly:
`MASM, que significa Microsoft Macro Assembler, é um assembler desenvolvido pela Microsoft para a família de processadores Intel x86. Ele permite escrever programas em linguagem assembly, que é uma das formas mais próximas de programação diretamente no hardware do computador. MASM é uma ferramenta poderosa para programadores que querem explorar programação em assembly no ambiente Windows, oferecendo uma combinação de controle de baixo nível e ferramentas de desenvolvimento modernas.`

# TASM em Assembly:
`TASM, que significa Turbo Assembler, é um assembler desenvolvido pela Borland que se destaca por sua compatibilidade tanto com a sintaxe do Intel Assembly quanto com a sintaxe idealizada pela Microsoft (usada no MASM). Isso o torna bastante versátil para programadores que desejam trabalhar com diferentes estilos de programação em assembly. TASM é uma ferramenta poderosa e flexível para programação em assembly, valorizada por sua capacidade de alternar entre diferentes estilos de sintaxe e por sua integração em um ambiente de desenvolvimento produtivo.`

