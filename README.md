# raspberry-pi-demo-dictionary-attack
educational python project for Raspberry Pi OS demonstrating a dictionary attack using a wordlist


EXPLANATION

This program demonstrates how attackers perform an offline dictionary attack against hashed passwords. The password entered by the user is converted into a cryptographic hash using OpenSSL. John the Ripper then reads each candidate password from a wordlist, hashes each candidate using the same hashing algorithm and salt, and compares the resulting hash to the stored hash. If the generated hash matches the stored hash, John has identified the original password.
