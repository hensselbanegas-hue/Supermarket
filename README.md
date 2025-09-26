#include <iostream>
#include <string>
using namespace std;
string nombreCliente;

void menuVerduras(){
	int opcion;
	do{
		cout <<"Verduras";
		cout <<"1. Tomates";
		cout <<"2. Repollo";
		cout <<"3. papas";
		cout <<"4. regresar";
		cout <<"seleccionar una opcion(numero del 1 al 4)";
		cin>> opcion;
		
			switch (opcion) {
			case 1:
				cout <<"has seleccionado Tomates";
				break;
			case 2:
				cout<<"has seleccionado Repollos";
				break;
			case 3:
				cout <<"has seleccionado papas";
				break;
			case 4:
				cout<<"regresar al lobby";
			default:
				cout<<"opcion invalida intenta de nuevo";
			}
		} while (opcion !=4);
	}



int main() {
	int opcion, i=1;
	int tipoCliente;
	int edadCliente;
	cout <<"ingrese su nombre"<<(i)<<endl;
	cin>>nombreCliente;
	cout<<" tipo de cliente";
	cin>>tipoCliente;
	cout<<"Edad";
	cin>>edadCliente;
