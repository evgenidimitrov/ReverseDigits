using System;
using System.Text;

namespace ReverseDigits
{
    class ReverseDigits
    {
        static decimal ReversingDigits(decimal number)
        {
            return decimal.Parse(new string(number.ToString().ToCharArray().Reverse().ToArray()));
        }

        static void Main()
        {
            Console.WriteLine("Enter a number:");
            decimal number = decimal.Parse(Console.ReadLine());

            Console.WriteLine("Converted number: {0}" , ReversingDigits(number));
        }
    }
}
