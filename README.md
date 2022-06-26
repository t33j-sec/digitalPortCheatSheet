# digitalPortCheatSheet
## A novel attempt at a Python-based Port Cheat Sheet. 

### Project Background
So, this project was born from a lab in the Python module of ThriveDX's CyberDefense Professional Program. The original lab had you create a dictionary and ask the user which service they wanted to know the port for, and it would return the port number. The lab documentation only had 6 or so services listed, so I set out to see if anyone had already built a dict of at least well-known ports. 

My google results turned me on to two functions within the **socket** module, **getservbyname** and **getservbyport**. These modules were perfect for what I wanted to do. After some talk with my instructors, I decided that this would be a perfect opprotunity to mess around with tkinter. 


### 26JUN22 Update

Very early version of software located at Pre-Alpha.py. This is more of a PoC than anything. It will only work in one direction (Enter Service -> Get Port). 

Things to work on:

    * Add Port -> Service functionality.
    * Figure out how to not have to delete text inside submission box manually. 
    * Error Handling
      * Service/Proto not found
      * Bad input
    * Add TCP/UDP Options