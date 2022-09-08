### EX NO : 02
### DATE  : 
# <p align="center">Palindrome</p>



## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare two variable with string datatype
### Step3:
Loop over the entire string and reverse it
### Step4:
Use if condition to check whether the string and the reversed string is equal or not
### Step5:
print palindrome if it's equal else print not a palindrome.
### Step6:
stop

## Program:
```c#
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("{0} is Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```

## Output:
![Screenshot 2022-09-07 095940](https://user-images.githubusercontent.com/70213227/189131366-b13576ea-92f1-4605-b847-2165872c8608.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
