# 404B Lesson 1 Class Exercise - Variables

## Instructions

### Split VS Code Window

You can drag `main.py` tab to the right side of the window to split the window into two panes. This will allow you to see the instructions and the code at the same time.

### Answering

You can answer the questions by writing your answers in the `main.py` file.

You can run the code by clicking the `Run` button on the top right corner of the editor.

The output will be shown in the `Terminal` tab at the bottom of the editor.

## Questions

1. What is the value of variable `x`?

   ```python
   x = 3
   x = x + 2
   x = x + x
   ```

2. What are the values of variable a, b and c?

    ```python
    a = 5
    b = 10
    c = b

    a = a + 1
    b = b - 1
    c = c + a
    ```

3. What are the values of variable first and second?

    ```python
    first = 8
    second = 19
    first = first + second
    second = first - second
    first = first - second
    ```

4. Rewrite the code in Q3 to be shorter, by declaring the variables together and by using the special assignment operators (e.g., += , −=, *=, and /=) as appropriate.

5. Modify the program to remove all redundant expressions and give meaning to "magic" number using variables.

    ```python
    work_hours = 4 + 5 + 8 + 4

    # Calculate pay at work based on hours worked each day
    print("My total hours worked:")
    print(4 + 5 + 8 + 4)

    print("My hourly salary:")
    print("$8.75")

    print("My total pay:")
    print((4 + 5 + 8 + 4) * 8.75)

    print("My taxes owed:")  # 20% tax
    print((4 + 5 + 8 + 4) * 8.75 * 0.20)
    ```

6. Modify the program to remove all redundant expressions and give meaning to "magic" number using variables.

    ```python
    # This program computes the total amount owed for a meal,
    # assuming 8% tax and a 15% tip.
    print("Subtotal:")
    print(38 + 40 + 30)
    
    print("Tax:")
    print((38 + 40 + 30) * 0.08)
    
    print("Tip:")
    print((38 + 40 + 30) * 0.15)
    
    print("Total:")
    print(38 + 40 + 30 + (38 + 40 + 30) * 0.08 + (38 + 40 + 30) * 0.15)
    ```
