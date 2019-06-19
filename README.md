## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Instructions](#instructions)
* [Preview](#preview)
* [Authors](#authors)

## General info

Text message encryption and decryption in image. Please refer to the design document for more detailed information about the algorithms implemented.
	
## Technologies
Project is created with:
* Visual Studio Code 1.35.1
* Python 3.7.2
* Python Pillow Library 

  **Windows Installation**
  
    ``` > pip install Pillow ```
  
  ***Mac Installation***
  
   ``` $ pip install Pillow ```
   
  ***Linux Installation***
  
   ``` $ pip install Pillow ```

## Instructions
1.  Create a text file named msg.txt. Put your secret message inside. (keep it under 1024 characters to be safe.)
2.  Run asciiToImage.py to create an image named msgImg.png.
3.  Run privateKeyGenerator.py to generate a randomly generated private key image called pk.png.
4.  Find an image of your liking and save it as pub.png.
5.  Run encrypt.py to generate eng.png (your encrypted image!).
6.  To decrypt you need to have both the private and public images that were used to make the original encrypted image in the same folder as the decrypt.py script. Run decrypt.py and you will find the original plain-text message in a file called decryptedMessage.txt.





## Authors

* Burak Can Ozter - burak.ozter@dal.ca
* Mark Hooper


	
