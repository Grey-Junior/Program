# ChaCha20

First make sure you have Python installed in your computer. 
Then after you have installed it restart your computer.
Open CMD and type: pip install pycryptodome

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

First you need to have 3 files, (Encrypter.py , decrypter.py, and a file that you want to encrypt, can be a text fille or a image or even a vide, but if its in smaller size it will be better)

Encryption:

- Then open the folder where all of the 3 files are.
- Right click and select "Open in terminal" (this will open the folder in CLI)
- Now run the Encrypter.py script by typing the command 
	[python encrypter.py filename.txt password]



This will run the script and encrypt the file that you have selected, and now you will see the file you have it has been encrypted in your folder and its not readable anymore. And the script file also created a .log file where it saved the information about the file that it encrypted.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------


Decryption:

-Follow the first two steps as encryption

-Then run the command:
	[python decrypter.py filename.txt password]


- Make sure the file name is same as the file name you encrypted, otherwise it will give you an error.
- Make sure that the password is also same, otherwise it will tell you that the password is wrong.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

 
