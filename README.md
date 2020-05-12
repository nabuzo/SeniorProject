# The importance of Symmetric Cyrptography.
* In this project, I am going to demonstrate the following symmetric encryption techniques: Caesar Cipher and the Avalanche Effect of AES. 
* The following techniques will illustrate the use of symmetric cryptography.

## Usage
*Installation*
* Download the following code: **_ShiftCipher.zip_** & **_AvalancheEffect.zip_** and extract it. Once extraction is complete, copy the address of the folder where it's stored. 
* Open the command prompt, type _"cd"_ and paste the address. Your system will have a different naming prompt but be sure to be in those specific folders.
![ss1](https://user-images.githubusercontent.com/60201371/81632825-ce30b280-93d0-11ea-82e3-93aa6f5d1a75.PNG)
![ss2](https://user-images.githubusercontent.com/60201371/81632903-fe785100-93d0-11ea-877a-0923a0f80e13.PNG)


*Shift Cipher*

Before anything else, make sure you can compile the program by typing **_"javac filename.java"_**. If not working, you may need to install JDK.

![ss3](https://user-images.githubusercontent.com/60201371/81634333-5ebcc200-93d4-11ea-9124-5c3ac9fe9536.PNG)

* To encrypt a text file, type the following command:
![ss4](https://user-images.githubusercontent.com/60201371/81634330-5e242b80-93d4-11ea-87be-1ca0b33771c3.PNG)
  - _"-e"_ indicates encryption.
  - _"encryptinput.txt"_ is the file you want to encrypt. **MUST BE ALL IN UPPERCASE LETTERS**. You can name your file in any name you are comfortable with
  - _"4"_ is the key on how many shifts you want it to be.
  - _"encryptoutput.txt"_ this is the encrypted file. Your encrypted file can be named anything on the command prompt.

* To decrypt a text file, type the following command:
![ss5](https://user-images.githubusercontent.com/60201371/81634332-5ebcc200-93d4-11ea-89e9-bf858b676da6.PNG)
  - _"-d"_ indicates decryption.
  - _"decryptinput.txt"_ is the file you want to encrypt. **MUST BE ALL IN UPPERCASE LETTERS**. You can name your file in any name you are comfortable with
  - _"5"_ is the key on how many shifts you want it to be.
  - _"decryptoutput.txt"_ this is the encrypted file. Your encrypted file can be named anything on the command prompt.

* All the text files must be in the same folder as the code. You should be able to find all the text file and the generated output text file in the same folder. 


*Avalanche Effect*

Before anything else, make sure you can compile the program by typing **_"javac filename.java"_**. If not working, you may need to install JDK.

![ss6](https://user-images.githubusercontent.com/60201371/81635309-8dd43300-93d6-11ea-827e-9a8677fb7154.PNG)

* To run the program, type the following command:
![ss8](https://user-images.githubusercontent.com/60201371/81725171-0e347b80-944b-11ea-9721-561b2f153691.PNG)
  - _"-c"_ indiates compare.
  - _"keypair.txt"_ is the text file that I used to compare the key and its plaintext
  - _"output.txt"_ is the output file. The output can be named anything on the command prompt. It basically shows the same output on the command prompt but in more neat way.
* The output generated a Ciphertext from the key & the plaintext. It will flipped the bit from 0 to 127, inclusively. Each flipped bit generates a new plaintext and new ciphertext, and it will shows the number of bits that's been flipped from the original plaintext & ciphertext.

## Information
*Why Cryptography is important for security?*
* "Cryptography is the science of secret writing with the goal of hiding the meaning of a message" (Understanding Cyrptography, 3). This technique allows people to have confidence in sending important information in the electronic world.
Cyrptography itself is split into three main branches: Symmetric Algorithms, Asymmetric Algorithms, and Protocol. In this project, I will be focusing on Symmetric Algorithms. 

*What is Symmetric Algorithm?*
* Symmetric Algorithm is what many people assume cryptography is all about. Two parties have an encryption and decryption method for which they share a secret key. Some examples of symmetric encryption are: Blowfish, AES, RC4, DES, RC5, and RC6. This project will show two encryption techniques which are: Caesar's Cipher (the simplest method of symmetric encryption) and Avalanche Effect of AES.

*Caesar Cipher*
* This is the first well cipher, a substitution cipher, was used by Julius Caesar around 58 BC. Caesar shifted each letter in his military commands in order to make them appear meaningless. My program works on shift cipher that determine what the key is to encrypt and decrypt the message.

*Avalanche Effect of AES*
* AES is the most widely used symmetric cipher today. It has a block cipher with 128-bit block size and supported three key lengths: 128, 192, and 56 bit. My program shows avalanche effect which is calculated by changing one bit in plaintext and keeping the key the same. It improves the level of security by changing one bit in encryption. Avalanche effect creates a combination of confusion and diffusion to enhance the security level. And this is what I would like to illustrate in my program.

    ![ss7](https://user-images.githubusercontent.com/60201371/81724264-b1849100-9449-11ea-836a-d9e29bb942eb.PNG)
* This chart is to visualize if there are any "weak" indexes for filipping a bit in a plaintext. The *average number of bits flipped is 64.758*, which is about 50%. This shows that AES Block Cipher maintains its avalanche effect for any bit flipped in the plaintext and that there is not index of bit that results in a number of flipped bits signaficantly below the goal of 64 flipped bits. 

*How does Symmetric Algorthim improved throughout the year and how it influenced our current crypto systems?*
* Symmetric Algorithm is being improved continuously every year. It is used almost everywhere to share information between a smaller number of people. However, it has a major disadvantage: transmitting the keys used to encrypt and decrypt data. When keys are shared over an unsecured network, these keys are vulnerable to being intercepted by malicious third parties. This is where researches created asymmetric encryption that uses public and private key. Where public key is available to everyone, and the private key is only known by the owner to decrypt a message that was sent to him/her. 

*Note:* All types of computer encryption are subject to vulnerabilities. Eventhough Symmetric encryption has its own flaws, it still remain a critical component of modern computer security. 


## FAQ
* **Contact Information:** abuzo_nicole@columbusstate.edu
* **Demo Link:** 


