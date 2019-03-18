# sketchy_password_generator
Mitchell / Isthmus Feb 2019

Short and sweet bash script to make passwords from sha256 sums. Not audited, not recommended for use, not approved for internal consumption.

```
$ ./SHAscript.sh 
Type message string, press [enter]
MyPasswordForServiceX

bf869ef183381e5fa14fba19f4d7e6a14bde3314febcbda8a01502e5f5eeab2e  -
chars:   ^10       ^20       ^30       ^40       ^50       ^60

Press [enter] to clear the screen
```

For shorter passwords, collect characters from start to carrot. e.g. the 20 character output would be
`bf869ef183381e5fa14f`

# Seriously don't use this yet
The script is internally reproducible, however the hash for `MyPasswordForServiceX` should actually be `08EF0E123982FB876B4390ED23BAC5A20E39F5A7D7205372AA6A5763591B4E2B`
