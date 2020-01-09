Extra resourse:
https://www.youtube.com/watch?v=Pl8OlkkwRpc
Questions:
1. What is the number of leading zeros currently used in the hash for Bitcoin?
17

2. What is the desired time required to find a Hash in Bitcoin?
10 min 

3. Does a change in a Private Key affect the blockchain as in the case of the public key?
If the private key and public key connected. If the private key chanched public key supposed to have refresh too. 

4. Is a Public Key uniquely linked to a private key?
Public key can be shared to others but combination is unique for every operation and user. 

5. Who/What changes the bitcoin difficulty?
difficulty = difficulty_1_target / current_target
The difficulty adjusts every 2016 blocks (roughly every 2 weeks).

6. How many miners (i.e. processing power) are currently needed to run the 51% attack?
At present you need 12.42 TH/s to pull off a 51% attack. 
Since power efficiency will be HUGE for this scale of an operation, let's use the most power efficient card we can find. This lovely pastebin doc tells us that is the Radeon 5850 at 1.595 MH/W.

At present you need 12.42 TH/s to pull off a 51% attack, which would require 51,585 of these cards. Assuming we put four cards to a rig it also requires 12,897 computers to run them all. Assuming the PCs take a scant 200 watts, each rig requires 804 watts of power, 10,365,735 watts in all. Assuming a fairly high efficiency cooling system, we can bump that up to about 14,619,916 watts. Before anyone claims that this alone is impossible, keep in mind it's about 0.7% of the peak output of Hoover Dam. Speaking of Hoover Dam, I'm going to use my local energy rate of 11.28 cents per kW/h (I live in Vegas) to find that it would cost $39,579.04 to run and cool these rigs for a single day.

7. What are some possible attacks on a blockchain? Hacking a major company which handles wallets, sends bitcoins, stores major blockhains, etc.
Eclipse attack, Selfish mining attack, Finney attack, The DAO attack, Parity Multisig Wallet Attack.

8. Are there major bitcoin servers?
AntPool
Slush Pool
F2Pool
BTCC Pool
Eligius
BTC.com
BW Pool

9. Distribution of bitcoin owners?
So, the address which is the 149,238'th richest contains exactly 10 Bitcoins. That address is at 0.76% in the distribution. The address at 1% is in the 1–10 bracket and will contain a little less than 10 Bitcoins.

10.What is a Merkle tree?
In cryptography and computer science, a hash tree or Merkle tree is a tree in which every leaf node is labelled with the hash of a data block, and every non-leaf node is labelled with the cryptographic hash of the labels of its child nodes. Hash trees allow efficient and secure verification of the contents of large data structures. Hash trees are a generalization of hash lists and hash chains.

PuTTYgen
Its an app to generate public and private key. 
PuTTYgen - utility for generating RSA and DSA keys (puttygen.exe)
It is analogous to the ssh-keygen tool used in some other SSH implementations.
The basic function is to create public and private key pairs. PuTTY stores keys in its own format in .ppk files. However, the tool can also convert keys to and from other formats.
PuTTYgen.exe on Windows is a graphical tool. A command-line version is available for Linux.
The PuTTYgen app is part of the PuTTY distribution. Its full name is PuTTY Key Generator. And the purpose is the generation of key pairs and their conversion to various formats.
To generate a public key, you need to run puttygen.exe, click the Load button (or select File -> Load private key from the menu) and after displaying the information in the Key window. Save the public key in the desired format.
