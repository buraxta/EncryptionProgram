# EncryptionProgram
You're asked for options below:  

(N)ewKey,(G)etKey,(E)ncrypt,(D)ecrypt,(Q)uit
And according to your answer process's handled.  

Logic is not so hard;  
* First we create a list which contain characters from ASCII table starts 32 to 127 (because it's not useful for us to use values below 32)
* then we shuffle the firs list using Collections class
* thanks to nested for loop we determine which character equals within the shuffled list by index
* for encryption, we replace given value with new characters within this shuffledList
* for encryption we use this shuffledList as a key, without this list, we can't decryp any part of message

*this whole logic is created by bro code
