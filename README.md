# Day-16-Exceptions-String-to-Integer
Read a string, S, and print its integer value; if  S cannot be converted to an integer, print Bad String.

String Metotlar app.patika.dev

<img width="979" alt="Ekran Resmi 2022-05-21 18 53 26" src="https://user-images.githubusercontent.com/105243448/169659598-18a77742-c928-4d25-8a64-30576343fbf8.png">



```
using System;

namespace trycatch
{
    class MainClass
    {
        public static void Main(string[] args)
        {
            string S = Console.ReadLine();

            try{
                Console.WriteLine(Convert.ToInt32(S));
            }
            catch (Exception )
            {
                Console.WriteLine("Bad String");
            }
            
        }
    }
    
}

`
