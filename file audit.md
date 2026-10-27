# README Claims Audit

This audit checks the README claims against the code in `factorial.py`.

| README claim | Status | Evidence from `factorial.py` |
|---|---|---|
| The program calculates the factorial of a non-negative number. | Supported | The program accepts `number` and calculates `factorial` when `number >= 0`. |
| The program accepts a number from the user. | Supported | `input("Enter a non-negative number: ")` collects user input. |
| The program uses a `for` loop. | Supported | The code uses `for i in range(1, number + 1):`. |
| The program displays the calculated factorial. | Supported | The code uses `print("Factorial of", number, "is", factorial)`. |
| The program handles negative-number input. | Supported | The code checks `if number < 0:` and prints a message. |
| Python 3 is required. | Supported | The code uses standard Python 3 syntax and `input()`. |
| The example result for input `5` is `120`. | Supported | The loop multiplies values from `1` to `5`, producing `120`. |
| No license has been added to the project. | Unverified | A license file cannot be checked from `factorial.py`; confirm this in the GitHub repository. |
