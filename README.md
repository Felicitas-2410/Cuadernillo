# Cuadernillo
using System;
using System.Collections.Generic;
using System.Linq;
using System.Net.NetworkInformation;
using System.Text;
using System.Threading.Tasks;

namespace Dias_Habiles
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //declarar variables 
            int dia;
            Console.WriteLine("DIAS DE LA SEMANA");
            Console.Write("Ingrese un numero del 1 al 7 :");
            dia = int.Parse(Console.ReadLine());
            
            
            switch (dia)
            {
                case 1:
                    Console.WriteLine("DOMINGO");
                    break;
                case 2:
                    Console.WriteLine("LUNES");
                    break;
                case 3:
                    Console.WriteLine("MARTES");
                    break;
                case 4:
                    Console.WriteLine("MIERCOLES");
                    break;
                case 5:
                    Console.WriteLine("JUEVES");
                    break;
                case 6:
                    Console.WriteLine(" VIERNES");
                    break;
                case 7:
                    Console.WriteLine("SABADO");
                    break;
            }
            if (dia == 1); 
            else
            {
                Console.WriteLine("invalido");
            }
            Console.ReadKey();
        }
    }
}
