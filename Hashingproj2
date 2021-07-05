import hashlib

print(hashlib.algorithms_available)

value = 'Archana'
val = value.encode()

print('First hash value using sha1 algorithm :',hashlib.sha1(val).hexdigest())

print('Second hash value using sha224 algorithm :',hashlib.sha224(val).hexdigest())

print('Third hash value using shake_256 algorithm :',hashlib.shake_256(val).hexdigest(10))