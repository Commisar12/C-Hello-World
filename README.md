# C-Hello-World
The basic Hello World application in C#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace HelloWorld
{
    class Hello
    {
        static void Main()
        {
            Console.WriteLine("Hello World!");
            //this keeps the console window open in debug mode
            Console.WriteLine("Press any key to exit.");
            Console.ReadKey();

        }
    }
}
