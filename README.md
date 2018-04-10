# ppcryptopython
### Overview
```
import hashlib
hashlib.new("md4","x".encode("utf-16le")).hexdigest()
```

test
```
from Crypto.Cipher import AES
key = "key"
plain = "plain"
cipher = AES.new(key)
ciphertext = cipher.encrypt(plain)
print ciphertext.encode("hex")
cipher.decrypt(ciphertext)
```

### Caesar Cipher and ROT13
```
alpha = "ABCDE"
str_in =input("please input str")
n = len(str_in)
str_out=""
for i in range(n):
  c = str_in[i]
  loc = alpha.find(c)
  print i,c,loc,
  newLoc = loc+3
  str_out+=alpha[newloc]
  print newloc, str_out
```
