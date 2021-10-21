using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Heranca
{
    class ContaJuridica
    {
        static void Main(string[] args)
        {
            Conta2 ContaJuridica;

            ContaJuridica = new Conta2(8015,"jose", 250.0, 150.0);
            Console.WriteLine(value: ContaJuridica.Saldo);

        }
    }
}
