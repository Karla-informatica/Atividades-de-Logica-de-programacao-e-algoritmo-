#include <iostream> 
 
int soma(int a, int b)
{
 return a + b;
}
int subtraçao(int a, int b)
{
 return a - b;
}
int multiplicaçao(int a, int b)
{
 return a * b;
}
int divisao(int a, int b)
{
 return a / b;
}

int main() 
{
 int resultado1 = soma(50,230);
 int resultado2 = subtraçao(78,32);
 int resultado3 = multiplicaçao(35,6);
 int resultado4 = divisao(100,2);

 std::cout << "O resultado da soma e:" << resultado1 << std::endl;
 std::cout << "O resultado da subtraçao e:" << resultado2 << std::endl;
 std::cout << "O resultado da multiplicaçao e:" << resultado3 << std::endl;
 std::cout << "O resultado da divisao e:" << resultado4 << std::endl;
return 0;
}
