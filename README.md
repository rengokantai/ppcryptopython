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
