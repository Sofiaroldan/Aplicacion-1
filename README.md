using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp3
{
    class Program
    {
        static void Main(string[] args)
        {
            {
                char[,] mat = new char[5, 15];
                char buscar;

                for (int f = 0; f < 15; f++)
                {
                    for (int c = 0; c < 5; c++)
                    {
                        Console.Write("fila:" + f + "Nombre:" + c);
                        Console.Write("ingrese los datos");
                        mat[c, f] = char.Parse(Console.ReadLine());

                        Console.WriteLine("--------------------------------------------- ----- ");

                        for (f = 0; f < 15; f++)
                        {

                            Console.WriteLine(mat[c, f]);
                        }
                        Console.WriteLine("--------------------------------------------- ----- ");
                        Console.WriteLine("Ingrese caracter a buscar");
                        buscar = char.Parse(Console.ReadLine());

                        for (int l = 0; l <= 0; l++)
                        {
                            if (mat[c, f] == buscar) ;

                        }

                        Console.Write("dato " + buscar + " encontrado");

                    }
                }

                Console.ReadKey();
            }
        }
    }
}
