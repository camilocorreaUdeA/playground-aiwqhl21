# Quiz

Una pregunta para repasar lo que acabamos de aprender.

?[¿Cuál es el error en el siguiente código?
```cpp
#include <iostream>

using namespace std;

class MyClass
{
  int x;
  void printX(void)
  {
    cout<<"El valor de x es: "<<x<<endl;
  }
};

int main()
{
	
	MyClass obj;
  obj.x = 2;
  obj.printX();
  
  return 0;
}
```]
-[ ] Está mal declarado el objeto
-[ ] La función printX no está bien codificada 
-[x] Los miembros de la clase son privados
-[ ] Ninguna de las anteriores
