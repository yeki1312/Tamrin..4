# Tamrin..4
using System;

class Program
{
    static void Main()
    {
        int position = -1; // موقعیت عدد 2 (در صورت وجود)

        Console.WriteLine("لطفاً 5 عدد وارد کنید:");

        for (int i = 1; i <= 5; i++)
        {
            Console.Write($"عدد {i}: ");
            int number = int.Parse(Console.ReadLine());

            if (number == 2 && position == -1)
            {
                position = i; // ذخیره موقعیت اولین عدد 2
            }
        }

        if (position != -1)
        {
            C
