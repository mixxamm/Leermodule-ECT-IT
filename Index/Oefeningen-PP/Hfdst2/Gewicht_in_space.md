# Oplossing 1

```csharp
            //input van de gebruiker
            double GewichtopAarde = 76.0;
            double FactorMercurius = 0.38;
            double FactorVenus = 0.91;
            double FactorMars = 038;
            double FactorJupiter = 2.34;
            double FactorSaturnus = 1.06;
            double FactorUranus = 0.92;
            double FactorNeptunus = 1.19;
            double FactorPluto = 0.06;

            double GewichtopMercurius = GewichtopAarde * FactorMercurius;
            double GewichtopVenus = GewichtopAarde * FactorVenus;
            double GewichtopMars = GewichtopAarde * FactorMars;
            double GewichtopJupiter = GewichtopAarde * FactorJupiter;
            double GewichtopSaturnus = GewichtopAarde * FactorSaturnus;
            double GewichtopUranus = GewichtopAarde * FactorUranus;
            double GewichtopNeptunus = GewichtopAarde * FactorNeptunus;
            double GewichtopPluto = GewichtopAarde * FactorPluto;

            Console.WriteLine("Je weegt op Mercurius " + GewichtopMercurius + "Kg.");
            Console.WriteLine("Je weegt op Venus " + GewichtopVenus + "Kg.");
            Console.WriteLine("Je weegt op Aarde " + GewichtopAarde + "Kg.");
            Console.WriteLine("Je weegt op Mars " + GewichtopMars + "Kg.");
            Console.ForegroundColor = ConsoleColor.Red;
            Console.WriteLine("Je weegt op Jupiter " + GewichtopJupiter + "Kg.");
            Console.ResetColor();
            Console.WriteLine("Je weegt op Saturnus " + GewichtopSaturnus + "Kg.");
            Console.WriteLine("Je weegt op Uranus " + GewichtopUranus + "Kg.");
            Console.WriteLine("Je weegt op Neptunus " + GewichtopNeptunus + "Kg.");
            Console.ForegroundColor = ConsoleColor.Green;
            Console.WriteLine("Je weegt op Pluto " + GewichtopPluto + "Kg.");
            Console.ResetColor();
```

[Terug](../Hfdst2.md)