1.)Crack the password of attached file using John the Ripper (just like Fcrackzip): a) using automatic password generation b) using word dictionary. 
Step 1:get the password hash 
To get the password hash to be cracked, we need to enter the command: 
$zip2john GradedLab1.zip 
  
 
Step 2:put the password hash in a text file Type the following command : 
 
$zip2john GradedLab1.zip > hash121.txt 
  
 
 
 
 
 
 
 
 
 
 
Followed by: 
$John hash.txt 
 
The command above initiates John the Ripper, a proficient password cracking tool.   
 
  
 
 
 
The txt file contains the following message:	 
  
 
