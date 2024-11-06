AgeCalculator2

The AgeCalculator2 is a Java program that calculates the age of a person based on their date of birth (DOB). The program takes the date of birth as a command-line argument in the format dd-MM-yyyy and outputs the person's age in years, months, and days. It also includes validation checks to ensure the input is a valid date and that the date is not in the future.
Features

    Leap Year Check: The program validates whether the entered date is February 29 and checks if the specified year is a leap year.
    Invalid Date Handling: It checks for invalid date formats or non-existent dates.
    Future Date Validation: Ensures the entered date of birth is not in the future.
    Age Calculation: Calculates the age in years, months, and days.

Prerequisites

    Java 8 or later is required to run the program.
    Command-line access to run the Java program.

How to Use

    Clone or download the repository to your local machine.
    Compile the Java file:

javac AgeCalculator2.java

Run the program with a date of birth as a command-line argument:

    java AgeCalculator2 <dd-MM-yyyy>

Example

If your date of birth is 12-04-1995, you would run:

java AgeCalculator2 12-04-1995

Output

The program will output the age in years, months, and days:

Your age is 29 years, 7 months, and 12 days.

Error Handling

    Invalid Date Format: If the date format is incorrect, the program will display:

Invalid date format or non-existent date. Please enter the date in the format dd-MM-yyyy.

Leap Year Error: If February 29 is provided on a non-leap year, the program will show:

Invalid date: dd-02-yyyy is not in a leap year.

Future Date: If the date of birth is in the future, the program will output:

The date of birth cannot be in the future.



        
