<div align="center">
<h1>OverTheWire</h1>
<b> Bandit </b>
</div>

<br>

[Website](http://overthewire.org/wargames/bandit)


Level 0:
<br>
The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: bandit0
```


Level 0 - Level 1:
<br>
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```


Level 1 - Level 2:
<br>
The password for the next level is stored in a file called - located in the home directory
```
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```


Level 2 - Level 3:
<br>
The password for the next level is stored in a file called spaces in this filename located in the home directory
```
ssh bandit1@bandit.labs.overthewire.org -p 2220
Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```


Level 3 - Level 4:
<br>
The password for the next level is stored in a hidden file in the inhere directory.
```
ssh bandit3@bandit.labs.overthewire.org -p 2220
Password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```


Level 4 - Level 5:
<br>
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.
```
ssh bandit4@bandit.labs.overthewire.org -p 2220
Password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```


Level 5 - Level 6:
<br>
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


Level 6 - Level 7:
<br>
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


Level 7 - Level 8:
<br>
The password for the next level is stored in the file data.txt next to the word millionth
```
ssh bandit7@bandit.labs.overthewire.org -p 2220
Password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```


Level 8 - Level 9:
<br>
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once
```
ssh bandit8@bandit.labs.overthewire.org -p 2220
Password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```


Level 9 - Level 10:
<br>
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.
```
ssh bandit9@bandit.labs.overthewire.org -p 2220
Password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```
