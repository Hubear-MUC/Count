Count Version 2.3

This program counts upwards from 0 to 9.

    
  1  int i,a;
  2
  3  main()
  4  {
  5  for (i=0;i<9;++i)
  6  {
  7  a=i;
  8  }
  9  }



The counting itself has to be watched with a debugger.

Set a breakpoint to line 4 or 5.

Run the program and let it stop at the breakpoint set before.

Use the step- function of the debugger to step through the program and watch the value in variable a which will contain the latest value of the counting.

Also the next- function can be used to watch the content of variable a.



Version history:
----------------

Version 2.3

Added an empty line between the variable definitions and the operating code to make the program more readable and maintainable.


Verison 2.2

Placed the for- loop in the following line to make the code readable and maintainable
more propperly.


Version 2.1

Placed the closing curly bracket of main() in a seperate line to make the code more readable.

Version 2.1 works in the same way as version 2.0


Version 2.0

Replaced the counting by a for- loop.


Version 1.0

Initial version