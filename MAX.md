#include <stdio.h>

int max (int a, int b) {                        //Функция для нахождения максимума из 2-х чисел
        if (a > b) {
            return a; }
        else {
            return b; }
    }

int main()
{
    int max_ab = (5, 7);                      //Переменная для использования функции
    printf ("Max from a and b: %d", max_ab);  //Вывод результата

    return 0;
}
