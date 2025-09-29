# File Globbing
## globbing~matching-with-:/challenge$ ./run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{4oh1c1TPdHUuaUrcD8OJnHoMCzS.QXxIDO0wCN1EzNzEzW}
## globbing~matching-with-:/challenge$ ./run
pwn.college{opSKKLtj3zSUlVTEf1_5o1s3oYN.QXyIDO0wCN1EzNzEzW}
## globbing~matching-with-:/challenge/files$ ../run file_[bash]
pwn.college{gZ2_GbHVAmaGZraPSBBLfRW0UmR.QXzIDO0wCN1EzNzEzW}
globbing where the argument matches any element from the list []
## globbing~matching-paths-with-:~$ /challenge/run /challenge/files/file_[bash]
pwn.college{IhPBsmGTazEy2FNO8Dre9n3XPQD.QX0IDO0wCN1EzNzEzW}
## globbing~multiple-globs:/challenge/files$ /challenge/run *p*
pwn.college{4yC_xbzvkqObCQI2KzoExaAaIbA.0lM3kjNxwCN1EzNzEzW}
## globbing~mixing-globs:/challenge/files$ /challenge/run [cpe]*
pwn.college{8wqxXCuC92eLuCuIUElvsyiDmhq.QX1IDO0wCN1EzNzEzW}
## globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]*
pwn.college{4_4-4ZqPUyt-1A66UaMwTMroIm1.QX2IDO0wCN1EzNzEzW}
## globbing~tab-completion:/challenge$ cat /challenge/pwncollege​ 
pwn.college{w8WUaePJ49mLaLjhqa3xPJkrO7K.0FN0EzNxwCN1EzNzEzW}
why??
## globbing~multiple-options-for-tab-completion:/challenge/files$ cat pwncollege-flag
pwn.college{4El_Gho3vJgtPO5UdsZetoUcF7Z.0lN0EzNxwCN1EzNzEzW}
## globbing~tab-completion-on-commands:~$ pwncollege-27018 
]pwn.college{AjKlvHEpbnXgvwEqu1LwOXcS6yA.0VN0EzNxwCN1EzNzEzW}
