# 2016 Text Only Challenges

This is the repository for all challenges which were simply text based.

## Grab Bag 10

The flag at the time could be found on the rules page for the 2016 CTF. An archival copy can be found [here](https://github.com/mitre-cyber-academy/mitre-cyber-academy.github.io/blob/09cb31f19b5ebd6c940f5333702fc797cb90b47f/competitions/rules/index.html#L53).

**Flag:** 55572e792981f50145f75649f53fcd3c

## Crypto 50

Problem: The key is not MCA-3CD9E73E
Solution: `ruby -e "puts 'MCA-' + (0x3CD9E73E ^ 0xFFFFFFFF).to_s(16)"`

**Flag:** MCA-C32618C1

## Crypto 100

This is a null cipher (https://en.wikipedia.org/wiki/Null_cipher) the result sentence is encoded into the first letter of each word in the provided sentence.

FLAG = MCA ABBFACFF

"The hour ended, running eternally south", uttered Lance, "This is never good. Kerosene's everywhere, Yikes! It's stupid man."
Creating another anthropomorphic baseball bat for another creepy, freaky fella. Yippy! Oscar! Umbrellas are rare except
when everyone lets Canadian orangutans misspell "electroencephalograms"

They will get this

"The Resulting Key Is MCA ABBFACFF you are welcome"

**Flag:** MCA-ABBFACFF

## Crypto 200

The players are provided with the plaintext "Attack at dawn" and the ciphertext which is generated using a cipher. The users have to derive the key used to encrypt the text from. This could be as simple as saying:

Plaintext: "Attack at dawn"
Ciphertext: "mvt-7k 5l :coo"
**Key:** MCA-5A597C9B
See http://www.cs.du.edu/~snarayan/crypt/vigenere.html for vinegere cipher

**Flag:** Is also the key which is MCA-5A597C9B