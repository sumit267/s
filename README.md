# s
Write a console application that obtains four int values from the user and displays the product.
/* 
Write a console application that obtains four int values from the user and displays the
product. Hint: you may recall that the Convert.ToDouble() command was used to convert the
input from the console to a double; the equivalent command to convert from a string to an int
is Convert.ToInt32().
*/

using System;

namespace Practical1A
{
    class P1A
    {
        static void Main()
        {
            int no1, no2, no3,no4,product;
            Console.WriteLine("Enter Four No : ");
            no1 = Convert.ToInt32(Console.ReadLine());
            no2 = Convert.ToInt32(Console.ReadLine());
            no3 = Convert.ToInt32(Console.ReadLine());
            no4 = Convert.ToInt32(Console.ReadLine());
            product = no1 * no2 * no3 * no4;
            Console.WriteLine("product of Given No = " + product);


        }
    }
}
