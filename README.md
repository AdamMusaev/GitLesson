# Аттестация

using System;
namespace ConsoleApp5
{
    class OneMain
    {
        static void Main(string[] args)
        {
            DK1 qq = new DK1();
            DK1.OtecMat();
            DK2 ww = new DK2();
            DK2.son();
            DK3 ee = new DK3();
            DK3.daughter();
        }
    }
    class Parents
    {
        public static void OtecMat()
        {
            Console.Write("Введите своё имя:");
            string rr = Console.ReadLine();
            Console.WriteLine($"Имя :{rr}");
            Console.ReadKey();
           
        }
        public static void son()
        {
            Console.WriteLine("Имя: Арнольд");
            Console.WriteLine("Рост: 198");
            Console.WriteLine("Вес: 93кг");
            Console.WriteLine("Хобби: Качалка");
        }
        public static void daughter()
        {
            Console.WriteLine("\nИмя: Белла");
            Console.WriteLine("Рост: 180");
            Console.WriteLine("Цвет волос: Брюнетка");
            Console.WriteLine("Хобби: Пианино");
        }
    }
    class DK1 : Parents
    {         

    }
    class DK2 : Parents
    {
           
    }
    class DK3 : Parents
    {

    }
}
