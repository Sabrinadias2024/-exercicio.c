#include <iostream>

int main() {

   int senhaCorreta = 1234;

   int senhaUsuario;

   do {

       std::cout << "Digite a senha: ";

       std::cin >> senhaUsuario;

       if (senhaUsuario == senhaCorreta) {

           std::cout << "Senha Correta" << std::endl;

           break; // Sai

       } else {

           std::cout << "Senha Incorreta" << std::endl;

       }

   } while (senhaUsuario != senhaCorreta); 

   return 0;

}
