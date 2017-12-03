we are planning to use 3 components:
main-parser - that will read the code and seperate it into lines L1..LN (using spoon?)
add all the variables into some data structure (named DS)
foreach line Li
         foreach variable V in DS check if V in Li
		if true - need to check the var is V value is used (in some arithmetic way)


basic funcions:
1. for line L and variable A - is A c-use?
2. for some A1..An variables - active func 1
3. for some lines L1..Ln - active func 2
4. need some parsing - keep it in data structure.

testing:
project phases:
creating a first test - "int x = 3;   \n x++;" - check if it's work
creating another test - "if (true) x++;"
creating another test - "if (false) x++;"
try to work with more then one variable.


need to check how to work with spoon :)