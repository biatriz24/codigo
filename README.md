#include <stdio.h>

int main() {
    int codigo;
    printf("Informe o código do produto\n");
    scanf("%d", &codigo);

    if (codigo == 1) {
        printf("Alimento não perecível\n");
    } else if (codigo == 2 || codigo == 3 || codigo == 4) {
        printf("Alimento perecível\n");
    } else if (codigo == 5 || codigo == 6) {
        printf("Vestuário\n");
    } else if (codigo == 7) {
        printf("Higiene pessoal\n");
    } else if (codigo == 8 || codigo == 9 || codigo == 10) {
        printf("Utensílios domésticos\n");
    } else {
        printf("Código inválido\n");
    }

    return 0; 
}

