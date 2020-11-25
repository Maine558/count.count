using System;

namespace _2_цифры
{
    class Program
    {
        static void Main()
        {


            Console.WriteLine("Напишите 2 любых числа. Первое - делимое, второе - делитель");

            int num1 = int.Parse(Console.ReadLine());

            int num2 = int.Parse(Console.ReadLine());

           

            if (num2 == 0)
            {

                Console.WriteLine("На ноль делить нельзя");


            }

            else if (num1>=num2)
            {

                var result = num1 / num2;

                Console.WriteLine(result);


            }
             else
            {

                Console.WriteLine("Недопустимое выражение");

            }


           
           


        }
    }
}

