1.)Crack the password of attached file using John the Ripper (just like Fcrackzip): 

To get the password hash to be cracked, we need to enter the command: 

$zip2john GradedLab1.zip 

  ![image](https://github.com/MANISH-RAWAT4749/EthicalHacking/assets/135990621/36b7f70d-f677-46fd-8a75-6610ee820e56)

 
Step 2:put the password hash in a text file Type the following command : 

$zip2john GradedLab1.zip > hash121.txt 

![image](https://github.com/MANISH-RAWAT4749/EthicalHacking/assets/135990621/5a92c7b3-e024-4785-8bce-2ecc6cdb477b)

 



   
Step 3 : This command initiates John the Ripper, a proficient password cracking tool.
$John hash.txt 
 

 ![image](https://github.com/MANISH-RAWAT4749/EthicalHacking/assets/135990621/351926cb-3a09-4f57-b0a0-f6ee1a00834f)

 
 
 
 
 
 
The txt file contains the following message:	 


  ![image](https://github.com/MANISH-RAWAT4749/EthicalHacking/assets/135990621/72fa794c-3d21-4503-8825-5377c1bf156c)

 
