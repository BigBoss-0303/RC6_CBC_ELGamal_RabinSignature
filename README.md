RC6-Block-Cipher with EC-El-Gamal key encryption & Rabin Signature
================

Implementation of RC6 Block-Cipher encryption and decryption with EC-El-Gamal key encryption & Rabin Signature in Python.

## Specification

#### RC6:
* W = 32  // word size in bits
  
* R = 12  // number of rounds

* B = 16  // key size in bytes

* Block size : 4*32 bit blocks

#### EC-El-Gamal:


#### Rabin:


## Functions

* encrypt.py and decrypt.py are used to encrypt and decrypt using user input

* ecElgamal.py is used to encrypt and decrypt the RC6's key using Elliptic curve

* rabinSignature.py is used to sign and verify the signature of the input message 

* helper.py contains helper functions

## Getting started

* Install the python package "tinyec" (pip install tinyec).

* Run the program:
  * To encrypt & decrypt a message, run encrypt.py & decrypt.py together. 
     
