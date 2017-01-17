# directoryencryption
Linux shell script to encrypt directories into an archive that can be moved. 


Options:
-e: Encrypts specified file
-d: Decrypts specified file

Example of encryption:
	bash fencrypt -e mydirectory
Example of decryption:
	bash fencrypt -d myencrypteddirectory

ToDo:

-Specifying whether a target is a directory or file.
-Any input directory specified as mydirectory/ instead of mydirectory will cause an error. 
