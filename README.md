# Hola-Mundo
cpp of Hola Mundo
#include <iostream>
using namespace std;

//Metodo Saludar
void saludar(char* nombre){
	cout << "Hola " << nombre << endl; // prints !!!Hola mundo!!!
}
int main() {
	saludar("Peter");
	return 0;
}
