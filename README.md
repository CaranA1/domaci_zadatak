# Домаћи задатак из Техничке документације
##  Задатак
Програм који на основу унетих дужина страница трапеза a и b и висине h израчунава
површину трапеза P.

$P = \frac{a+b}{2} \cdot h$
### Алгоритамска шема
![](Main.png)
## Решење
```
using System;

class Program
{
    static void Main()
    {
        double a;
        double b;
        double h;
        double P;

        Console.Write("Unesite dužinu stranice a: ");
        a = double.Parse(Console.ReadLine());

        Console.Write("Unesite dužinu stranice b: ");
        b = double.Parse(Console.ReadLine());

        Console.Write("Unesite visinu h: ");
        h = double.Parse(Console.ReadLine());

        P = ((a + b) / 2) * h;

        Console.WriteLine("Površina trapeza je: " + P);
    }
}
```
### Тест примери
