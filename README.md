# Multiplication_table
Bash script for  generating a multiplication table.

> SCRIPT FLOW

A script file named "multiplication_table.sh" was created using command `touch multiplication_table.sh`

![image](./img/1.png)

1. A Shebang line was added to the very top of the script.

![image](./img/2.png)

2. Add a script prompting the user to enter a number for which the multiplication table will be generated.

![image](./img/3.png)

3. Ask the user if they want a full table (1 to 10) or a partial table.

![image](./img/4.1.png)

4. Use conditional logic to handle the user's choice.

![image](./img/5.png)

5. validate the range, invalide range will prompt the full table to show.

![image](./img/6.png)

6. Ensure the user inputs valid numbers.

![image](./img/7.png)

7a. Add a list form loop to generate the multiplication table based on the user's input.

![image](./img/12.png)

7b. Add a C-style for loop to generate the multiplication table based on the user's input.

![image](./img/8.png)


>Differnce between list form for loop and C-style for loop.

C-style for loop allows you to be abale to define the start, condition and increment in one line, while list form for loop is clearer to read.

>Execution

To execute this script command `chmod +x multiplication_table.sh
./multiplication_table.sh` will be used in terminal.

>Output

**Full multiplication table**

Showing full multiplication table of 4 from range 1-10

![image](./img/9.png)

**Partial multiplication table**

Showing partial multiplication table of 4 from range 3-6

![image](./img/10.png)

**Invalid range**

Showing partial multiplication table of 4 from range 8-3, because this was an invalid range the full muliplication table of 4 is displayed.

![image](./img/11.png)

