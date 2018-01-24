# CS405-checkers-ai


Binary to tile conversion

1 = 001 => _  
2 = 010 => b  
3 = 011 => B  
4 = 100 => r  
5 = 101 => R  

The Board will be stored as a 12 byte glob of data.  
##### Encoding  
Use binary AND followed by a left shift.  

##### Decoding  
Binary AND the data with 7 (111) to get the right-most tile, then right shift.
