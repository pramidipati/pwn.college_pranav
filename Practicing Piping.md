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
## piping~grepping-errors:~$ /challenge/run 2>&1 | grep pwn.college
pwn.college{0NmoNE_KTbkSq9keAYD7-ymcPVH.QX1ATO0wCN1EzNzEzW}
## piping~filtering-with-grep-v:~$ /challenge/run|grep -v DECOY
pwn.college{cYoq3XYabokG3MyxDttd_8v__Zm.0FOxEzNxwCN1EzNzEzW}
## piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret c8gr3_GV | /challenge/college
pwn.college{c8gr3_GVVV5I-vUnQ1HVfUO0th4.QXxITO0wCN1EzNzEzW}  
tee is a splliter of the output of command 1 which sends the output to multiple arguments
## piping~process-substitution-for-input:~$ diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)
 pwn.college{0ejiuZnQ0yvK_3pGvZvJbK3_fJ-.0lNwMDOxwCN1EzNzEzW}  
pipe: cmd2 reads stdin  
cmd1 | cmd2  
process substitution: cmd2 is given a filename it can open  
cmd2 <(cmd1)
## piping~writing-to-multiple-programs:~$ /challenge/hack | tee >(/challenge/the) >(/challenge/planet) 
pwn.college{kdgq3wpnyoezC9w6UoRGKVG3EEq.QXwgDN1wCN1EzNzEzW}
## piping~split-piping-stderr-and-stdout:~$ /challenge/hack  2> >(/challenge/the) 1> >(/challenge/planet) 
pwn.college{A-DcKXosUkKyUzcSgiWB2fiE8Vn.QXxQDM2wCN1EzNzEzW}
## piping~named-pipes:~$ cat /tmp/flag_fifo
You've correctly redirected /challenge/run's stdout to a FIFO at 
/tmp/flag_fifo! Here is your flag:
pwn.college{8iiM47dAntvyQvyGZBv3yPkwlKK.01MzMDOxwCN1EzNzEzW}  
Named fifos only work when the stdin and stdout are both connected for this pipe



