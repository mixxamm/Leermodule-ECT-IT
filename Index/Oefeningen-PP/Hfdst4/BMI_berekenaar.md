# Oplossing 1

```csharp
            Console.Write("Gewicht (kg): ");
            double gewicht = double.Parse(Console.ReadLine());

            Console.Write("Lengte (m): ");
            double lengte = double.Parse(Console.ReadLine());

            double BMI = Math.Round(gewicht / (Math.Pow(lengte,2)),2);
            Console.WriteLine($"Je BMI is {BMI}");
```

[Terug](../Hfdst4.md)