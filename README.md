# Encrypted-Steganography

![Image](https://raw.githubusercontent.com/arjunsk/Encrypted-Steganography/master/screenshot_python.png)

      This is simple python implementation of Steganograhpy using AES encryption.
      Instead of writing plain text inside the image, we write the encrypted payload. Hence the data is more secure.
      During the decryption, the user has to input the password inorder to get the decoded message.
      
**Python commands**

      #To encode a message inside your image using password
      python code.py -e picture.jpg
      
      #To decode the message (You have to enter the password)
      python code.py -d picture.jpg  
      
  Modules used:
  1. Python Image Library
  2. Crypto.cipher
