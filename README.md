// 1. Напишите цикл, который принимает на вход два числа (А и В) 
// и возводит число А в натуральную степень В.

// 3,5->243(3 в пятой);
// 2,4->16

// Console.WriteLine("Введите число A");
// int a = Convert.ToInt32(Console.ReadLine());
// Console.WriteLine("Введите число B");
// int b = Convert.ToInt32(Console.ReadLine());
// int step = a;

// for (int i = 1; i < b; i++)
// {
// step = step * a;
// }
// Console.WriteLine("A в степени B равно: " + step);

// 2. Напишите программу, которая принимает на вход число и выдаёт сумму цифр в числе.
// 452->11
// 82->10
// 9012->12

// Console.WriteLine("Введите число");
// int i = Convert.ToInt32(Console.ReadLine());
// int sum = 0;

// while (i > 0)
// {
// int num = i % 10;
// i = i / 10;
// sum = sum + num;
// }
// Console.WriteLine("Сумма всех цифр в числе равна: " + sum);

// 3. Напишите программу, которая задаёт массив из 8 элементов
//  и выводит их на экран. Вывод сделать отдельным методом.
// 1,2,5,7,19-> [1,2,5,7,19]
// 6,1,33->[6,1,33]

// int [] numbers = new int[8];
// Console.Write("[");

// for (int i = 0; i < numbers.Length; i++)
//  {
//     numbers [i] = new Random().Next(0, 11);
//     Console.Write(" " + Method (i) + " ");
//  }
// Console.Write("]");

// int Method (int a)
// {
//     return numbers[a];
// }
