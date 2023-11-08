System requires python3

sudo apt install python3-pip
sudo pip3 install pycryptodome

first open a terminal in a linux distro like ubuntu and run the line with the key being 16-byte:
python3 server.py <port number> <key>

once it starts listening open another tab or window terminal and run the line using the same port number and key as the :
python3 client.py <ip> <port number> <key>

when it prompts you to enter a message, enter anything you wish to send to the server and hit enter

head to where you have the terminal with the server listening to find what was sent to the server