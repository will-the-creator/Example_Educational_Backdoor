# Example_Educational_Backdoor

This repository contains a simple C-based backdoor for **educational purposes only**.  
It is intended for security research and demonstration in controlled environments.

use resposibly

# to run
gcc -o Basic_Educational_Backdoor Basic_Educational_Backdoor.c

strip Basic_Educational_Backdoor

./Basic_Educational_Backdoor

# how to use
after running './Basic_Educational_Backdoor'

open a new terminal

run 'nc 127.0.0.1 12345'
you can then send a signal to the system useing 'ping'
you should receive a signal back 'pong'
