# Oplossing 1

```csharp
            const int frietjes = 20;
            const int koninginnenhapje = 10;
            const int ijsjes = 3;
            const int drank = 2;

            Console.WriteLine("Frietjes?");
            int aantalFriet = int.Parse(Console.ReadLine());
            int totaalF = aantalFriet * frietjes;
            Console.WriteLine($"Tussenprijs = {totaalF} euro");

            Console.WriteLine("koninginnenhapje?");
            int aantalKoninginnenhapje = int.Parse(Console.ReadLine());
            int totaalK = koninginnenhapje * aantalKoninginnenhapje;
            Console.WriteLine($"Tussenprijs = {totaalF} euro + {totaalK} euro");

            Console.WriteLine("Ijsjes?");
            int aantalIjsjes = int.Parse(Console.ReadLine());
            int totaalI = ijsjes * aantalIjsjes;
            Console.WriteLine($"Tussenprijs = {totaalF} euro + {totaalK} euro + {totaalI} euro");

            Console.WriteLine("Dranken");
            int aantalDranken = int.Parse(Console.ReadLine());
            int totaalD = aantalDranken * drank;
            Console.WriteLine($"Tussenprijs = {totaalF} euro + {totaalK} euro + {totaalI} euro  + {totaalD} euro");

            int totaal = totaalF + totaalK + totaalI + totaalD ;

            Console.WriteLine();

            Console.WriteLine($"Het totaal te betalen bedrag is {totaal} EURO.");

```

[Terug](../Hfdst4.md)