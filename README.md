# digite-valor
valor


#include <iostream>

using namespace std;
float Soma(float Num1, float Num2);
int main(int argc, char** argv)
{
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
	return 0;
}
float Soma(float Num1, float Num2){
	return Num1 + Num2;
}
