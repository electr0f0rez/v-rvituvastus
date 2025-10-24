```csharp
# v-rvituvastus
värvituvastus
            //5 värvituvastus
            Console.WriteLine("Milline värv sulle kõige rohkem meeldib?:");
            string favouriteColour = Console.ReadLine();
            if (favouriteColour == "punane")

            {
                Console.BackgroundColor = ConsoleColor.Red;
            }
            if (favouriteColour == "oranz")
            {
                Console.WriteLine("Kahjuks oranzi ei ole");
            }
            if (favouriteColour == "roheline")
            {
                Console.BackgroundColor = ConsoleColor.Green;
            }
            else
            {
                Console.WriteLine("Värvi ei tunne");
            }
            Console.WriteLine("Värv suudetud!");
