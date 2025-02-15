# Password Generator

Generates secure and customizable passwords based on user-defined criteria.

## Documentation

This Java program creates strong passwords based on user-specified parameters.  The program reads input parameters from a file (`test_files/input.txt`) and writes the generated password to a file (`test_files/output.txt`).


### Design Choices

*   **Password Generation:** To ensure strong and unpredictable passwords, we use Java's SecureRandom class.
*   **Character Sets:** Character sets (lowercase, uppercase, digits, and special symbols) are stored as String constants.


### Algorithms and Data Structures

*   **Password Generation Algorithm:** The algorithm generates a random password length within the specified range. Based on the user's selected character types, it randomly selects characters from the corresponding sets and appends them to the password string.
*   **Data Structures:** Strings (`String`) store character sets.  `StringBuilder` is used to efficiently construct the password string.



