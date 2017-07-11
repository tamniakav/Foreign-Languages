# Foreign-Languages
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Foreign_Languages
{
    class Program
    {
        static void Main(string[] args)
        {
            string countryName = Console.ReadLine();

            switch (countryName)
            {
                case "England":
                case "USA": Console.WriteLine("English");break;
                case "Spain":
                case "Mexico":
                case "Argentina": Console.WriteLine("Spanish");break;
                default:
                    Console.WriteLine("unknown");
                    break;
            }
        }
    }
}
