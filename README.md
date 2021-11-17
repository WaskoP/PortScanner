# PortScanner
A basic port scanner which scans for open ports on a specified network.

Created with PyCharm. To test, extract PortScanner to your PyCharm project folder and execute main.py.

It will create 2 text files which were for a scenario where I wanted to reserve some IP addresses for printers on a network, print out those IP's as well as all the other available host IP's on the subnet. Ignore this if just interested in port scanning functionality.

The program will ask for you to input the network you wish to scan including subnet mask. By default it will only scan for open ports 80 and 23 on the specified network. If different ports are to be scanned, this can be easily edited within the code.

Once port scanning for that network is complete it will ask if you would like to scan a single host for open ports range 1 - 1025. If yes, then enter the host IP and it will scan ports 1 - 1025 for any open ports. If no then the program will terminate.

Feel free to use this code however you please.

-WaskoP
