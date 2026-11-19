# calculadora-imc
Cálculo del índice de masa corporal

#include <iostream>
using namespace std;

double calcularImc(double pesoKg, double estaturaM) {
    return pesoKg / (estaturaM * estaturaM);
}

int main() {
    double peso, estatura;
    cout << "Peso (kg): ";
    cin >> peso;
    cout << "Estatura (m): ";
    cin >> estatura;
    cout << "IMC: " << calcularImc(peso, estatura) << endl;
    return 0;
}
