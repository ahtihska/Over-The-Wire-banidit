## Contents
* [Level 0](#level-0)
* [Level 0 - Level 1](#level-0---level-1)
* [Level 1 - Level 2](#level-1---level-2)
* [Level 2 - Level 3](#level-2---level-3)
* [Level 3 - Level 4](#level-3---level-4)
* [Level 4 - Level 5](#level-4---level-5)
* [Level 5 - Level 6](#level-5---level-6)
* [Level 6 - Level 7](#level-6---level-7)
* [Level 7 - Level 8](#level-7---level-8)
* [Level 8 - Level 9](#level-8---level-9)
* [Level 9 - Level 10](#level-9---level-10)
* [Level 10 - Level 11](#level-10---level-11)
* [Level 11 - Level 12](#level-11---level-12)
* [Level 12 - Level 13](#level-12---level-13)
* [Level 13 - Level 14](#level-13---level-14)
* [Level 14 - Level 15](#level-14---level-15)
* [Level 15 - Level 16](#level-15---level-16)
* [Level 16 - Level 17](#level-16---level-17)
* [Level 17 - Level 18](#level-17---level-18)
* [Level 18 - Level 19](#level-18---level-19)

## Level 0

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: bandit0
```


## Level 0 - Level 1
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```

## Level 1 - Level 2
The password for the next level is stored in a file called - located in the home directory
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```


## Level 2 - Level 3
The password for the next level is stored in a file called spaces in this filename located in the home directory
```
ssh bandit1@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```


## Level 3 - Level 4
The password for the next level is stored in a hidden file in the inhere directory.
```
ssh bandit3@bandit.labs.overthewire.org -p 2220
Password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```


## Level 4 - Level 5
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.
```
ssh bandit4@bandit.labs.overthewire.org -p 2220
Password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```

## Level 5 - Level 6
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
<br>
human-readable
<br>
1033 bytes in size
<br>
not executable
```
ssh bandit5@bandit.labs.overthewire.org -p 2220
Password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```


## Level 6 - Level 7
The password for the next level is stored somewhere on the server and has all of the following properties:
<br>
owned by user bandit7
<br>
owned by group bandit6
<br>
33 bytes in size
```
ssh bandit6@bandit.labs.overthewire.org -p 2220
Password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```

## Level 7 - Level 8
The password for the next level is stored in the file data.txt next to the word millionth
```
ssh bandit7@bandit.labs.overthewire.org -p 2220
Password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```

## Level 8 - Level 9
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once
```
ssh bandit8@bandit.labs.overthewire.org -p 2220
Password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```


## Level 9 - Level 10
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.
```
ssh bandit9@bandit.labs.overthewire.org -p 2220
Password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```

## Level 10 - Level 11
The password for the next level is stored in the file data.txt, which contains base64 encoded data
```
ssh bandit10@bandit.labs.overthewire.org -p 2220
Password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
```


## Level 11 - Level 12
The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions
```
ssh bandit11@bandit.labs.overthewire.org -p 2220
Password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```

## Level 12 - Level 13
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)

```
ssh bandit12@bandit.labs.overthewire.org -p 2220
Password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
```


## Level 13 - Level 14
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on
```
ssh bandit13@bandit.labs.overthewire.org -p 2220
Password: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
```


## Level 14 - Level 15
The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.
```
ssh bandit14@bandit.labs.overthewire.org -p 2220
Password: 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```



## Level 15 - Level 16
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL encryption.

Helpful note: Getting “HEARTBEATING” and “Read R BLOCK”? Use -ign_eof and read the “CONNECTED COMMANDS” section in the manpage. Next to ‘R’ and ‘Q’, the ‘B’ command also works in this version of that command
```
ssh bandit15@bandit.labs.overthewire.org -p 2220
Password: BfMYroe26WYalil77FoDi9qh59eK5xNr
```

## Level 16 - Level 17
The credentials for the next level can be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.
```
ssh bandit16@bandit.labs.overthewire.org -p 2220
Password: cluFn7wTiGryunymYOu4RcffSxQluehd
```


## Level 17 - Level 18
There are 2 files in the homedirectory: passwords.old and passwords.new. The password for the next level is in passwords.new and is the only line that has been changed between passwords.old and passwords.new

NOTE: if you have solved this level and see ‘Byebye!’ when trying to log into bandit18, this is related to the next level, bandit19.
```
ssh bandit17@bandit.labs.overthewire.org -p 2220
Password: xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn
```


## Level 18 - Level 19
The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.
```
ssh bandit18@bandit.labs.overthewire.org -p 2220
Password: kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
```
