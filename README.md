# contacts
#include <cs50.h>  // Inclui a biblioteca cs50 para funções de entrada/saída fáceis de usar
#include <stdio.h>  // Inclui a biblioteca padrão C para operações de entrada/saída (printf)

int main(void) {    // Função principal do programa, ponto de entrada
    string name = get_string("Qual é o seu nome? ");  // Solicita e armazena o nome do usuário
    int age = get_int("Qual é a sua idade? ");        // Solicita e armazena a idade do usuário (número inteiro)
    string number = get_string("Qual é o seu número de telefone? ");  // Solicita e armazena o número de telefone do usuário

    printf("Nome: %s\n", name);    // Exibe o nome do usuário formatado com a string name
    printf("Idade: %i\n", age);     // Exibe a idade do usuário formatado com o inteiro age
    printf("Número: %s\n", number);  // Exibe o número de telefone do usuário formatado com a string number

    return 0;  // Indica execução bem-sucedida do programa
}
