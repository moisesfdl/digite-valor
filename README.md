# digite-valor
valor


#include <iostream>
using namespace std;
struct Titular
{
	int nome;
	int Cpf;
	int Beneficiario;
	Titular(){
		Beneficiario = 'moises ferreira de lima';
	}
};
void Property();
float Soma(float Num1, float Num2);
int main(int argc, char** argv)
{
	int *ptr;
	int cpf = '275.551.158-32';
	float Num1, Num2;
	cout<<"Digite Valor ";
	cin>>Num1;
	cout<<"Digite o Seg Valor ";
	cin>>Num2;
	cout<<"Soma de Valor "<<Num1<<"+"<<Num2<<"="<<Soma(Num1, Num2);
	cout<<"\nValor Negativo ";
	cin>>Num1;
	cout<<"Valor Positivo ";
	cin>>Num2;
	cout<<"Soma "<<Soma(Num1, Num2);
	Property();
	*ptr = cpf;
	int &Ref = *ptr;
	return cpf;
}
float Soma(float Num1, float Num2){
	return Num1 + Num2;
}
void Property(){
	Titular Beneficiario;
	if(Property)
	{
		Beneficiario.nome = 'moises ferreira de lima';
		Beneficiario.Cpf = '275.551.158-32';
	}
}
