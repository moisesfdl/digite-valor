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
	float Num1[7]{0.50 , 0.25,  0.5, 0.0, -0.05, -0.25, -0.5 };
	float Num2[7]{0.50 , 0.25,  0.5, 0.0, -0.05, -0.25, -0.5 };
	cout<<"\tQual o valor\n\t[0.50]\t[0.25]\t[0.5]\t[0.0]\t[-0.05]\t[-0.25]\t[-0.5]\n";
	cout<<"Digite Valor ";
	cin>>Num1[7];
	cout<<"Digite o Seg Valor ";
	cin>>Num2[7];
	cout<<"Soma de Valor "<<Num1[7]<<"+"<<Num2[7]<<"="<<Soma(Num1[7], Num2[7]);
	cout<<"\nValor Negativo ";
	cin>>Num1[7];
	cout<<"Valor Positivo ";
	cin>>Num2[7];
	cout<<"Soma "<<Soma(Num1[7], Num2[7]);
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
