1.)Crack the password of attached file using John the Ripper (just like Fcrackzip): 

To get the password hash to be cracked, we need to enter the command: 

$zip2john GradedLab1.zip 

  ![image](https://github.com/MANISH-RAWAT4749/EthicalHacking/assets/135990621/36b7f70d-f677-46fd-8a75-6610ee820e56)

 
Step 2:put the password hash in a text file Type the following command : 
 
$zip2john GradedLab1.zip > hash121.txt 
  
 
 
 
 
 
 
 
 
 
 
Followed by: 
$John hash.txt 
 
The command above initiates John the Ripper, a proficient password cracking tool.   
 
  
 
 
 
The txt file contains the following message:	 
  
 
