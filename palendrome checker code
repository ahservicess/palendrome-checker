using System;

namespace Palindrome_Checker
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter a string like this (civic,121,mam e.t.c):");
            string input = Console.ReadLine();
            input = input.ToLower();
            int left = 0; 
            int right = input.Length - 1;
            bool isPalindrome = true; 

            while (left < right)
            {
                if (input[left] != input[right])
                {
                    isPalindrome = false;
                    break;
                }
                else
                {
                    left++;
                    right--;
                }
            }

            if (isPalindrome)
            {
                Console.WriteLine("String is a palindrome");
            }
            else
            {
                Console.WriteLine("String is not a palindrome");
            }
            Console.ReadLine();
        }
    }
}
