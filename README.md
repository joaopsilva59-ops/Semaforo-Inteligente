- Nome do projeto: knowflow-Semafaro-Iteligente
- 
- Nome do desenvolvedor: João Pedro Baltazar Silva

- Curso: Técnico em Desenvolvimento de Sistemas
- 
- Objetivo do projeto: Desenvolver um sistema de semáforo inteligente capaz de controlar o fluxo de veículos de forma automatizada, podendo simular tempos de abertura e fechamento com base em regras pré-definidas.
- 
- Linguagem utilizada: C
- 
- Descrição resumida do funcionamento: O programa simula o funcionamento de um semáforo, alternando entre os estados:
- Verde (libera passagem)
- Amarelo (atenção)
- Vermelho (parada)
- Os tempos de cada estado são controlados por estruturas de repetição e funções, permitindo a simulação contínua do sistema.

- Como executar o programa, quando houver código:
Compile o código com um compilador C (GCC):

gcc main.c -o semaforo

Execute o programa:

./semaforo
O semáforo será exibido no terminal em funcionamento contínuo.

Estrutura do repositório

semaforo-inteligente/
│
├── README.md
├── main.c
├── Docs/
│   └── Documentacao-JoaoPedroBaltazarSilva.docx
└── Evidencias/
    └── prints/

    main.c (pra acompanhar o README)
    
    #include <stdio.h>
#include <unistd.h>

int main() {
    while (1) {
        printf(" VERDE - Siga\n");
        sleep(5);

        printf(" AMARELO - Atenção\n");
        sleep(2);

        printf(" VERMELHO - Pare\n");
        sleep(5);
    }

    return 0;
}
