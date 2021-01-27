Count Version 2.2

This program counts upwards from 0 to 9.

    
  1  int i,a;
  2  main()
  3  {
  4  for (i=0;i<9;++i)
  5  {
  6  a=i;
  7  }
  8  }



The counting itself has to be watched with a debugger.

Set a breakpoint to line 3 or 4 and run the program.

Run the program and let it stop at the breakpoint set before.

Use the step- function to step through the program and watch the value in 
variable a which will contain the latest value of the counting.

Also the next- function can be used to watch the content of variable a.



Version history:
----------------

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