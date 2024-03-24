# c-cpp
This repository empowers you to streamline your C and C++ development workflow within Visual Studio Code. It equips you with step-by-step instructions on

## Extensions
```
Code Runner
```

![Code_Runner](https://github.com/ibasloom/c-cpp/blob/main/Images/Code_Runner.png)
```
C/C++
```
![C/C++](https://github.com/ibasloom/c-cpp/blob/main/Images/C%3AC%2B%2B.png)

## ChatGPT Prompt

```
I need a C program that prints a right triangle of stars based on the user input.
```

```
#include <stdio.h>

int main() {
    int rows;

    // Prompt the user to enter the number of rows
    printf("Enter the number of rows for the right triangle: ");
    scanf("%d", &rows);

    // Loop to print the right triangle pattern
    for (int i = 1; i <= rows; ++i) {
        for (int j = 1; j <= i; ++j) {
            printf("* ");
        }
        printf("\n");
    }

    return 0;
}

```

```
#include <iostream>
using namespace std;

int main() {
    int rows;

    // Prompt the user to enter the number of rows
    cout << "Enter the number of rows for the right triangle: ";
    cin >> rows;

    // Loop to print the right triangle pattern
    for (int i = 1; i <= rows; ++i) {
        // Inner loop to print stars in each row
        for (int j = 1; j <= i; ++j) {
            cout << "* ";
        }
        // Move to the next line after each row
        cout << endl;
    }

    return 0;
}

```


```
Could you please provide a C++ program that calculates the factorial of a number?
```

```
#include <iostream>
using namespace std;

// Function to calculate factorial
int factorial(int n) {
    if (n == 0 || n == 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}

int main() {
    int num;

    // Prompt the user to enter the number
    cout << "Enter a number to calculate its factorial: ";
    cin >> num;

    // Calculate factorial
    int result = factorial(num);

    // Display the result
    cout << "Factorial of " << num << " = " << result << endl;

    return 0;
}
```
