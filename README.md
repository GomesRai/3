# 3

#include <stdio.h>
#define vr 50

char nome[vr];
int op;

void cadastro();

int main(void) {
    cadastro();
    return 0;
}

void cadastro() {
    static int linha;
    int continuar;
    int nota;
    do {
        printf("Digite o nome: ");
        scanf("%s", &nome[linha]);
        printf("Voce gostou desse tema? 100 Anos da Semana de Arte Moderna (Digite 1 para sim ou 2 para nao): ");
        scanf("%d", &op);
        printf("Digite uma nota de 1 a 10 para a obra: ");
        scanf("%d", &nota);
        printf("Voce gostou desse tema? 150 Anos de Santos Dumont (Digite 1 para sim ou 2 para nao): ");
        scanf("%d", &op);
        printf("Digite uma nota de 1 a 10 para a obra: ");
        scanf("%d", &nota);
        printf("Voce gostou desse tema? Jogos Olimpicos de Paris 2024 (Digite 1 para sim ou 2 para nao): ");
        scanf("%d", &op);
        printf("Digite uma nota de 1 a 10 para a obra: ");
        scanf("%d", &nota);
        printf("Voce gostou desse tema? Tokyo 2020 (Digite 1 para sim ou 2 para nao): ");
        scanf("%d", &op);
        printf("Digite uma nota de 1 a 10 para a obra: ");
        scanf("%d", &nota);
        printf("Deseja continuar? (Digite 1 para sim ou 2 para nao): ");
        scanf("%d", &continuar);

        linha++;
    } while (continuar == 1);
}
