# Experiment-2

# Find the numbers of days in a month

## Aim:
  To write a Java program to find the number of days in a month.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it NumberDays.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using Switch cases.

Step 5 : Display the operations done the input in the terminal.

## Program
```
import java.util.Scanner;
public class NumberDays
{
    public static void main(String[] strings) {

        Scanner input = new Scanner(System.in);

        int number_Of_DaysInMonth = 0;
        String month = input.next();

        switch (month) {
            case "January":
                number_Of_DaysInMonth = 31;
                break;
            case "February":
                number_Of_DaysInMonth = 31;
                break;
            case "March":
                number_Of_DaysInMonth = 31;
                break;
            case "April":
                number_Of_DaysInMonth = 30;
                break;
            case  "May":
                number_Of_DaysInMonth = 31;
                break;
            case "June":
                number_Of_DaysInMonth = 30;
                break;
            case "July":
                number_Of_DaysInMonth = 31;
                break;
            case "August":
                number_Of_DaysInMonth = 31;
                break;
            case  "September":

                number_Of_DaysInMonth = 30;
                break;
            case "October":
                number_Of_DaysInMonth = 31;
                break;
            case "November":
                number_Of_DaysInMonth = 30;
                break;
            case "December":
                number_Of_DaysInMonth = 31;
        }
        System.out.print(month + " has " + number_Of_DaysInMonth + " days\n");
    }
}
```
## Output
![3](https://github.com/SaiDarshan2003/Experiment-3/assets/94692595/17e761b1-d372-4853-8ad3-ce8a01ae1c30)


## Result 
  We have successfully created a Java program to display the numbers of days in a month.
