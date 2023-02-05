# kpcap

This project reads all the details of network interfaces and stores them under an S3 bucket.It basically runs as double container in a pod;

## Components;
1-) Tcpdump
2-) watcher 

tcpdump command sniff the network and watcher detect the journal files and uploads them to the S3.

<a href="https://github.com/WoodProgrammer/pcap-journal">Pcap Journal</a>
