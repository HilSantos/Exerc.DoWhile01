# Exerc.DoWhile01
Trabalhando com do while, validação de idade entre 0 e 120

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ExercicioDoWhile01
{
    public class Program
    {
        static void Main(string[] args)
        {
            //Trabalhando com do while
            //Validação de idade entre 0 e 120

  int idade;
            do
            {
                Console.WriteLine("Informe uma idade entre 0 e 120: ");
                idade = Convert.ToInt32(Console.ReadLine());

  } while (idade < 0 || idade <= 120);
            Console.WriteLine("Idade Rgistrada!");

  Console.ReadKey();

  }
}
}
