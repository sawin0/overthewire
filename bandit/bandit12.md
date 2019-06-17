[$]-> ssh bandit12@bandit.labs.overthewire.org -p 2220

[$]-> 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

[$]-> mkdir /tmp/sawin

[$]-> cp data.txt /tmp/sawin/data.txt

[$]-> cd /tmp/sawin

[$]-> xxd -r data.txt data.out

[$]-> file data.out

[$]-> mv data.out data.gz

[$]-> gzip -d data.gz

[$]-> file data

[$]-> bzip2 -d data

[$]-> file data.out

[$]-> mv data.out data.gz

[$]-> gzip -d data.gz

[$]-> file data

[$]-> tar -xf data

[$]-> file data5.bin

[$]-> tar -xf data5.bin

[$]-> file data6.bin

[$]-> bzip2 -d data6.bin

[$]-> file data6.bin.out

[$]-> tar -xf data6.bin.out

[$]-> file data8.bin

[$]-> mv data8.bin data8.gz

[$]-> gzip -d data8.gz

[$]-> cat data8


The password for bandit13 is: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
	

