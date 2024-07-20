# SE2012-Practical - 02 - Java Basics

1. Write a Java program that reads a ship’s serial number and displays the class of the ship. Each ship serial number begins with a letter indicating the class of the ship. The program first reads the first 
   letter of a ship’s serial number into a char variable and then displays that character. Use a switch statement to display a message indicating the class of the ship.

    | Class ID | Ship Class  |
    |----------|-------------|
    | B or b   | Battleship  |
    | C or c   | Cruiser     |
    | D or d   | Destroyer   |
    | F or f   | Frigate     |

---

2. Write a Java program that performs various string manipulation tasks as described below. Ensure that you include comments in your code to explain each step.

### Part 1: String Concatenation
- Prompt the user to enter their first name, middle name, and last name separately.
- Concatenate these strings to create a full name in the format: "Last Name First Name Middle Name".
- Display the concatenated full name.

### Part 2: String Comparison
- Prompt the user to enter another full name.
- Compare this new full name with the previously concatenated full name to check if they are the same (case-insensitive comparison).
- Display an appropriate message indicating whether the names are the same or different.

### Part 3: String Modification
- Modify the concatenated full name (Last Name First Name Middle Name) to replace all occurrences of the letter 'a' with '@' and 'e' with '3'.
- Convert the entire full name to uppercase.
- Display the modified full name.

### Part 4: String Splitting
- Split the concatenated full name into individual components (Last Name First Name Middle Name) based on the comma and space.
- Display each component separately.

### Part 5: String Trimming
- Prompt the user to enter a string with leading and trailing spaces.
- Trim the spaces from the string and display the trimmed string.

### Part 6: Additional Manipulations
- Count the number of vowels (a, e, i, o, u) in the concatenated full name.
- Display the number of vowels found.

### Notes for Students:
- Use the Scanner class to read input from the user.
- For string concatenation you can use the + operator.
- For string comparison use the `.equalsIgnoreCase()` method.
- For string modification use the `.replace()` method and `.toUpperCase()` method.
- For string splitting use the `.split()` method.
- For string trimming use the `.trim()` method.
- To count vowels you can iterate over the string and use a conditional statement to check for vowels.
