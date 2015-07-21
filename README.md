# ninja
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Example
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World");
           
           
         Console.WriteLine("ÜÇGEN");
            string a = " ";
            for (int i = 1; i < 10; i = i + 2)
            {
                int j = (9 - i) / 2;
                for (int k = 1; k <= j; k++)
                {
                    Console.Write(a);


                }
                for (int m = 1; m <= i; m = m + 1)
                {
                    Console.Write("*");
                }
                for (int l = 1; l <= j; l++)
                {
                    Console.Write(a);


                }
                Console.WriteLine("");
            }

         
            Console.WriteLine("KARE");

            for (int i = 0; i < 5; i++)
            {
                for (int j = 0; j < 5; j++)
                {
                    Console.Write("*");
                }
                Console.WriteLine("");
            }
            Console.WriteLine("İÇİ BOŞ KARE");

            for (int b = 0; b < 5; b++)
            {
                if (b == 0 || b == 4)
                
                     {
                for (int j = 0; j < 7; j++)
                {
                    Console.Write("*");
                }
                Console.WriteLine("");
            }



                else                {
                    for (int c = 0; c < 5; c++)
                    {
                        if (c == 0)

                            Console.Write("*");
                        if (c > 0 || c <= 3)
                        {
                            Console.Write(" ");
                        }
                        if (c == 4)
                            Console.WriteLine("*");

                    }
                }
            

            }

                Console.ReadLine();
            }

        }

    }

    



