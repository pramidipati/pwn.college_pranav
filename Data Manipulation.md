# Data Manipulation
## hacker@data~translating-characters:~$ /challenge/run | tr 'a-z''A-Z' 'A-Z''a-z'
yOUR CASE-SWAPPED FLAG:
pwn.college{0jpPFHWmBV4uDXlxkJgVJXtPbvu.01MxEzNxwCN1EzNzEzW}
## data~deleting-characters:~$ /challenge/run | tr -d '^%'
Your character-stuffed flag:
pwn.college{EftjJ5UiQM2IUVhI1HVWONyhF6U.0FNxEzNxwCN1EzNzEzW}
## hacker@data~deleting-newlines:~$ /challenge/run | tr -d '\n'
Your line-split flag: 
pwn.college{4Qm8KAxcVEEEYPB30hzVfL5NLyR.0VNxEzNxwCN1EzNzEzW}
## hacker@data~extracting-the-first-lines-with-head:~$ /challenge/pwn | head -n 7 | /challenge/college
Congratulations, you piped the right codes!
pwn.college{MBzkySWEsi9PddxJ94SegKNmyRR.0lNxEzNxwCN1EzNzEzW}
## hacker@data~extracting-specific-sections-of-text:~$ /challenge/run | cut -d " " -f 2 | tr -d "\n"
pwn.college{0Wff1oONt2T65DhC_nEJhVNPb_w.01NxEzNxwCN1EzNzEzW}
## data~sorting-data:~$ sort -r /challenge/flags.txt
pwn.college{E_pvba3eFG2Y91J53T-ZUtvnk5N.0FM0MDOxwCN1EzNzEzW}
