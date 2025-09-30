# Chaining commands
## chaining~chaining-with-semicolons:~$ /challenge/pwn ;/challenge/college 
Yes! You chained /challenge/pwn and /challenge/college! Here is your flag:
pwn.college{gKUq6RQ0NKpVyf5pa8zm-S93HA3.QX1UDO0wCN1EzNzEzW}
## chaining~building-on-success:~$ /challenge/first-success && /challenge/second 
Nice chaining! Flag: pwn.college{UJjSN9tXPLYoI1lzqlStFOPdPuC.0lM0MDOxwCN1EzNzEzW}
## chaining~your-first-shell-script:~$ bash x.sh
pwn.college{Ua5W_JNBN1Oy9ndfrpsIdeuOFOm.QXxcDO0wCN1EzNzEzW}  
echo '/challenge/pwn ; /challenge/college' > x.sh
## chaining~executable-shell-scripts:~$ ./x.sh
Congratulations on your shell script execution! Your flag:
pwn.college{Y6931GsMHN5TAfAzI7zuHbPV5BA.QX0cjM1wCN1EzNzEzW}
## chaining~understanding-shebangs:~$ /challenge/run 
Flag: pwn.college{UOCx9i1mDUz9OH6vMvhH6UbAKEx.0VOzMDOxwCN1EzNzEzW}
## chaining~scripting-with-arguments:~$ echo -e 'echo "$2" "$1"'>solve.sh
hacker@chaining~scripting-with-arguments:~$ /challenge/run
Correct! Your script properly reversed the arguments.
Here's your flag:
pwn.college{oqTx_lCjX0Ajupg9aJnJ2gYV7bQ.0VNzMDOxwCN1EzNzEzW}
## chaining~scripting-with-conditionals:~$ 
echo -e 'if [ "$1" == "pwn" ]\nthen\n echo "college"\nfi' > /home/hacker/solve.sh
pwn.college{INVLX286xrWxApIpDPZZzEqHDva.0lNzMDOxwCN1EzNzEzW}  
## chaining~scripting-with-default-cases:~$echo -e 'if [ "$1" == "pwn" ]\nthen\n echo "college"\nelse echo "nope"\nfi' > /home/hacker/solve.sh
pwn.college{Yuu1EeABIr9RknDLK4Tw9MNgZKt.01NzMDOxwCN1EzNzEzW}
## chaining~scripting-with-multiple-conditions:~$ /challenge/run 
pwn.college{gZnEFNM_MhsQsm3IE4h_Oog9wfA.0FOzMDOxwCN1EzNzEzW}
## chaining~reading-shell-scripts:~$ /challenge/run 
pwn.college{gOrv9Cb8_mUl73kOQHT_MH2z3eB.0lMwgDOxwCN1EzNzEzW}


