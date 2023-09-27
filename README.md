# Tarefa 1
## 1.
```cpp
#include <iostream>

using namespace std;

int main() {
    float nota1, nota2, nota3;
    
    cout << "Digite a nota da primeira avaliacao: ";
    cin >> nota1;
    cout << "Digite a nota da segunda avaliacao: ";
    cin >> nota2;
    cout << "Digite a nota da terceira avaliacao: ";
    cin >> nota3;

    float media = (nota1 + nota2 + nota3) / 3;
    if (media >= 10) {
        cout << "Esta Aprovado!" << endl;
    } else {
        cout << "Esta Reprovado!" << endl;
    }
    return 0;
}
```

## 2.
```cpp
#include <iostream>

using namespace std;

int main() {
    int num1, num2;
    cout << "Digite o primeiro numero inteiro: ";
    cin >> num1;
    cout << "Digite o segundo numero inteiro: ";
    cin >> num2;
    if (num1 == num2) {
        cout << "Os numeros sao iguais." << endl;
    }
    else if (num1 > num2) {
        cout << "O primeiro numero (" << num1 << ") e maior." << endl;
    }
    else {
        cout << "O segundo numero (" << num2 << ") e maior." << endl;
    }
    return 0;
}
```

## 3.
```c++
#include <iostream>
using namespace std;
int main() {
    int numero;
    // Pedir ao utilizador que insira um número
    cout << "Digite um numero para calcular a tabuada: ";
    cin >> numero;
    // Calcular e apresentar a tabuada
    Tarefa 1 2
    cout << "Tabuada do " << numero << ":" << endl;
    for (int i = 1; i <= 10; i++) {
        cout << numero << " x " << i << " = " << numero * i << endl;
    }
    return 0;
}
```

## 4.
```c++
#include <iostream>

using namespace std;

int main() {
    float lado1, lado2, lado3;
    // Solicitar ao utilizador que insira as medidas dos lados
    cout << "Introduza o lado 1 do triangulo: ";
    cin >> lado1;
    cout << "Introduza o lado 2 do triangulo: ";
    cin >> lado2;
    cout << "Introduza o lado 3 do triangulo: ";
    cin >> lado3;
    // Verificar se é um triângulo
    if (lado1 <= 0 || lado2 <= 0 || lado3 <= 0 || (lado1 + lado2 <= lado3) || (lado1 + lado3 <= lado2) || (lado2 + lado3 <= lado1)) {
        cout << "Nao e um triangulo" << endl;
    }
    else if (lado1 == lado2 && lado2 == lado3) {
        cout << "E um triangulo equilatero (todos os lados iguais)" << endl;
    } else if (lado1 == lado2 || lado2 == lado3 || lado1 == lado3) {
        cout << "E um triângulo isosceles (dois lados iguais e um diferente)" << endl;
    } else {
        cout << "E um triangulo escaleno (todos os lados diferentes)" << endl;
    }
    return 0;
}
```

## 5.
```cpp
#include <iostream>
#include <cmath>

using namespace std;

int main() {
    double cateto1, cateto2;
    cout << "Digite o valor do primeiro cateto: ";
    cin >> cateto1;
    cout << "Digite o valor do segundo cateto: ";
    cin >> cateto2;
    double hipotenusa = sqrt(cateto1 * cateto1 + cateto2 * cateto2);
    double area = 0.5 * cateto1 * cateto2;
    cout << "A hipotenusa do triangulo e: " << hipotenusa << endl;
    cout << "A area do triangulo e: " << area << endl;
    return 0;
}
```