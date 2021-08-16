## Cryptography

The Caesar Cipher is a great introduction to encryption, decryption, and code cracking, thanks to its simplicity.

### Encrypting a message
#### Imagine Caesar wants to send this message:
SECRET MEETING AT THE PALACE
#### Here's what that might look like encrypted:
YKIXKZ SKKZOTM GZ ZNK VGRGIK

### To make the encrypted message above, I shifted the alphabet by 6 and used this substitution table:
```
 A	B	C	D	E	F	G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W	X	Y	Z
```

```
G	H	I	J	K	L	M	N	O	P	Q	R	S	T	U	V	W	X	Y	Z	A	B	C	D	E	F
```

### Deciphering is done in reverse, with a right shift of 3.

The encryption can also be represented using modular arithmetic by first transforming the letters into numbers, according to the scheme, A → 0, B → 1, ..., Z → 25.[2] Encryption of a letter x by a shift n can be described mathematically as,[3]

{\displaystyle E_{n}(x)=(x+n)\mod {26}.}E_{n}(x)=(x+n)\mod {26}.
Decryption is performed similarly,

{\displaystyle D_{n}(x)=(x-n)\mod {26}.}D_{n}(x)=(x-n)\mod {26}.