# Python Homework: Message Encoder-Decoder Application

**Overview**

This project was created for a university Python programming assignment to demonstrate user input handling, control flow, and string manipulation. It’s a simple Caesar cipher tool that lets users encode or decode messages by shifting characters through the alphabet. The program includes built-in error handling for invalid inputs and showcases how loops and conditionals can maintain program stability.

The script was tested interactively — including intentional user mistakes — to confirm that input validation and menu logic function as expected.

---

**How It Works**

The user selects one of three menu options:
- 1) Encode a message
- 2) Decode a message
- 3) Exit the program

The user enters a message and chooses an integer shift between –25 and 25. The program validates the input, performs the character shift, and outputs the encoded or decoded message. Non-alphabetic characters (spaces, punctuation, etc.) are preserved exactly.

---

**Key Features**

- Input validation for non-integer or out-of-range shift values
- Support for both uppercase and lowercase letters
- Wraparound shifting (e.g., shifting "z" forward by 2 becomes "b")
- Continuous loop menu for multiple encodes/decodes until exit

---

**Skills and Concepts**

- Loops and conditionals (while, if/elif/else)
- User input validation
- String indexing and modular arithmetic
- Function design and reusability
- Error handling and testing through intentional misuse

---
