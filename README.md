# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![image](https://github.com/user-attachments/assets/c52ee7e7-dca4-4d1b-93e8-06634ea979c9)

## OUPUT - ARP
![image](https://github.com/user-attachments/assets/e0885a48-436c-4b93-ae69-4e35c0aaa182)

## PROGRAM - RARP
![image](https://github.com/user-attachments/assets/372a8d97-5853-437e-ad1b-b5e59879d41e)

## OUPUT -RARP
![image](https://github.com/user-attachments/assets/f84d2ae4-23ae-4684-8ac0-579da2973a7f)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
