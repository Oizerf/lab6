# lab6// 1
// string heroName = "Ada";
// int health = 70;
// int maxHealth = 100;
// int gold = 15;
// int strength = 6;
// int weaponDamage = 3;
// bool isRunning = true;

// while (isRunning)
// {
//     Console.WriteLine("====================");
//     Console.WriteLine($"Bohater: {heroName}");
//     Console.WriteLine($"Zdrowie: {health}/{maxHealth}");
//     Console.WriteLine($"Złoto: {gold}");
//     Console.WriteLine("====================");
//     Console.WriteLine("1. Atak treningowy");
//     Console.WriteLine("2. Odpoczynek");
//     Console.WriteLine("3. Koniec gry");
//     Console.Write("Wybór: ");

//     string? command = Console.ReadLine();

//     if (command == "1")
//     {
//         int damage = strength + weaponDamage;
//         Console.WriteLine($"Zadajesz {damage} obrażeń manekinowi.");
//     }
//     else if (command == "2")
//     {
//         health += 10;

//         if (health > maxHealth)
//         {
//             health = maxHealth;
//         }

//         Console.WriteLine($"Odpoczywasz. Masz teraz {health} HP.");
//     }
//     else if (command == "3")
//     {
//         isRunning = false;
//     }
//     else
//     {
//         Console.WriteLine("Nieznana komenda.");
//     }
// }
// 2
// void ShowPanelTitle(string title, ConsoleColor backgroundColor)
// {
//     Console.BackgroundColor = backgroundColor;
//     Console.ForegroundColor = ConsoleColor.White;
//     Console.WriteLine($"  {title.ToUpper()}  ");
//     Console.ResetColor();
// }

// void ShowStatus(string name, int health, int maxHealth, int gold)
// {
//     ShowPanelTitle("Status bohatera", ConsoleColor.DarkBlue);

//     Console.ForegroundColor = ConsoleColor.Cyan;
//     Console.Write("Bohater:  ");
//     Console.ResetColor();
//     Console.WriteLine(name);

//     Console.ForegroundColor = ConsoleColor.Green;
//     Console.Write("Zdrowie: ");
//     Console.ResetColor();
//     Console.WriteLine($"{health}/{maxHealth} HP");

//     Console.ForegroundColor = ConsoleColor.Yellow;
//     Console.Write("Złoto:    ");
//     Console.ResetColor();
//     Console.WriteLine(gold);
// }

// void ShowMenu()
// {
//     ShowPanelTitle("Menu", ConsoleColor.DarkCyan);
//     Console.WriteLine("[1] Atak treningowy");
//     Console.WriteLine("[2] Odpoczynek");
//     Console.WriteLine("[3] Koniec gry");
// }
// ShowPanelTitle("league",ConsoleColor.Blue);
// ShowStatus("yone",50,100,15);
// ShowMenu();
// 3
// int CalculateDamage(int strength, int weaponDamage)
// {
//     int damage = strength + weaponDamage;
//     return damage;
// }
//     int Heal(int health, int amount, int maxHealth)
// {
//     if (amount <= 0)
//     {
//         return health;
//     }

//     int newHealth = health + amount;
//     return Math.Min(newHealth, maxHealth);
// }
//4
// string ReadCommand()
// {
//         while (true)
//     {
//         Console.Write("Wybór: ");
//         string? command = Console.ReadLine();
//         if (command == "1")
//         {
//             Console.WriteLine("wybrales 1");
//             break;
//         }
//                 else if(command == "2")
//         {
//             Console.WriteLine("wybrales 2");
//             break;
//         }
//                 else if(command == "3")
//         {
//             Console.WriteLine("wybrales 3");
//             break;
//         }
//         else
//         {
//             Console.WriteLine("niema takiej komendy");
//         }
//     }
// }
// ReadCommand();
//5
