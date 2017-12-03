# cs653hw3

The whole challenge I would say is understanding headers.

First I study how the headers work. I use this
http://www.binarytides.com/raw-socket-programming-in-python-linux/
when I implement my code for sending a SYN packet.

Then for receiving I use http://www.binarytides.com/python-packet-sniffer-code-linux/ as reference of how to receive packet
Honestly, most of the time I just keep tweaking things until it works. I use Wireshark to debug and monitor the packets to make sure that I am doing the right thing.

My approach is first send a SYN packet, then if I get SYN-ACK, then I send HTTP GET. Then I will parse the result.
