using System;
using System.Collections;

class Program
{
    static void Main()
    {
        ArrayList numbers = new ArrayList();

        Console.WriteLine("Nhap so nguyen vao danh sach (Nhap 'x' de dung):");
        while (true)
        {
            string input = Console.ReadLine();
            if (input.ToLower() == "x")
                break;

            int number;
            if (int.TryParse(input, out number))
            {
                numbers.Add(number);
            }
            else
            {
                Console.WriteLine("Vui long nhap mot so nguyen hop le.");
            }
        }

        // Sap xep danh sach cac so theo thu tu tang dan
        numbers.Sort();

        // In ra danh sach da sap xep
        Console.WriteLine("Danh sach so nguyen theo thu tu tang dan:");
        foreach (int num in numbers)
        {
            Console.WriteLine(num);
        }
    }
}
