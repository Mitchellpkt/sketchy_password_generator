# sketchy_password_generator
Short and sweet bash script to make passwords from sha256 sums. Not audited, not recommended for use, not approved for internal consumption.

```
$ ./SHAscript.sh 
Type message string, press [enter]
MyPasswordForServiceX  

./SHAscript.sh: line 6: MyPasswordForServiceX: command not found
e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855  -
chars:   ^10       ^20       ^30       ^40       ^50       ^60

Press [enter] to clear the screen
```

For shorter passwords, collect characters from start to carrot. e.g. the 20 character output would be
`e3b0c44298fc1c149afb`
