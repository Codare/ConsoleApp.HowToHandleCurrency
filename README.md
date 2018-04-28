# decimal is the correct .Net type to use for handling currency

Console.WriteLine("Which type should be used for handling currency in .NET");

double xDouble = 0.1;
double yDouble = xDouble + xDouble + xDouble;

Console.WriteLine($"Adding double 0.1 three times and storing the result in yDouble: should be false if using double. {yDouble == 0.3}"); // Prints False

decimal xDecimal = 0.1m;
decimal yDecimal = xDecimal + xDecimal + xDecimal;

Console.WriteLine($"Adding decimal 0.1 three times and storing the result in yDecimal: should be true if using decimal. {yDecimal == 0.3m}"); // Prints True

Console.ReadLine();
