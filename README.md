Question : - 

1. Please write a simple CLI application in the language of your choice that does the following:
Print the numbers from 1 to 10 in random order to the terminal.
Please provide a README, that explains detailed how to run the program on MacOS and Linux

solution : -

1.By default MacOS and Linux distu come with python version 2. So Dont need to install it on the system.
2. Open a file with vi editor, write my code and save it as .py extention.

<Command shell in MacOS/Linux>

Emran:Desktop emran$ vi random-number.py 
#!/usr/bin/env python2
import random
for i in range(10):
    print random.randint(1, 10)

3. run the  created script as below and will get the random number between 1 to 10.

<Command shell in MacOS/Linux>  

Emran:Desktop emran$ python2 random-number.py  
1
7
3
8
7
3
5
10
4
2
