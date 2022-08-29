//# Seminar_3

//Задача 21
//Напишите программу, которая принимает на вход координаты двух точек и находит расстояние между ними в 3D пространстве.
//A (3,6,8); B (2,1,-7), -> 15.84
//A (7,-5, 0); B (1,-1,9) -> 11.53

// Console.Write("ваедите координату по оси 0X точки А: ");
// int XА = Convert.ToInt32(Console.ReadLine());
// Console.Write("ваедите координату по оси 0Y точки А: ");
// int YА = Convert.ToInt32(Console.ReadLine());
// Console.Write("ваедите координату по оси 0Z точки А: ");
// int ZА = Convert.ToInt32(Console.ReadLine());

// Console.Write("Введите координату по оси 0X точки В: ");
// int XВ = Convert.ToInt32(Console.ReadLine());
// Console.Write("ваедите координату по оси 0Y точки В: ");
// int YВ = Convert.ToInt32(Console.ReadLine());
// Console.Write("ваедите координату по оси 0Z точки В: ");
// int ZВ = Convert.ToInt32(Console.ReadLine());

// double distance = Math.Sqrt(Math.Pow((XА - XВ),2) + Math.Pow((YА - YВ),2) + Math.Pow((ZА - ZВ),2));
// //Console.WriteLine("Расстояние между точками " + Math.Round(distance,2)); 
// Console.WriteLine($"Расстояние между точками = {distance:f2}"); 

//Задача 23
//Напишите программу, которая принимает на вход число (N) и выдаёт таблицу кубов чисел от 1 до N.
//3 -> 1, 8, 27
//5 -> 1, 8, 27, 64, 125

//  Console.Write("Введите число: ");
//     int number = Convert.ToInt32(Console.ReadLine());
//     for (int count = 1; count <= number; count++)
//     {
//     Console.Write(Math.Pow(count, 3) + "\t");
//     } 

//Задача 19
//Напишите программу, которая принимает на вход пятизначное число и проверяет, является ли оно палиндромом.
//14212 -> нет
//12821 -> да
//23432 -> да

// Console.Write("Введите число из пяти цифр: ");
// string? imputNumber = Console.ReadLine();
// if (imputNumber[0] == imputNumber[4] && imputNumber[1] == imputNumber[3]) Console.WriteLine($"Число, {imputNumber} является палиндромом");
// else Console.WriteLine($"Число,{imputNumber} не является палиндромом ");