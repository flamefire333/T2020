# T2020

convert.html is the assembler which is in charge of supporting a live interace for moving T2020 Assembly to binary to hex
  The rules for the live converter is that any Assembly should create hex that can be turned back into the original Assembly, please try to adhere to them if you change the converter
  
debug.html runs a series of hex commands by first storing them as an index array and then incrementing through the array.

--Setting Up a Working/Testing Directory--
If you're running the files on your own computer you can just edit them in any editor and open them like any other webpage

If you're on the CS machines you need to put them in your public_html folder (or some subdirectory) and then run the following two commands while in the directory with the files:

chmod o+x *

chmod o+r *


These make all the files executable and readable so you can access them by URL.
