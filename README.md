# Elgamal_ECC
**Elliptic curve cryptography simulating Elgamal encryption and decryption**
=========================================================================


**Steps:**

1) Sync the code:

  git clone https://github.com/snehamaganahalli/Elgamal_ECC.git
  
2) Install necessary libraries:

  sudo apt-get install libssl-dev

  sudo apt-get install libgmp3-dev

3) Compile the code

  gcc elgamal_ecc.c -lssl -lgmp

4) Run

./a.out

=========================================================================

**Sample Output:**

p = 1332297598440044874827085558802491743757193798159

x = 707063202426763381591074511839286558424752204273

Base point P = (1089473557631435284577962539738532515920566082499,127912481829969033206777085249718746721365418785)

Public key xP =  (109249117715726311040932556094923803628298987195,645861170542939148329571376570715355545531243515)


Enter 1 to encrypt and 0 to decrypt:1

Enter Plain text in the form of point P(x,y) Usage:x,y

**5,4**

Encrypting!!!!!!!!!!!!!!!!!

Encrypted: (5,4)

Ephemeral key = 840298544949172379633860894746432306428340117455

Cipher C1: (538471493586195987330618897320858017779395776159,116170739782514136268746526886342613561415957913)

Cipher C2 with msg: (416868656276829510925798625100180895875100618915,686129939066707432932371384712198606964904405658)

Enter 1 to encrypt and 0 to decrypt:0

Enter cipher text C1, C2 in the form of point P(x,y)

Enter C1. Usage:x,y

**538471493586195987330618897320858017779395776159,116170739782514136268746526886342613561415957913**

Enter C2. Usage:x,y

**416868656276829510925798625100180895875100618915,686129939066707432932371384712198606964904405658**

Decrypting!!!!!!!!!!!!!!!!!

D1=(56239879971296780100587766166067413140932852336,840587705443433119774933853606146138452359903420)

Decrypted: (5,4)


=========================================================================

**Name: Sneha Maganahalli Rajendranath**

**Roll No: CS21M522**
