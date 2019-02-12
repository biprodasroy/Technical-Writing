## Sample Program
> দুটি intiger ইনপুট নিয়ে sum আউটপুটে প্রিন্ট করো।
```bash

// ইনপুট-আউটপুট লাইব্রেরী ইনঙ্লুড করি
#include<stdio.h>

int main(){
    # দুটো ইন্টিজার টেইপের ভেরিয়েবল ডিক্লিয়ার করি
    int x, y;

    # x এর মান ইনপুট নিতে বলি
    printf("Enter a value of x: ");

    # x এর মান ইনপুট নিই
    scanf("%d",&x);

    # y এর মান ইনপুট নিতে বলি
    printf("Enter a value of y: ");

    # y এর মান ইনপুট নিই
    scanf("%d",&y);

    # x ও y এর মান জোগ করে sum ভেরিয়েবলে রাকি
    int sum = x + y;

    # Sum প্রিন্ট করি
    printf("Sum of x & y is %d", sum);
}
```
- `include`: Library include করার জন্য
- `stdio.h`: Standard Input/Output header file
- `main`: `main` is a function. Each program start from `main`. For each `C` program, there must be one `main` function.
- `int` referes Integer type. `char` referes Character type. `float` refers Float (real number) type.
- `x`, `y` is called variable. Variable store data
- `printf` is a function defined in `stdio.h`. `printf` used for outputting something
- `scanf` is a function defined in `stdio.h`. `scanf` used for inputting something



## How computer program works??
1. Each program start from main program
2. Compiler process each statement line-by-line.
3. program end with return 0



### function: A function do 3 things.
1. Input 
2. Process
3. Output

```bash
# Function structure
output function(input){
    process
} 

```

- main is also a function. So, main input something, process the code and out the result.
```bash
# Main function structure
output main(input){
    process
}

# Main function sample
int main(){
    // process code
    return 0;
}
```