# goto statement in C/C++

The goto statement is a jump statement which is sometimes also referred to as unconditional jump statement. The goto statement can be used to jump from anywhere to anywhere within a function.

**Syntax** :

![](https://github.com/AswinS07/C_programming/tree/82e0997762ed854b7866a18af2d94261b81a2838/_includes/goto_syntax.png)

In the above syntax, the first line tells the compiler to go to or jump to the statement marked as a label. Here label is a user-defined identifier which indicates the target statement. The statement immediately followed after 'label:' is the destination statement. The 'label:' can also appear before the 'goto label;' statement in the above syntax.

![](https://github.com/AswinS07/C_programming/tree/82e0997762ed854b7866a18af2d94261b81a2838/_includes/flowchart_goto_statement.png)

Below are some examples on how to use goto statement:

**Examples:**

* **Type 1 :**

  In this case, we will see a situation similar to as shown in Syntax1 above. Suppose we need to write a program where we need to check if a number is even or not and print accordingly using the goto statement. Below program explains how to do this:

![](https://github.com/AswinS07/C_programming/tree/82e0997762ed854b7866a18af2d94261b81a2838/_includes/goto_example1.png) **Output:** ![](https://github.com/AswinS07/C_programming/tree/82e0997762ed854b7866a18af2d94261b81a2838/_includes/goto_out1.png)

* **Type 2: :**

  In this case, we will see a situation similar to as shown in Syntax1 above. Suppose we need to write a program which prints numbers from 1 to 10 using the goto statement. Below program explains how to do this.

![](https://github.com/AswinS07/C_programming/tree/82e0997762ed854b7866a18af2d94261b81a2838/_includes/goto_example2.png)

**Output:** 

## **Disadvantages of using goto statement:**

* The use of goto statement is highly discouraged as it makes the program logic very complex.
* use of goto makes the task of analyzing and verifying the correctness of programs \(particularly those involving loops\) very difficult.
* Use of goto can be simply avoided using break and continue statements.

