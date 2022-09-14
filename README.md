# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step 1: 
To start the C# program in visual Studio 2022.

### Step 2: 
Create a class and declare two variable with string datatype.

### Step 3: 
Loop over the entire string and reverse it.

### Step 4: 
Use if condition to check whether the string and the reversed string is equal or not.

### Step 5: 
print palindrome if it's equal else print not a palindrome.

### Step 6: 
Save the program and run the program in visual studio 2022.

## Program:
~~~
using System;
namespace Palindrome
{
    public class program
    {
        static void Main(string[] args)
        {
            string s, rev = "";
            Console.WriteLine("Enter String: ");
            s = Convert.ToString(Console.ReadLine());
            for (int i = s.Length - 1; i >= 0; i--)
            {
                rev += s[i];
            }
            if (rev == s)
            {
                Console.WriteLine("{0} is a Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not a Palindrome", s);
            }
            Console.ReadLine();
        }
    }
}

~~~

## Output:
![image](https://user-images.githubusercontent.com/66360846/190066226-bd48b004-69f4-46fe-93e2-7737754d98a7.png)

![image](https://user-images.githubusercontent.com/66360846/190066330-000adf5e-5dde-4960-a767-598416c01ba2.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
