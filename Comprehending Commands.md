# Comprehending Commands
## cat-not-the-pet-but-the-command:~$ cat flag
pwn.college{wPgsRcz1W-B-fys7HebvnmlZ48y.QXxcTN0wCN1EzNzEzW}  
Using the cat command to read files
## catting-absolute-paths:~$ 
pwn.college{kfI6C8PN9zVoWD_AIlMpNsHTAqV.QX5ETO0wCN1EzNzEzW}  
absolute path as an argument for cat
## more-catting-practice:~$ 
pwn.college{kljdcGMucEPPNcP9DqW8_iFGOe9.QXwITO0wCN1EzNzEzW}  
same as before
## grepping-for-a-needle-in-a-haystack:~$ 
pwn.college{kezshuhwhlYj_oNKWUTxInxLk4H.QX3EDO0wCN1EzNzEzW}  
extracting particular lines that have the substring, following is the way to do so  
grep SEARCH_STRING /path/to/file
## comparing-files:~$ 
pwn.college{0hjN2SdhjW96SUoaGl8n9nMoz1A.01MwMDOxwCN1EzNzEzW}  
using diff to see differenceces in two text files. Typical output is like <1a2> or <2c2> followed by < reffering to the first file and > to the latter . a,c,d:add delete change
## listing-files
pwn.college{4rmKZoCXh6F7ZOvGPNixM_dKPLU.QX4IDO0wCN1EzNzEzW}  
listing the files and subdirectories in the directory using ls  
## touching-files:/tmp$ 
pwn.college{IY0k07uGnnkCyYvCh9Qx8JL6rxQ.QXwMDO0wCN1EzNzEzW}  
touch=creating text files
## removing-files:~$
pwn.college{8Yp2Wzvx7ZgD47F81Ybxlg7-snr.QX2kDM1wCN1EzNzEzW}  
rm file_name
## moving-files:/$ /challenge/check
pwn.college{QKuBokzytv3KhZLD68o3b7qNRxH.0VOxEzNxwCN1EzNzEzW}  
moving files with mv : mv source target
## hidden-files:/$
pwn.college{g5Qxo21g2A-X4Is7a4CniS4eXsO.QXwUDO0wCN1EzNzEzW}  
ls -a for hidden files
## an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/char/agp$ 
pwn.college{0-b4y8sfZX-AsqVgzxcv9w_1bQt.QX5IDO0wCN1EzNzEzW}  
## making-directories:/tmp/pwn$ /challenge/run
pwn.college{08PV4abgz7tlDdwsXwXlN0hVH7s.QXxMDO0wCN1EzNzEzW}  
making directories : mkdir  
## hacker@commands~finding-files:~$ 
pwn.college{cHF3rRek4bWmyE-B9twWC25jOlV.QXyMDO0wCN1EzNzEzW}  
finding files : find location -name file_name  
## commands~linking-files:~$ /challenge/catflag
pwn.college{4AIptr2jBn-06wMu6z-asawA-CO.QX5ETN1wCN1EzNzEzW}  
linked the file which did not have the flag to one which did  
direntry → inode → data blocks  
Hardlink Softlink  
Works across filesystems?	 No	 Yes  
Can link directories?	 No	 Yes  
Storage overhead	Very small	Small (stores path string)  
