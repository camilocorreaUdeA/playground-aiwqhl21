# Bienvenido!

This C++ template lets you get started quickly with a simple one-page playground.

```C++ runnable
#include <iostream>

using namespace std;

template<typename T>
void func(T&& a)
{
    auto& x = a;
    cout<<x<<endl;
}

int main()
{
	
	int x = 2;
    const int d = 3;
    int& b = x;
    const int& c = x;
    int&& e = 3;
    const int&& f = 4;
    func(x);
    func(d);
    func(b);
    func(c);
    func(e);
    func(f);
    func(8);
       
	return 0;
}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced C++ template](https://tech.io/select-repo/598)
