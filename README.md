# mednafen-server-raspberry-pi
mednafen-server-raspberry-pi

Server for raspbian issue 8 and issue 9

# Server side
Run the server : mednafen-server standard.conf
Your server is at 192.168.123.100 


# Client side
$ mednafen "$1"
press 't'
and type: 
 /connect 192.168.123.100
 
 Alternatively one can type the command line: mednafen  -vdriver sdl -connect -netplay.host 192.168.123.100  "$1" 
  

# Conclusion
Mednafen is perfect for 1, 2, 3 up to 4 players. 
(fceux, in comparison, is rather with several bugs still and not well working for netplay)

Mednafen Server for 4p is OK, great and it will work on Raspberry. The Netplay of Mednafen was successfully tested with 4 clients over network with mednafen 0.9.41 using 4 x PI Boxes and one PI server. 
No increase of temperature of Pi was noticed on 8b, which is perfect.


# References
More info on Wikipedia and mednafen websites: 

https://en.wikipedia.org/wiki/NES_Four_Score

https://mednafen.github.io/documentation/netplay.html

