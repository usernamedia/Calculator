# My Awesome Java Calculator Project!

## What's This All About?

So, this is a calculator I made in Java for my second-semester programming class. It's not just a basic calculator; it does some extra stuff like square roots, absolute values, and even lets you raise numbers to a power! It's a console program, meaning you run it from the command line.

## What Can It Do?

*   **The Usual Math:** Add, subtract, multiply, divide, modulus (that's the remainder after division).
*   **Cooler Stuff:**
    *   `power(a, b)`:  `a` to the power of `b` (like a squared, a cubed, etc.).
    *   `sqrt(x)`:  The square root of `x`.
    *   `abs(x)`:  Makes `x` positive (absolute value).
    *   `round(x)`:  Rounds `x` to the nearest whole number.
*   **Doesn't Break (Hopefully!):**  It tries to handle errors, like dividing by zero or typing in something that's not a number.
*   **Remembers Stuff:** It keeps a history of the last 10 calculations you did.

## How To Get It Working

1.  **Grab the Files:** Download all the `.java` files (`CalculatorException.java`, `CalculatorHistory.java`, and `Main.java`). Put them in the same folder.
2.  **Compile It:** Open a terminal (or command prompt) and go to that folder. Then type:
    ```bash
    javac CalculatorException.java CalculatorHistory.java Main.java
    ```
3.  **Run It:** Type:
    ```bash
    java Main
    ```
4.  **Use It!**  Just follow the instructions on the screen. Type in your math problems, and it should give you the answer. Type "y" if you want to keep going, "n" to quit.

## How It Works (The Gist)

*   **`Main.java`:** This is where all the action happens. It asks for your input, does the calculations, shows you the results, and keeps track of the history.
*   **`CalculatorHistory.java`:** This class is like a little notebook that remembers your past calculations. It uses a list to store them.
*   **`CalculatorException.java`:** This is for errors. If something goes wrong (like you try to divide by zero), it throws one of these exceptions.

## Why I Did It This Way

*   **Classes:** I used classes to organize things. Like, the history stuff is all in the `CalculatorHistory` class, so it's not mixed up with everything else.
*   **Error Handling:** I wanted it to be a little bit robust, so it tries to catch errors and tell you what's wrong instead of just crashing.
*   **Keep It Simple:** I tried to keep the code relatively easy to understand, since it's for a beginner class.

## What I Learned / Challenges

*   **Parsing the Input:** Figuring out how to break down the math problem you type in was tricky.
*   **Order of Operations:** Making sure the calculator does things in the right order (multiplication before addition, etc.) took some thought.
*   **Making It Reliable:** Trying to handle all the possible things that could go wrong (bad input, etc.) was a lot of work.

## Files in This Project

*   `CalculatorException.java`:  Handles special calculator errors.
*   `CalculatorHistory.java`:  Keeps track of your calculation history.
*   `Main.java`:  The main program - handles input, output, and calculations.
*   `README.md`:  This file! Explains everything.

## Anything Else?

This was a fun project! I learned a lot about Java, object-oriented programming, and how to make a program that (hopefully) doesn't break too easily. If you have any questions or suggestions, feel free to let me know!
