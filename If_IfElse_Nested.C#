using System;

class Program
{
    static void Main()
    {
        Console.Write("Enter your age: "); // Prompt user for age
        string input = Console.ReadLine(); // Read user input

        // Attempt to convert input to integer
        bool isNumber = int.TryParse(input, out int age);

        if (isNumber) // Check if input is a valid integer
        {
            if (age >= 18) // First if: eligible to vote
            {
                Console.WriteLine("You are eligible to vote.");

                // Nested if: check if senior citizen
                if (age >= 65)
                {
                    Console.WriteLine("You are also a senior citizen.");
                }
            }
            else // If age is less than 18
            {
                Console.WriteLine("You are not eligible to vote yet.");
            }
        }
        else // If input is not a valid integer
        {
            Console.WriteLine("Invalid input. Please enter a valid number.");
        }
    }
}
