In C++, loops are used to execute a block of code repeatedly. Here are the main types of loops in C++ along with explanations:

1. **`for` Loop:**
   - The `for` loop is used when the number of iterations is known beforehand.
   - Syntax:
     ```cpp
     for (initialization; condition; update) {
         // code to be executed
     }
     ```
   - Example:
     ```cpp
     for (int i = 0; i < 5; ++i) {
         cout << i << " ";
     }
     // Output: 0 1 2 3 4
     ```

2. **`while` Loop:**
   - The `while` loop is used when the number of iterations is not known beforehand, and the loop continues as long as the condition is true.
   - Syntax:
     ```cpp
     while (condition) {
         // code to be executed
     }
     ```
   - Example:
     ```cpp
     int i = 0;
     while (i < 5) {
         cout << i << " ";
         ++i;
     }
     // Output: 0 1 2 3 4
     ```

3. **`do-while` Loop:**
   - The `do-while` loop is similar to the `while` loop, but the block of code is executed at least once, as the condition is checked after the execution.
   - Syntax:
     ```cpp
     do {
         // code to be executed
     } while (condition);
     ```
   - Example:
     ```cpp
     int i = 0;
     do {
         cout << i << " ";
         ++i;
     } while (i < 5);
     // Output: 0 1 2 3 4
     ```

4. **`range-based for` Loop:**
   - Introduced in C++11, the `range-based for` loop simplifies iteration over a range, such as elements of an array or a container.
   - Syntax:
     ```cpp
     for (element_type element : range) {
         // code to be executed
     }
     ```
   - Example:
     ```cpp
     int arr[] = {1, 2, 3, 4, 5};
     for (int x : arr) {
         cout << x << " ";
     }
     // Output: 1 2 3 4 5
     ```

5. **Loop Control Statements:**
   - C++ provides loop control statements like `break` and `continue`:
     - **`break`:** Exits the loop prematurely.
     - **`continue`:** Skips the rest of the code inside the loop for the current iteration and moves to the next iteration.

   ```cpp
   for (int i = 0; i < 10; ++i) {
       if (i == 5) {
           break; // exit loop when i is 5
       }
       if (i % 2 == 0) {
           continue; // skip even numbers
       }
       cout << i << " ";
   }
   // Output: 1 3
   ```

Understanding these loop structures and control statements allows you to efficiently control the flow of execution in your C++ programs.
