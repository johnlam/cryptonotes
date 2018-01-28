# Crypto - 101

### Pre-requisites

 * Python
 * pip install bcrypt pynacl cryptography

### ALWAYS USE LIBSODIUM/NACL

*Never roll your own crypto.* (unless you want to learn how things work)
*Avoid messing with primitives* or libs that require args that you don't understand.

### Our Characters
 * Alice
 * Bob
 * Eve

Alice wants to communicate with Bob. Eve (the eavesdropper) can listen to what they "say".

### Types of encryption
https://ico.org.uk/for-organisations/guide-to-data-protection/encryption/types-of-encryption/

##### Symmetric
Alice and Bob know the key to encrypt their data.
The key doesn't change and has been shared out of band (e.g. verbally at the pub)

AES

##### Assymetric
Alice and Bob don't have a key to encrypt their data.



##### Hashing
Not all hash functions are created the same.

### Above all NaCL (libsodium)
A bunch of godlike cryptographers made a lib, humans made bindings to these libs. Use them. https://download.libsodium.org/doc/bindings_for_other_languages/




### # The connection to this site is encrypted and authenticated using TLS 1.2 (a strong protocol),
# ECDHE_RSA with X25519 (a strong key exchange), and AES_128_GCM (a strong cipher).

### let's talk certs and openssl
