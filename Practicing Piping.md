# Practicing Piping
## piping~redirecting-output:~$ echo PWN > COLLEGE
pwn.college{UrZ-SyK1KGAuUnSsWZayIDY2Dzv.QX0YTN0wCN1EzNzEzW}
## piping~redirecting-more-output:~$ cat myflag
pwn.college{QgpyIPgrUkKhUS7m3BE0DoQPtWg.QX1YTN0wCN1EzNzEzW}
## piping~appending-output:~$ cat the-flag 
pwn.college{sHtxg8kBCLlpGFvWdlA7V6Z9M3R.QX3ATO0wCN1EzNzEzW}
'>>' for appending
## piping~redirecting-errors:~$ cat myflag 
[0,1,2]> for std[in,out,err]
pwn.college{046HUnmQT0qxpPsHrgmi2I2-cyS.QX3YTN0wCN1EzNzEzW}
## piping~redirecting-input:~$ /challenge/run < PWN
pwn.college{YBJ2t9mWy2HhCyeECvI_-SYekEW.QXwcTN0wCN1EzNzEzW}
## piping~grepping-stored-results:~$ grep pwn.college /tmp/data.txt  
pwn.college{cut2iNPlJKe4wKNlLMps7_siZLK.QX4EDO0wCN1EzNzEzW}
## piping~grepping-live-output:~$ /challenge/run|grep pwn.college  
pwn.college{sxMaR0Rru8wkolz1g4pXMzqVCaA.QX5EDO0wCN1EzNzEzW}

