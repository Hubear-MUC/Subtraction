Subtraction 3.0
---------------

Two numbers given as arguments are subtracted and the result will be shown 
in the terminal.

The second number given will be subtracted from the first one.

The new feature is that the number from which is subtracted and the number
that is to be subtracted can be given as arguments at the command line when 
the program is invoked.

It will be assumed that the name of the program file after compilation will be

  subtract


Just invoke like

  ./subtract number1 number2

for example

  ./subtract 5.80 6.95

And the result will be shown on the terminal.
The numbers are represented as double- values.

If too few arguments are given, the program aborts without telling a result.

The interactive mode that enabled entering the numbers after invocation with
"in: " prompts got removed because the subtraction of two numbers certainly is
not regarded as a big task and it was considered more comfortable to pass the
two numbers just at the invocation.



Version history:
----------------

Implementation of the number entry as arguments at invocation.
Termination of the program if too less data is entered.