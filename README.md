# HTTP-server-and-chat-application-CO3094-
This is Assignment 1 of the Computer Networks course at Ho Chi Minh City University of Technology – VNU. This project was completed by a team of four members.



run server 
make sure port 9000 is free

python start_tracker.py --server-ip 192.168.56.1 --server-port 9000

python start_tracker.py --server-ip 10.123.176.214 --server-port 9000

run peer
make sure port 6000(the port of peer) is free
python peer.py --server-ip 127.0.0.1 --server-port 9000 --peer-ip 127.0.0.1 --peer-port 6000

python peer.py --server-ip 192.168.56.1 --server-port 9000 --peer-ip 192.168.56.1 --peer-port 6002

python peer.py --server-ip 192.168.56.1 --server-port 9000 --peer-ip 192.168.56.1 --peer-port 6003


python peer.py --server-ip 10.123.176.215 --server-port 9000 --peer-ip 10.123.176.215 --peer-port 6000

python peer.py --server-ip 10.123.176.216 --server-port 9000 --peer-ip 10.123.176.216 --peer-port 6002

python peer.py --server-ip 10.123.176.217 --server-port 9000 --peer-ip 10.123.176.217 --peer-port 6003