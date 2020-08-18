Created by Jory Anderson, Tim Salomonsson, and Purvika Dutt

# IMApplication
Establishes confidentiality, integrity, and authentication (CIA) rules by using symmetric keys, message authentication codes (MAC), and mutual authentication respectively.

* Establishes a connection between a server/client and allows the two parties to communicate securely using:
  * Confidentiality via symmetric key encryption 
  * Integrity via Message Authentication Codes 
  * Authentication via ensuring matching security parameters, as well as both server/client verifying each certificate using the provided KeyStore/KeyPairGen (mutual authentication).
    * Two user accounts are also provided: one for client and one for server. Each is stored in a local DB and verified using a hash+salt.
* The included technical manual includes instructions for building/compiling, as well as running the server and client.
