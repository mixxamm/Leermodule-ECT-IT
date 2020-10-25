# Oplossing 1

```csharp
            Console.Write("Geef de eerste 3 getallen: ");
            string eerste = Console.ReadLine();

            Console.Write("Volgende 7 getallen: ");
            string tweede = Console.ReadLine();

            Console.Write("Laatste 2 getallen; ");
            int laatste = int.Parse(Console.ReadLine());

            int eersteTien = Convert.ToInt32(eerste + tweede);
            int deling = eersteTien / 97;

            if (deling == laatste )
            {
                Console.WriteLine("Je bankrekening is geldig");
            }

            else
            {
                Console.WriteLine("Je bankrekening is geldig");
            }
```

[Terug](../Hfdst5.md)