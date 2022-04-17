#blue
$IP Address
```
10.10.208.166
```

#Task 1

1. How many port open? 
```
3
```

2. what is machine vulnerable to?
```
ms17-010
```

#Task 2

1. What is the full of the code? (exploitation code)
```
exploit/windows/smb/ms17_010_eternalblue
```

2. Name of this value (show option adn set the one required value)?
```
RHOSTS
```
#Task 3

1. What is the name of the post module we will use? (Exact path, similar to the exploit we previously selected)
```
post/multi/manage/shell_to_meterpreter
```
2. Select this (use MODULE_PATH). Show options, what option are we required to change?
```
SESSION
```
#Task 4

1. What is the name of the non-default user?
```
jon
```
2. what is the cracked password?
```
alqfna22
```
#Task 5

1. flag 1?
```
flag{access_the_macine}
```
2. flag 2?
```
flag{sam_database_elevated_access}
```
3. flag 3?
```
flag{admin_documents_can_be_valuable}
```