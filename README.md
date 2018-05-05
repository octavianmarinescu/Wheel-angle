# Wheel-angle

Server - Reads input from keyboard and associates the input with one of the 5 values below.
       - Whenever a client connects its received input is checked against the keyboard input.
       - If the two values are identical: ACK is sent
       - If the two values are different: NAK is sent

(up arrow) - Acc
(down arrow) - Break
(left arrow) - Left
(right arrow) - Right
(everthing else) - NAN

Client - Gets a random number and associates it with one of the five values below.
       - Sends the value and prints the received respons

0 - Break
1 - Acc
2 - Left
3 - Right
4 - NAN
